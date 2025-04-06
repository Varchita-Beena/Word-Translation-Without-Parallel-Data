# Word-Translation-Without-Parallel-Data
## procrustes_method_supervised_keyed_vectors.ipynb :- Implementation for supervised procrustes method using dictionary (paired translated words). Precision@1 and precision@5 using cosine similarity.</br>
The train set precision values</br>
precision@1 0.183</br>
precision@5 0.311</br>
The test set (unseen pairs) precision values</br>
precision@1 0.126</br>
precision@5 0.253</br>
similarity after alignment  0.011440736 similarity before alignment  0.008342263</br>
</br>
##### The train set precision values</br>
English: hands Hindi: हाथ Predicted hindi: हाथ with cosine similarity: 0.6519642</br>
English: ruckus Hindi: हंगामा Predicted hindi: हुड़दंग with cosine similarity: 0.47384137</br>
English: indent Hindi: हाशिये Predicted hindi: wrapper:tag with cosine similarity: 0.4393165</br>
English: lek Hindi: लेक Predicted hindi: बेमरंग्बन with cosine similarity: 0.39674598</br>
English: kuna Hindi: कुना Predicted hindi: पीसोMYR with cosine similarity: 0.45688576</br>
English: raven Hindi: रेवेन Predicted hindi: लाँगबॉटम with cosine similarity: 0.44949812</br>
English: affinity Hindi: अपनापन Predicted hindi: अंतर्संबद्धता with cosine similarity: 0.4434074</br>
English: roles Hindi: भूमिकाएँ Predicted hindi: भूमिकाओं with cosine similarity: 0.49793386</br>
English: nigerian Hindi: नाइजीरियाई Predicted hindi: अफ्रीकाः with cosine similarity: 0.50330544</br>
English: viruses Hindi: वाइरस Predicted hindi: वायरस with cosine similarity: 0.59939754</br>
</br>
</br>
##### The test set (unseen pairs) precision values</br>
English: edis Hindi: एडिस Predicted hindi: फॉरजेड with cosine similarity: 0.42466432</br>
English: front Hindi: सामने Predicted hindi: बगल with cosine similarity: 0.5281441</br>
English: councillor Hindi: पार्षद Predicted hindi: पार्षदाें with cosine similarity: 0.4645879</br>
English: its Hindi: इसकी Predicted hindi: इसकी with cosine similarity: 0.5375196</br>
English: violin Hindi: वायलिन Predicted hindi: वायलिन with cosine similarity: 0.5389761</br>
English: gastroenteritis Hindi: gastroenteritis Predicted hindi: आंत्रशोथ with cosine similarity: 0.5138856</br>
English: davydenko Hindi: डेवीडेंको Predicted hindi: जाकोविच with cosine similarity: 0.53353024</br>
English: mast Hindi: mast Predicted hindi: मस्तूलों with cosine similarity: 0.40644103</br>
English: disputed Hindi: विवादित Predicted hindi: विवाद with cosine similarity: 0.4504298</br>
English: pak Hindi: pak Predicted hindi: सेनपाकिस्तान with cosine similarity: 0.50651467</br>
</br>
### With 5000 words in dictionary
The train set precision values
precision@1 0.266
precision@5 0.415
The test set (unseen pairs) precision values
precision@1 0.094
precision@5 0.195
similarity after alignment  0.011470868 similarity before alignment  0.009003754
##### translated words - seen pairs
English: hands Hindi: हाथ Predicted hindi: हाथ with cosine similarity: 0.6022275
English: ruckus Hindi: हंगामा Predicted hindi: हुड़दंग with cosine similarity: 0.41569775
English: indent Hindi: हाशिये Predicted hindi: CTRL with cosine similarity: 0.43581644
English: lek Hindi: लेक Predicted hindi: लेक with cosine similarity: 0.65189576
English: kuna Hindi: कुना Predicted hindi: पीसोMYR with cosine similarity: 0.41060355
English: raven Hindi: रेवेन Predicted hindi: मोसेली with cosine similarity: 0.44332454
English: affinity Hindi: अपनापन Predicted hindi: अंतर्संबद्धता with cosine similarity: 0.39857852
English: roles Hindi: भूमिकाएँ Predicted hindi: भूमिकाएँ with cosine similarity: 0.46996263
English: nigerian Hindi: नाइजीरियाई Predicted hindi: अफ्रीकाअमेरिकाएशियायूरोपमध्य with cosine similarity: 0.5022264
English: viruses Hindi: वाइरस Predicted hindi: वायरस with cosine similarity: 0.5785912
##### translated words - unseen pairs
English: edis Hindi: एडिस Predicted hindi: आएलैंड with cosine similarity: 0.43247128
English: front Hindi: सामने Predicted hindi: सामने with cosine similarity: 0.4470095
English: councillor Hindi: पार्षद Predicted hindi: जनप्रतिनिधयों with cosine similarity: 0.43252182
English: its Hindi: इसकी Predicted hindi: इसकी with cosine similarity: 0.45273936
English: violin Hindi: वायलिन Predicted hindi: संगीतवादन with cosine similarity: 0.44182146
English: gastroenteritis Hindi: gastroenteritis Predicted hindi: कोलाइटिस with cosine similarity: 0.49575508
English: davydenko Hindi: डेवीडेंको Predicted hindi: जाकोविच with cosine similarity: 0.55178636
English: mast Hindi: mast Predicted hindi: खम्भें with cosine similarity: 0.4072425
English: disputed Hindi: विवादित Predicted hindi: विवादित with cosine similarity: 0.42386115
English: pak Hindi: pak Predicted hindi: उसामा with cosine similarity: 0.4765336

### With 10k words in dictionary
The train set precision values</br>
precision@1 0.193</br>
precision@5 0.35</br>
The test set (unseen pairs) precision values</br>
precision@1 0.103</br>
precision@5 0.219</br>
similarity after alignment  0.010376268 similarity before alignment  0.008341992</br>
##### translated words - seen pairs</br>
English: hands Hindi: हाथ Predicted hindi: हाथ with cosine similarity: 0.65525377</br>
English: ruckus Hindi: हंगामा Predicted hindi: आक्रोष with cosine similarity: 0.42692068</br>
English: indent Hindi: हाशिये Predicted hindi: CTRL with cosine similarity: 0.4433787</br>
English: lek Hindi: लेक Predicted hindi: लेक with cosine similarity: 0.506214</br>
English: kuna Hindi: कुना Predicted hindi: पीसोMYR with cosine similarity: 0.44070446</br>
English: raven Hindi: रेवेन Predicted hindi: हरमाईनी with cosine similarity: 0.44423327</br>
English: affinity Hindi: अपनापन Predicted hindi: अंतर्संबद्धता with cosine similarity: 0.4478989</br>
English: roles Hindi: भूमिकाएँ Predicted hindi: भूमिकाएँ with cosine similarity: 0.50458145</br>
English: nigerian Hindi: नाइजीरियाई Predicted hindi: अफ्रीकाना with cosine similarity: 0.49658823</br>
English: viruses Hindi: वाइरस Predicted hindi: वायरस with cosine similarity: 0.5694108</br>
##### translated words - unseen pairs</br>
English: edis Hindi: एडिस Predicted hindi: आएलैंड with cosine similarity: 0.40768152</br>
English: front Hindi: सामने Predicted hindi: सामने with cosine similarity: 0.48437136</br>
English: councillor Hindi: पार्षद Predicted hindi: उपमेयर with cosine similarity: 0.48169968</br>
English: its Hindi: इसकी Predicted hindi: इसकी with cosine similarity: 0.48725736</br>
English: violin Hindi: वायलिन Predicted hindi: वायलिन with cosine similarity: 0.48095876</br>
English: gastroenteritis Hindi: gastroenteritis Predicted hindi: meningococcaemia with cosine similarity: 0.4689428</br>
English: davydenko Hindi: डेवीडेंको Predicted hindi: योकोविच with cosine similarity: 0.5231801</br>
English: mast Hindi: mast Predicted hindi: ऐटेना with cosine similarity: 0.40597954</br>
English: disputed Hindi: विवादित Predicted hindi: विवादलेख with cosine similarity: 0.43322024</br>
English: pak Hindi: pak Predicted hindi: पाक with cosine similarity: 0.52749634</br>
</br>
### With 20k words in dictionary
The train set precision values</br>
precision@1 0.185</br>
precision@5 0.324</br>
The test set (unseen pairs) precision values</br>
precision@1 0.121</br>
precision@5 0.248</br>
similarity after alignment  0.009675078 similarity before alignment  0.007982716</br>
##### translated words - seen pairs</br>
English: hands Hindi: हाथ Predicted hindi: हाथों with cosine similarity: 0.65998125</br>
English: ruckus Hindi: हंगामा Predicted hindi: हुड़दंग with cosine similarity: 0.48993558</br>
English: indent Hindi: हाशिये Predicted hindi: CTRL with cosine similarity: 0.4353192</br>
English: lek Hindi: लेक Predicted hindi: लेक with cosine similarity: 0.41450316</br>
English: kuna Hindi: कुना Predicted hindi: पीसोMYR with cosine similarity: 0.4715731</br>
English: raven Hindi: रेवेन Predicted hindi: लोबोरहाम्फुस with cosine similarity: 0.43840784</br>
English: affinity Hindi: अपनापन Predicted hindi: अंतर्संबद्धता with cosine similarity: 0.4422865</br>
English: roles Hindi: भूमिकाएँ Predicted hindi: भूमिकाओं with cosine similarity: 0.49805602</br>
English: nigerian Hindi: नाइजीरियाई Predicted hindi: सूडानीज with cosine similarity: 0.50198674</br>
English: viruses Hindi: वाइरस Predicted hindi: वायरस with cosine similarity: 0.60307866</br>
##### translated words - unseen pairs</br>
English: edis Hindi: एडिस Predicted hindi: आएलैंड with cosine similarity: 0.44277245</br>
English: front Hindi: सामने Predicted hindi: बगल with cosine similarity: 0.52321273</br>
English: councillor Hindi: पार्षद Predicted hindi: पार्षदाें with cosine similarity: 0.48065284</br>
English: its Hindi: इसकी Predicted hindi: इसकी with cosine similarity: 0.5047025</br>
English: violin Hindi: वायलिन Predicted hindi: वायलिन with cosine similarity: 0.52525574</br>
English: gastroenteritis Hindi: gastroenteritis Predicted hindi: आंत्रशोथ with cosine similarity: 0.49241182</br>
English: davydenko Hindi: डेवीडेंको Predicted hindi: डोकोविक with cosine similarity: 0.53380054</br>
English: mast Hindi: mast Predicted hindi: मस्तूलों with cosine similarity: 0.41655535</br>
English: disputed Hindi: विवादित Predicted hindi: विवाद with cosine similarity: 0.43785906</br>
English: pak Hindi: pak Predicted hindi: शरजील with cosine similarity: 0.5005091</br>

## unsupervised_method_domain_adversarial_setting_training.ipynb - Implementation without using dictionary (paired translations). 
Epoch 50/50 - train Avg Discriminator loss: 78.2848, Avg W loss: 0.0173 </br>
Epoch 50/50 - Validation Avg Discriminator loss: 18.4263 </br>

## CSLS.ipynb :- Precision@1 and precision@5 using cosine similarity uisng matrix obtained from adversarial setting. CSLS implementation,CSLS implementation also with faiss-cpu</br>
The adversarial training collaped in above setting.</br>
Translated words</br>
English: and Hindi: और Predicted hindi: जेहनी with cosine similarity: 0.23745158</br>
English: was Hindi: था Predicted hindi: जेहनी with cosine similarity: 0.23412967</br>
English: was Hindi: थी Predicted hindi: जेहनी with cosine similarity: 0.23412967</br>
English: for Hindi: लिये Predicted hindi: जेहनी with cosine similarity: 0.24661002</br>
English: that Hindi: उस Predicted hindi: जेहनी with cosine similarity: 0.2455211</br>
English: that Hindi: कि Predicted hindi: जेहनी with cosine similarity: 0.2455211</br>
English: with Hindi: साथ Predicted hindi: जेहनी with cosine similarity: 0.24153118</br>
English: from Hindi: से Predicted hindi: जेहनी with cosine similarity: 0.22953205</br>
English: from Hindi: इससे Predicted hindi: जेहनी with cosine similarity: 0.22953205</br>
English: this Hindi: ये Predicted hindi: जेहनी with cosine similarity: 0.23956154</br>

The CSLS implementation stills needs to be optimized to have faster results.
