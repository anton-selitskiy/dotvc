# Voice Conversion with Optimal Transport

This page presents our paper:

**Title:** Discrete Optimal Transport and Voice Conversion
**Authors:** Anton Selitskiy and Maitreya Kocharekar  
**PDF:** [Download paper](paper.pdf)

## Abstract
In this work, we address the voice conversion (VC) task using
a vector-based interface. To align audio embeddings between speakers,
we employ discrete optimal transport mapping. Our evaluation results
demonstrate the high quality and effectiveness of this method. Additionally,
we show that applying discrete optimal transport as a post-processing step
in audio generation can lead to the incorrect classification of synthetic
audio as real.

## Code
[GitHub Repository](https://github.com/anton-selitskiy/dotvc)

## Audio Samples
Link to examples, or embed a player using HTML.

Source and reference are up to 1 min.
<table>
  <tr>
    <th>Source</th>
    <th>Reference</th>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="audio/60_60/19-227-0072.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="audio/60_60/1455-138263-0041.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
</table>
<table>
  <tr>
    <td>
      <p>k = 1</p>
      <audio controls>
        <source src="audio/60_60/converted_audio_1_60_60/19-227-0072._19_to_1455.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <p>k = 3</p>
      <audio controls>
        <source src="audio/60_60/converted_audio_3_60_60/19-227-0072._19_to_1455.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <p>k = 4</p>
      <audio controls>
        <source src="audio/60_60/converted_audio_4_60_60/19-227-0072._19_to_1455.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <p>k = 5</p>
      <audio controls>
        <source src="audio/60_60/converted_audio_5_60_60/19-227-0072._19_to_1455.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <p>k = 10</p>
      <audio controls>
        <source src="audio/60_60/converted_audio_10_60_60/19-227-0072._19_to_1455.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <p>k = 40</p>
      <audio controls>
        <source src="audio/60_60/converted_audio_40_60_60/19-227-0072._19_to_1455.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
</table>



Source is represented by 1 utterance, reference uses 10 utterances
<table>
  <tr>
    <th>Source</th>
    <th>Reference</th>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="audio/5_0/118-47824-0026.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="audio/5_0/1040-133433-0022.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
</table>
<table>
  <tr>
    <td>
      <p>k = 1</p>
      <audio controls>
        <source src="audio/5_0/converted_audio_1_5_0/118-47824-0026._118_to_1040.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <p>k = 3</p>
      <audio controls>
        <source src="audio/5_0/converted_audio_3_5_0/118-47824-0026._118_to_1040.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <p>k = 4</p>
      <audio controls>
        <source src="audio/5_0/converted_audio_4_5_0/118-47824-0026._118_to_1040.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <p>k = 5</p>
      <audio controls>
        <source src="audio/5_0/converted_audio_5_5_0/118-47824-0026._118_to_1040.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <p>k = 10</p>
      <audio controls>
        <source src="audio/5_0/converted_audio_10_5_0/118-47824-0026._118_to_1040.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <p>k = 40</p>
      <audio controls>
        <source src="audio/5_0/converted_audio_40_5_0/118-47824-0026._118_to_1040.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
</table>


## Citation
BibTeX entry or link to citation.

---
Created with ❤️ using GitHub Pages.
