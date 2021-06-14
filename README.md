<br>
<br>
<p class="text">Below Table Shows MOS with 95% Confidence Interval.</p>
<p class="text">GT - Ground Truth Audio.</p>
<p class="text">GT (Mel + WaveRNN) - first convert the ground truth audio into mel-spectrograms, and then convert the mel-spectrograms back to audio using WaveRNN.</p>

<br>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Method</b></td>
      <td style="text-align: center"><b>MOS_LQO (Narrowband)</b></td>
      <td style="text-align: center"><b>MOS_LQO (WideBand)</b></td>      
    </tr>
    <tr>
      <td style="text-align: center"><i>GT</i></td>
      <td style="text-align: center">4.549 &#177; 0.00</td>
      <td style="text-align: center">4.644 &#177; 0.00</td>      
    </tr>
    <tr>
      <td style="text-align: center"><i>GT (Mel + WaveRNN)</i></td>
      <td style="text-align: center">1.119 &#177; 0.0476</td>
      <td style="text-align: center">1.0441 &#177; 0.01867</td>      
    </tr>
    <tr>
      <td style="text-align: center"><i>FastSpeech (Mel + WaveRNN)</i></td>
      <td style="text-align: center">1.07393 &#177; 0.00958</td>
      <td style="text-align: center">1.0348 &#177; 0.00678</td>      
    </tr>    
  </tbody>
</table>
<br>
## Below are audio predictions 
<br>
<p class="text">1. इसी में ऊँचे अफसरों को आजकल कंप्यूटर की ट्रेनिंग दी जा रही है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/38_2_44_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/38_2_44_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/38_2_44.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">2. स्नैपचैट को मेरे फ़ोन से डिलीट कर दो </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/69_2_65_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/69_2_65_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/69_2_65.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">3. वहीं पोस्को ने ओड़िशा में बावन करोड़ रुपये के निवेश से इस्पात संयंत्र लगाने का प्रस्ताव किया है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/6_1_26_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/6_1_26_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/6_1_26.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">4. मेरे कल के सरे अलार्म चालू कर दो </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/74_3_60_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/74_3_60_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/74_3_60.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">5. सचिन पायलट ने मीडिया से कहा राजस् थान सरकार ने छह सौ और पचास तीन माइन आवंटित की </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/6_2_4_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/6_2_4_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/6_2_4.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">6. पंजाब के सभी सांसदों की तुलना में मैंने सांसद निधि सबसे ज्यादा खर्च की है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/81_1_133_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/81_1_133_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/81_1_133.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">7. इसलिए अब चाची के कलंक को लोग भूलने लगे थे </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/32_4_83_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/32_4_83_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/32_4_83.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">8. फिर झोला पत्नी को देकर टार्च जलाते बुझाते गढ़ी की ढलान पर उतरने लगते हैं </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/32_1_248_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/32_1_248_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/32_1_248.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">9. पुलिस ने कंपनी प्रबंधक और ठेकेदार के खिलाफ लापरवाही का मामला दर्ज कर लिया है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/61_4_91_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/61_4_91_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/61_4_91.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">10. बोले आपके परागी को अभी देखकर चला आ रहा हूँ </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/44_2_26_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/44_2_26_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/44_2_26.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">11. उसे हारों पुष्प गुच्छों से सम्मानित किया जा रहा है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/20_2_85_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/20_2_85_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/20_2_85.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">12. एचबीओ नाउ पे टीवी सीरीस दिखाओ </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/72_3_137_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/72_3_137_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/72_3_137.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">13. अगर सरकार इस दिशा में आगे कदम बढ़ाती है तो फेडरेशन उसका पुरजोर विरोध करेगी </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/58_3_97_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/58_3_97_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/58_3_97.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">14. मैं कहता अब मैं टोप उतार देता हूँ तो ठहाका लगता </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/16_3_65_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/16_3_65_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/16_3_65.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">15. इस प्रश्न पर आकर उसके दिल के पांव थम जाते </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/25_1_66_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/25_1_66_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/25_1_66.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">16. वह हर समय उदास रहती है किसी से बोलती नहीं </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/9_2_22_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/9_2_22_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/9_2_22.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">17. उससे पूछताछ करने का प्रयास किया गया लेकिन वह बार बार बेहोश हो रही है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/84_1_158_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/84_1_158_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/84_1_158.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">18. तुम्हें कुछ भी अच्छा नहीं लगता धन भोजन परिवार मनोरंजन </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/26_1_127_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/26_1_127_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/26_1_127.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">19. वह अपनी फरारी काटकर आराम से निकल जाते हैं </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/49_4_199_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/49_4_199_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/49_4_199.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">20. हॉसिटल में आशीर् तुरंत अपने क्तपता को पहचान गया </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/53_2_276_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/53_2_276_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/53_2_276.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">21. मैंने चुडिय़ा दी और निकली प्लास्टिक की चुडिय़ांउन्होंने बताया कि मैंने हाथ की चुडिय़ां खोली </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/87_4_217_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/87_4_217_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/87_4_217.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">22. यही नहीं मुख्य चौराहे पर हर समय दो से तीन यातायातकर्मी भी तैनात रहते है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/82_1_171_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/82_1_171_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/82_1_171.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">23. वो चुनावी मुहिम की रणनीति भी बनाएंगी और साथ साथ सड़कों पर मतदाताओं के बीच भी नजर आएंगी </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/2_2_104_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/2_2_104_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/2_2_104.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">24. मुझे लेस ट्रैफिक वाले रूट से असफ अली रोड ले के चलो </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/71_3_157_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/71_3_157_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/71_3_157.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">25. किड्स मूवी देखने के लिए टीवीएफ खोलो </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/68_2_74_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/68_2_74_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/68_2_74.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">26. रसिक और हितैषी मित्र मोहल्ला में एकत्र भी हो गए हैं </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/11_1_163_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/11_1_163_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/11_1_163.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">27. इस मरे को भी कर्ड कर्ड मेरे ही घर के सामने करना है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/23_2_92_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/23_2_92_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/23_2_92.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">28. देखो अगर कॉल कृष्णा का है तो रिसीव करो </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/74_2_91_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/74_2_91_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/74_2_91.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">29. अमेरिका के शहर इंडियाना की ऐले मेयर अपनी प्रेगनेंसी जांच के लिए अस्पताल में पहुंची </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/59_4_74_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/59_4_74_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/59_4_74.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">30. बड़ा होने के दौरान मैं ड्राइवर हुआ करता था </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/45_2_179_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/45_2_179_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/45_2_179.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">31. यह एक चार गीगाहर्त्ज क्वॉड कोर स्नैपड्रैगन प्रोसेसर और एक जीबी रैम पर चलता है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/82_1_189_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/82_1_189_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/82_1_189.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">32. उसने गहरी साँस ली कौन सोचेगा ये भी थक जाती होंगी </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/24_1_28_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/24_1_28_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/24_1_28.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">33. छितरे छितरे इन घरों में पहले मैं खूब जाती थी </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/11_2_115_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/11_2_115_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/11_2_115.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">34. जो भी आदेश मिले पार्टी का उसे शिरोधार्य करके काम में लग जाओ </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/21_1_151_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/21_1_151_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/21_1_151.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">35. बैठक की अध्यक्षता खंड प्रधान जगदीश सैनी ने की </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/46_1_159_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/46_1_159_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/46_1_159.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">36. बताया जा रहा है कि उसके बाद नौ मार्च को गोकुलवासी छड़ी मार होली खेलेंगे </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/82_1_47_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/82_1_47_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/82_1_47.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">37. जैसे नारेनुमा सस्वर गीत से मुझे इक्कीस तोपों की सलामी दी </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/39_2_147_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/39_2_147_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/39_2_147.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">38. सबसे पहले मां सरस्वती के प्रतिमा पर माल्यार्पण एवं फिर अतिथियों के स्वागत किया गया </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/78_7_20_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/78_7_20_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/78_7_20.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">39. बनारस से हल्दिया तक एक हजार छह सौ बीस किमी जलमार्ग मार्ग तैयार करना है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/88_6_128_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/88_6_128_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/88_6_128.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">40. रोज आधे घंटे का अभ्यास इसमें मददगार साबित होगा </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/49_4_79_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/49_4_79_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/49_4_79.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">41. रिया का संपर्क अपडेट करो </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/62_1_111_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/62_1_111_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/62_1_111.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">42. इसके अलावा पांच शिक्षाकर्मियों को गिरफ्तार भी किया गया </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/48_1_33_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/48_1_33_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/48_1_33.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">43. लोग अपने आप को असुरसक्षत महसूस करने लगे हैं </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/53_2_419_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/53_2_419_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/53_2_419.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">44. होंठ तिरछे होने लगे थे और वह सीधे रखने की पुरजोर कोशिश कर रहा था </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/27_2_102_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/27_2_102_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/27_2_102.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">45. सो प्रायः उन्हीं की जिम्मेदारी में होता है यह आयोजन </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/29_1_135_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/29_1_135_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/29_1_135.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">46. पार्टी के सचिव दीपक मिश्रा कहते हैं कि पार्टी ने कई उतार चढ़ाव देखे हैं </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/78_7_175_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/78_7_175_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/78_7_175.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">47. गुरु नगरी और यहां के लोगों के प्रति मेरी प्रतिबद्धता है और यह ताउम्र रहेगी </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/86_1_135_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/86_1_135_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/86_1_135.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">48. कहते हुए वह अपनी मूसी हुई सफेद सूती शर्ट धीरे धीरे उतारता है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/22_2_1_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/22_2_1_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/22_2_1.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">49. टाइपराइटर को ठीक किया और टाइप करने में मशगूल हो गई </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/24_2_193_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/24_2_193_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/24_2_193.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">50. भाजपा की विधानसभा में एक सौ छियासठ सदस्य हैं </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/45_4_13_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/45_4_13_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/45_4_13.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">51. ओला से एक रेंटल्स बुक करो </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/72_3_7_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/72_3_7_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/72_3_7.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">52. क्या मोदी यहां विदेशी मेहमानों की मेजबानी छोड़ देंगे </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/49_1_195_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/49_1_195_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/49_1_195.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">53. मिसेज रामरक्षा बहुत देर तक इन्हीं विचारों में डूबी रही </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/28_4_176_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/28_4_176_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/28_4_176.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">54. मैंने कल ओ एल एक्स कपडे मंगवाए है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/71_6_33_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/71_6_33_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/71_6_33.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">55. यही कारण है कि उन्हें तमाम प्रयासों के बाद बीस वें ओवर में सात विकेट गंवाकर जीत मिली </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/6_1_64_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/6_1_64_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/6_1_64.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">56. पैनोरमा मोड में सेल्फी लें </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/68_3_58_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/68_3_58_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/68_3_58.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">57. मेरे मन में विचार कौंधा कि अब वह बापू का गला घोंट देगी </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/27_3_22_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/27_3_22_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/27_3_22.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">58. उन्होंने इस मसले को राष्ट्रीय स्तर पर उठाने वाली मुस्लिम बहनों को भी बधाई दी </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/88_4_46_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/88_4_46_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/88_4_46.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">59. उन्होंने कहा हमें यह नहीं भूलना चाहिए कि कोई भी धर्म नफरत और ङ्क्षहसा करना नहीं सिखाता है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/4_1_52_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/4_1_52_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/4_1_52.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">60. तो फिर क्यों मांगे पुलिस कंट्रोल रूम से मदद </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/45_4_117_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/45_4_117_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/45_4_117.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">61. इतनी राहत जरूर है कि कभी कभार मुझे ये सारी घटनाएँ अविश्वसनीय लगने लगती हैं </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/21_2_62_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/21_2_62_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/21_2_62.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">62. अब भागवाली कहाकर दादी अपने कर्मों से अपने पति का भाग्य क्यों खराब करतीं </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/31_2_52_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/31_2_52_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/31_2_52.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">63. फिल्म रेड की शूटिंग हम लोग पन्द्रह सितंबर से लखनऊ में शुरू कर रहे हैं </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/78_2_160_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/78_2_160_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/78_2_160.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">64. खारघर रेलवे स्टेशन से मोबोर तक पहुचने में कितना वक़्त लगेगा </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/74_1_87_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/74_1_87_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/74_1_87.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">65. प्रत्यक्ष कर संग्रह अप्रैल नवंबर के दौरान पन्द्रह बढ़ा </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/45_4_76_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/45_4_76_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/45_4_76.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">66. निम्स हॉस्पिटल से गोमतीनगर तक पहुचने में कितने मिनट लगेगा </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/71_2_173_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/71_2_173_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/71_2_173.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">67. यह यूएसबी तीन शून्य रीडर और अधिकतम गति से डाऊनलोड करने की गारंटी देता है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/87_1_9_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/87_1_9_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/87_1_9.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">68. उन्होंने कहा कि नगरोटा बगवां में फार्मेसी संस्थान में इसी सत्र से कक्षाएं आरंभ होंगी </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/84_3_119_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/84_3_119_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/84_3_119.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">69. पुलिस ने दीपक के मोबाइल पर वह मेसेज देखा </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/47_5_67_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/47_5_67_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/47_5_67.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">70. मुस्लिम या ईसाई तो शायद पूरे मधू विहार में गिने चुने ही थे </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/29_3_96_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/29_3_96_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/29_3_96.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">71. दूसरे कालेजों में स्टूडैंट्स के दाखिला लेने के कारण भी खाली रह जाती हैं सीटें </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/80_2_70_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/80_2_70_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/80_2_70.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">72. अरे एक संस्कार और शर्म की चीज इन में नही होती </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/30_1_120_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/30_1_120_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/30_1_120.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">73. रिंग वॉल्यूम ऑन है या ऑफ </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/68_2_89_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/68_2_89_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/68_2_89.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">74. नेफ्ट या आई पी के लेनदेन को प्राथमिकता दी जाती है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/48_3_66_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/48_3_66_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/48_3_66.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">75. वे तथ्यों की समझ विकसित करने तथा उन्हें सरलता से समझाने पर विश्वास करते थे </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/31_4_30_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/31_4_30_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/31_4_30.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">76. स्लॅक ओपन करके सेव्ड ड्राफ्ट अज़ीज़ को भेज दो </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/64_3_116_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/64_3_116_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/64_3_116.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">77. अपराधियों पर न तो एनकाउंटर का फौफ दिख रहा है और न ही कानून का </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/84_1_76_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/84_1_76_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/84_1_76.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">78. वो जी बस तो आपको अंबाला कैंट पर ही छोड़ देगी </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/40_1_238_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/40_1_238_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/40_1_238.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">79. वैसे हिटलर जब जिंदा था तो उसकी तानाशाही और यातनाओं से लोग सहम जाते थे </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/86_1_107_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/86_1_107_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/86_1_107.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">80. ररया ने भी इस कैक्तटगरी में जीत हाससल की </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/54_1_8_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/54_1_8_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/54_1_8.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">81. हमारी पार्टी के बहुत सारे लोग जेल आते रहते हैं </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/31_3_126_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/31_3_126_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/31_3_126.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">82. कैसे हाथ में रहें शहरी उलझ गए हैं मोदी </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/46_3_98_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/46_3_98_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/46_3_98.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">83. सच में था ही नहीं या फिर है ही नहीं </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/10_3_162_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/10_3_162_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/10_3_162.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">84. चौदह अंग्रेज़ी काव्य संग्रह पाँच अंग्रेज़ी साहित्यालोचना पुस्तकें पाँच अंग्रेज़ी साहित्यालोचना संपादित पुस्तकें </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/36_2_131_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/36_2_131_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/36_2_131.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">85. यह कवायद सशकायतों के बाद शुरू की गई है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/51_4_53_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/51_4_53_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/51_4_53.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">86. गज़ल लगा दो साउंड क्लाउड एप पे </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/73_1_125_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/73_1_125_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/73_1_125.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">87. आचार्य को दया आ गयी बोले वी सी साहब मैं आपका बहुत आदर करता हूँ </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/17_2_96_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/17_2_96_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/17_2_96.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">88. मैन कैमरा से बूमरैंग कैप्चर करें </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/64_6_127_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/64_6_127_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/64_6_127.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">89. चौधरी की हवेली का दरवाजा कभी बंद नहीं होता था </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/9_1_28_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/9_1_28_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/9_1_28.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">90. काश आपने मरते समय का उसका मुस्कराता चेहरा उसका असीम हर्ष देखा होता </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/33_1_178_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/33_1_178_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/33_1_178.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">91. छूने पर कंपन को डिक्रीस कर दो </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/76_2_111_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/76_2_111_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/76_2_111.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">92. अंग्रेजी और संस्कृत वाक्यांशों का प्रयोग भी सबसे अलग था </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/23_1_76_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/23_1_76_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/23_1_76.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">93. बोधिसत् व के इस संग्रह में देशज अनुभवों की दुनिया है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/38_3_44_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/38_3_44_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/38_3_44.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">94. उस समय न तो कोई भी मक्तहला नेता क्तनवातचत </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/55_1_1_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/55_1_1_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/55_1_1.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">95. उनकी आवाज की तरह मुझे कोई मोह नहीं सकता </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/49_4_14_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/49_4_14_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/49_4_14.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">96. ईश्वर की लीला है और मनुष्य बने रहने का कर्तव्य भी </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/30_3_48_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/30_3_48_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/30_3_48.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">97. विनय को अब आक्रमण पंक्ति की धुरी बनकर टीम की जीत में योगदान देना होगा </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/79_3_49_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/79_3_49_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/79_3_49.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">98. उन्नत चरण यह चरण धनुष बाण के आविष्कार से शुरू हुआ </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/36_2_78_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/36_2_78_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/36_2_78.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">99. कोई कुछ कहे पति की तो राजकुमारी हैं ईशा </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/47_1_156_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/47_1_156_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/47_1_156.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">100. वहाँ रास्ता भी कुछ ज्यादा ही सँकरा हो गया था </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/42_1_99_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/42_1_99_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/42_1_99.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">101. लाल भात किसी जमाने में गरीब के खाने का एक मात्र भोजन हुआ करता था </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/35_1_14_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/35_1_14_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/35_1_14.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">102. मानवीय गुणों को प्रदूषित करता है और आंतरिक मिठास को क्षीण </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/26_3_49_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/26_3_49_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/26_3_49.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">103. टाइम लैप्स मोड में पिक्चर लो </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/65_1_18_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/65_1_18_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/65_1_18.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">104. शहर के दूर दराज क्षेत्रों एवं गाँवों से रोज यहाँ सैकड़ों लोग जमा होते थे </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/27_2_104_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/27_2_104_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/27_2_104.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">105. दो हजार तेरह के चुनावों में प्रधानमंत्री नवाज शरीफ की पार्टी की जीत हुई थी </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/57_1_160_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/57_1_160_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/57_1_160.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">106. मेलगुदालुर से हुसैन सागर लेक तक का बाइक रास्ता बताओ </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/69_3_276_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/69_3_276_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/69_3_276.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">107. लड़कियां ज्यादतर धागे के बने बैंड पसंद करती हैं </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/45_3_155_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/45_3_155_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/45_3_155.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">108. बस में हुए इस ब्लास्ट में एक व्यक्ति और उसकी पत्नी घायल हो गए थे </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/78_7_79_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/78_7_79_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/78_7_79.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">109. पलक झपकते जाने किधर से आते हैं और पलक झपकते ही फुर्र हो जाते हैं </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/18_2_60_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/18_2_60_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/18_2_60.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">110. मैप पर सर्च करो क्या मेरे आस पास कोई हॉस्पिटल है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/69_1_163_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/69_1_163_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/69_1_163.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">111. दिल्ली के कई इलाको को बुधवार और गुरुवार को पेयजल संकट का सामना करना पड़ेगा </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/88_5_151_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/88_5_151_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/88_5_151.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">112. सारे ड्राफ्ट को हटाए करो </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/76_5_9_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/76_5_9_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/76_5_9.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">113. उसे इसी आशय की लिखी जावेद अख्तर की नज्म याद आई </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/38_3_192_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/38_3_192_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/38_3_192.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">114. कांग्रेस प्रत्याशी जितना अधिक वोट पाएंगी सपा को ही उसका नुकसान झेलना पड़ सकता है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/87_5_165_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/87_5_165_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/87_5_165.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">115. सात आठ महीने पहले बहादुरगढ़ से कमांडो को गोली मारकर उसकी गाड़ी छीन ली थी </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/83_1_4_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/83_1_4_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/83_1_4.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">116. लोकायुक्त ने इन अफसरों के खिलाफ भी संयुक्त टीम से जांच की संस्तुति की है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/87_5_192_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/87_5_192_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/87_5_192.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">117. उसने पूछा कि जंगल में मोर नाचा तो उसे किसने देखा </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/44_1_68_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/44_1_68_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/44_1_68.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">118. भाजपा प्रदेश नेतृत्व ने स्थानीय स्तर पर चर्चाओं का प्रारंभिक दौर पूरा कर लिया है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/77_1_81_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/77_1_81_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/77_1_81.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">119. कार बुक कर दो ईज़ी कॅब्स से </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/76_2_252_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/76_2_252_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/76_2_252.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">120. भक्ति आंदोलन के उदय के बारे में एक बात और ध्यान देने लायक है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/41_1_79_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/41_1_79_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/41_1_79.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">121. कम नम्बर पर कई स्टूडेंट्स तनाव ग्रस्त होकर आत्म हत्या जैसे कदम उठा लेते थे </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/82_4_48_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/82_4_48_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/82_4_48.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">122. सुदर्शना ने कहा मेरे स्वामी मुझे भरोसा है सब कुछ अच्छा ही होगा </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/41_1_56_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/41_1_56_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/41_1_56.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">123. उसका बाप गाँव के एक ठाकुर के यहाँ हरवाही करता है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/41_1_32_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/41_1_32_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/41_1_32.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">124. इधर मेरठ जीआरपी को जब रेलवे स्टेशन पर चार बच्चे दिखे तो कुछ शक हुआ </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/88_1_20_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/88_1_20_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/88_1_20.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">125. उन्हें विजेता घोषित किया गया है जबकि उपविजेता का खिताब ऋषभ सिन्हा के नाम रहा </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/88_6_31_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/88_6_31_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/88_6_31.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">126. समय और स्थिति की परवाह न कर मैंने उसे हृदय से चिपका लिया </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/27_3_77_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/27_3_77_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/27_3_77.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">127. लोकसभा उसी सत्र में उसे पाररत कर चुकी थी </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/53_2_83_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/53_2_83_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/53_2_83.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">128. गजर बजता है और सुल्तान उसकी आवाज़ से डर जाता है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/36_3_203_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/36_3_203_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/36_3_203.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">129. इतने दिनों के संबंधों के बाद मना थोड़े ही करेंगे दोनों बूढ़ा बूढी क्यों </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/27_4_4_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/27_4_4_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/27_4_4.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">130. टिन्नी चुप कर क्या पटर पटर बोलती है सारा दिन </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/44_4_91_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/44_4_91_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/44_4_91.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">131. कहते हैं कि कोई एक कुआँ था जो लाशों से पाट दिया गया था </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/20_1_127_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/20_1_127_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/20_1_127.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">132. उसमें काशीनाथ सिंह अपने जीवन की एक बात बताते हैं </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/42_2_166_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/42_2_166_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/42_2_166.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">133. वी चैट पे यह डॉक्यूमेंट भेज दो </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/74_5_163_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/74_5_163_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/74_5_163.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">134. अरे दो दरख्वास्तें ही लिख दीं तो दस रुपये हो गए </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/31_1_126_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/31_1_126_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/31_1_126.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">135. सोचता हूँ तो तुम दोनों पर ममता घनी होती जाती है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/29_3_62_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/29_3_62_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/29_3_62.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">136. जबकि घटनास्थल से पुलिस की एफएसएल टीम ने वारदात के संबंध में साक्ष्य जुटाए है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/60_2_173_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/60_2_173_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/60_2_173.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">137. हरि ने मुझसे पूछा क्या उनकी पत्नी रूखे स्वभाव की है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/15_2_75_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/15_2_75_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/15_2_75.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">138. इसलिए किसी तालाब की सफाई नहीं हो सकी है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/45_3_139_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/45_3_139_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/45_3_139.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">139. बदमाशों ने घर की नौकरानी तक को नहीं बख्वा </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/56_1_132_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/56_1_132_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/56_1_132.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">140. कुंजरू इस काम को कहीं अच् छी तरह सँभाल सकते हैं </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/24_2_184_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/24_2_184_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/24_2_184.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">141. समुद्र शास्त्र के अनुसार जिस पुरुष के हाथों की उंगलियां सीधी और लचीली होती है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/87_3_27_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/87_3_27_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/87_3_27.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">142. बाद में सूचना मिली थी जिस पर भीनमाल से पुलिस भी मौके पर पहुंची है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/88_1_23_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/88_1_23_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/88_1_23.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">143. सिर्फ़ जी ही नहीं रहे है हँस भी रहे हैं </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/44_3_239_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/44_3_239_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/44_3_239.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">144. साथ ही दफ्तर गेस्ट हाउस आदि में गमले और कूलरों की समुचित सफाई कराने को भी कहा है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/6_2_7_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/6_2_7_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/6_2_7.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">145. इस मौके पर मीडिया ने उनकी बड़ी पुत्री जाह्ववी से बात करने की कोशिश की </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/58_2_82_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/58_2_82_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/58_2_82.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">146. मेरे विचारों की सूपरफास्ट गाड़ी यू जाती हवा की तरह तुम्हारे दिमाग के प्लेटफार्म पर </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/43_1_171_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/43_1_171_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/43_1_171.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">147. होली दिवाली दशहरा तो साल दर साल आता जाता रहता है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/20_1_104_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/20_1_104_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/20_1_104.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">148. एक हजार नौ सौ सोलह में विवाह विवाह के कारण कुछ दिन शिक्षा स्थगित रही </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/14_2_110_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/14_2_110_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/14_2_110.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">149. थंडरबर्ड ओपन करके सेव्ड ड्राफ्ट नेहा को भेज दो </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/70_1_196_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/70_1_196_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/70_1_196.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">150. इसमें कहा था कि वह स्कूल गया था और उसके पिता खेत पर गए थे </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/85_2_178_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/85_2_178_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/85_2_178.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">151. उस रात रूथ ने सेंट अंथोनी से जाने किस चमत्कार की प्रार्थना की </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/29_2_183_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/29_2_183_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/29_2_183.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">152. शेर बब् बर ने कहा उस रास् ते पर चलोगे तो समझ लो </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/43_2_179_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/43_2_179_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/43_2_179.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">153. मार्केट एक्सचेंज रेट्स के लिहाज से भारत की हिस्सेदारी केवल दो पाँच पर्सेंट की है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/78_2_12_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/78_2_12_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/78_2_12.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">154. मेरे फ़ोन में विउ डालो में सिनेमा देखना चाहता हूँ </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/73_3_24_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/73_3_24_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/73_3_24.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">155. व्रत उपवास रखे जाते दिन दिशा देखकर मुरादें बोली जातीं </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/27_2_17_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/27_2_17_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/27_2_17.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">156. उन्होंने कहा कि हिंदू महासभा को लठ्ठ ईंट तलवार जो इकठ्ठा करना है कर लें </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/59_4_192_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/59_4_192_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/59_4_192.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">157. केकरौ पता त छेलै नै कि असली बात की छेकै </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/31_3_180_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/31_3_180_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/31_3_180.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">158. जबकि मैं निजी क्षेत्र में आया ही इसलिए कि मुझे पैसा चाहिए </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/17_1_7_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/17_1_7_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/17_1_7.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">159. सेवाएं और फीडबैक बंद करो </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/76_2_153_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/76_2_153_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/76_2_153.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">160. उसने हृदय में घुस जानेवाली आँखों से एक बार राजा की ओर देखा </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/17_1_27_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/17_1_27_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/17_1_27.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">161. इसकी खोपड़ी उल्टी दिशा में चलने को हर समय तैयार रहती है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/37_2_230_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/37_2_230_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/37_2_230.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">162. दूसरा पास आ कर स्नेह के स्वर में कहता है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/7_2_109_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/7_2_109_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/7_2_109.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">163. उसके कुछ दिनों बाद की घटना तो और भी उदंडता से घटी थी </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/12_1_40_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/12_1_40_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/12_1_40.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">164. साथ ही स्वच्छन्द पुरुष स्वच्छन्द नारी के वश में अधिक रहते हैं </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/30_2_189_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/30_2_189_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/30_2_189.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">165. जस्ट कॅब को मेरे फ़ोन से डिलीट करिये </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/70_1_156_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/70_1_156_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/70_1_156.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">166. आपने ही तो इन पेड़ों के नाम अभिषेक और राहुल रखे थे </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/10_3_83_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/10_3_83_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/10_3_83.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">167. तड़पकर वह उस घर के आँगन में कूदा और तेजी से दालान की तरफ बढ़ा </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/31_2_134_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/31_2_134_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/31_2_134.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">168. पत्रकार गौरी ने राणा आयुब की किताब गुजरात फाइल्स का कन्नड़ वर्जन प्रकाशित किया था </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/58_2_30_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/58_2_30_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/58_2_30.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">169. इस्लाम अपनाकर दीन मोहम्मद बन गया था सुंदर सिंह </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/49_4_11_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/49_4_11_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/49_4_11.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">170. काले निशान पर दो तीन फूँक मारी और चल पड़ा </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/36_3_67_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/36_3_67_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/36_3_67.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">171. चार एक्स डिजिटल ज़ूम पर एडजस्ट करो </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/75_1_260_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/75_1_260_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/75_1_260.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">172. गुरूजी ने भी उसे सहयोग एवं मार्गदर्शन का पूरा आश्वासन दिया </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/23_2_51_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/23_2_51_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/23_2_51.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">173. यहां तक कि उनके निधन की अफवाह भी देर रात सोशल मीडिया पर आती रही </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/57_1_33_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/57_1_33_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/57_1_33.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">174. जोकोक्तवच ने मे को हराकर छठी बार लखताब जीता </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/52_1_18_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/52_1_18_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/52_1_18.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">175. सामान्य ओबीसी श्रेणी के उम्मीदवारों को एक सौ रुपए </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/46_3_102_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/46_3_102_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/46_3_102.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">176. मैन कैमरा ओपन करो एक बूमरैंग बनाओ </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/74_5_190_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/74_5_190_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/74_5_190.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">177. पर इनके चेहरे तो जाने पहचाने से लगते हैं </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/27_2_157_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/27_2_157_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/27_2_157.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">178. मेंटनेंस का खेल छह से आठ घंटे बिजली फेल </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/50_4_192_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/50_4_192_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/50_4_192.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">179. इसके साथ ही महात्मा गांधी मार्ग जाम हो गया </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/50_5_123_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/50_5_123_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/50_5_123.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">180. बच्ची दर्द से कराहती रही इसके बाद भी नशे में धुत आरोपी दरिंदगी करता रहा </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/84_3_334_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/84_3_334_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/84_3_334.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">181. लीइफ्ट से एक बाइक टैक्सी बुक करो </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/71_4_167_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/71_4_167_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/71_4_167.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">182. गीता रोज सुबह उससे तय करती कि नंदा जल्दी आ जाना </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/34_1_104_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/34_1_104_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/34_1_104.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">183. राहुल का संपर्क अपडेट करो </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/68_3_80_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/68_3_80_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/68_3_80.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">184. अगर यह भय हो तो क्या वह विचार करने योग्य नहीं </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/32_2_116_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/32_2_116_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/32_2_116.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">185. मेल खोलो एक मेल निकिता को भेजो </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/68_1_52_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/68_1_52_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/68_1_52.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">186. अहमदाबाद में स्कूल कॉलेज बहुत हैं अच्छे हैं और अमूमन हर चौराहे पर है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/30_1_273_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/30_1_273_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/30_1_273.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">187. मैं अवाक् इतनी साफ़ सफ़ाक सफेद दीवाल पर कोयले से यह किसने लिख मारा </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/32_1_78_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/32_1_78_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/32_1_78.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">188. हेडलाईन के नीचे एक जले हुए बच्चे की फोटो छपी थी </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/16_1_39_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/16_1_39_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/16_1_39.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">189. हर समय मुँह में दोहले की सुपारी भरे पगुराते रहते </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/26_3_98_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/26_3_98_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/26_3_98.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">190. ब्लू लाइट फ़िल्टर ऑफ </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/69_3_140_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/69_3_140_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/69_3_140.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">191. एक दिन खरगोश उनके पास बैठा कहानियाँ सुन रहा था </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/25_1_171_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/25_1_171_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/25_1_171.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">192. राष्ट्र स्तरीय विंटर कार्निवाल का मुख्य आकर्षण विंटर क्वीन प्रतियोगिता एक बार फिर विवादों में आ गई है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/6_1_73_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/6_1_73_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/6_1_73.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">193. सरकारी एजेंसियों को मौजूदा कानूनी व्यवस्था के तहत उनके खिलाफ कार्रवाई पर फैसला करना चाहिए </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/85_2_275_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/85_2_275_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/85_2_275.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">194. पर उसे तो इस गुफा से बाहर निकलना ही था </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/28_4_3_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/28_4_3_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/28_4_3.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">195. उन्होंने साहिबाबाद पुलिस को भी मामले की सूचना दी </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/45_2_43_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/45_2_43_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/45_2_43.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">196. देखो क्या कोई नया नोटिफिकेशन आया है क्या ब्लॉगर </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/62_4_60_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/62_4_60_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/62_4_60.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">197. ये पहले चरण के तहत मिले धक्के को बढ़ाते हुए रॉकेट को शक्तिशाली बनाता है </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/82_1_172_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/82_1_172_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/82_1_172.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">198. बीनू को उसके भाई ने गुटखे की लत लगा दी थी </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/39_1_97_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/39_1_97_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/39_1_97.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">199. हम ज्यादा गोल करने की कोशिश करेंगे लेकिन फुटबाल में कुछ कहा नहीं जा सकता </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/77_2_18_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/77_2_18_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/77_2_18.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">200. समीक्षा बैठक में एनएचएआई के अतधकारी भी मौजूद थे </p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by WaveRNN</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="fastspeech_prediction_june_2_115k/53_1_316_prediction_fastspeech.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="wavernn_synthesized_test_audios/53_1_316_wavernn_synthesized_target.wav")}} controls="" preload=""></audio></td>
	    <td style="text-align: center"><audio src={{ url_for('static', filename="test_audios/53_1_316.wav")}} controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


