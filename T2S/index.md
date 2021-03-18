###### Please enter your email ID and rate the generated audio files
<head>
    <link rel="stylesheet" href="w3.css">
    <title>Text To Singing MOS</title>
    <style>
         h1 {
            text-align: center;
            margin: 20px;
            }
  h3{
    text-align: center;
    text-justify: inter-word;
  }
  h6{
    text-align: justify;
    text-justify: inter-word;
  }
  .grrp{
  text-align: center;
  padding: 10px;
  margin: 10px;
  border: 1px solid #c6c6c6;
    }
  .grrp1{
  text-align: center;
  padding: 10px;
  margin: 10px;
    }
    </style>
</head>
<body>
<div class="grrp1">
  <form id="fs-frm" name="survey-form-test" accept-charset="utf-8" action="https://formspree.io/f/xaylrgvl" method="post">
    <fieldset id="fs-frm-inputs" style="border:0px solid black;">
      <label for="email-address">Email Address</label>
      <input type="email" name="_replyto" id="email-address" placeholder="email@domain.com" required=""><br><br>
      <p>Listen to the original audio files of 5 different singers and provide feedback on the synthesized waveforms produced using two systems</p>
      <div class='grrp'>
       <table border="0" width="20%" style="font-size:16px">
          <tbody><tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
          Target Melody</th></tr>
          <tr><td><audio controls="" preload="none" style="height:30px">
          <source src="https://resna-2007.github.io/T2S/Singer_1/ADIZ.wav" type="audio/mpeg">audio not supported</audio>
          </td></tr></tbody></table>
      </div>
  <div class='grrp'>  
    <h3>Singer1</h3>
        <table border="0" width="20%" style="font-size:16px">
          <tbody><tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
          Singer Ground Truth</th></tr>
          <tr><td><audio controls="" preload="none" style="height:30px">
          <source src="https://resna-2007.github.io/T2S/Singer_1/ADIZ.wav" type="audio/mpeg">audio not supported</audio>
          </td></tr></tbody></table>
          <table style="width:100%; font-size:12px; text-align: left;">
          <tbody><tr>
          <th>Lyrics</th>
          <th>"Edelweiss, Edelweiss 
          Every morning you greet me
          Small and white clean and bright
          You look happy to meet me
          Blossom of snow, may you bloom and grow
          Bloom and grow forever
          Edelweiss, Edelweiss"</th>
          </tr>
          </tbody></table> <br>
          <table border="0" width="20%" style="font-size:16px">
              <tbody>
                <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
                 Model 1</th></tr>
              <tr>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://resna-2007.github.io/T2S/Singer_1/Song1.wav" type="audio/mpeg">audio not supported</audio>
                </td></tr>
              </tbody></table>
              <label for="sim_n">How well does Wavenet resemble Ground truth</label>
              <select name="sim_n" id="sim_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_n">How would you rate the speech Quality (clarity)</label>
              <select name="speech_n" id="speech_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_n">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_n" id="synth_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
    <table border="0" width="20%" style="font-size:16px">
            <tbody>
              <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">Model 2</th></tr>
              <tr>
                <td><audio controls="" preload="none" style="height:30px">
                  <source src="https://resna-2007.github.io/T2S/Singer_1/Song2.wav" type="audio/mpeg">audio not supported</audio>
                  </td></tr>
              </tbody>
            </table>
              <label for="sim_g">How well does WAVEGLOW resemble Ground truth</label>
              <select name="sim_g" id="sim_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_g">How would you rate the speech Quality (clarity)</label>
              <select name="speech_g" id="speech_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_g">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_g" id="synth_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
    </div>
    <br><br>
     <button type="submit">Send Responses</button>
     </div>