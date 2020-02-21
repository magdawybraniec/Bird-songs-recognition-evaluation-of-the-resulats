# 1. Summary of the results
| O.n. | Species - ENG name | Species - LAT name | N mel-spectrograms | N mp3 files | f1 score |
| ---- | ------------------ | ------------------ | ------------------ | ----------- | -------- |
| 1. | Eurasian Skylark | *Alauda arvensis* | 6595 | 872 | 0,97 |
| 2. | Thrush Nightingale | *Luscinia luscinia* | 4749 | 396 | 0,95 |
| 3. | Yellowhammer | *Emberiza citrinella* | 17739 | 1452 | 0,94 |
| 4. | Common redstart | *Phoenicurus phoenicurus* | 5204 | 518 | 0,94 |
| 5. | Willow Warbler | *Phylloscopus trochilus* | 26094 | 2154 | 0,94 |
| 6. | Common Blackbird | *Turdus merula* | 40049 | 2045 | 0,93 |
| 7. | Great Tit | *Parus major* | 14425 | 1931 | 0,91 |
| 8. | Black Redstart | *Phoenicurus ochrurus* | 2678 | 358 | 0,91 |
| 9. | Goldfinch | *Carduelis carduelis* | 5038 | 628 | 0,88 |
| 10. | Robin | *Erithacus rubecula* | 21800 | 1587 | 0,88 |
| 11. | Chaffinch | *Fringilla coelebs* | 18705 | 2141 | 0,88 |
| 12. | Common Chiffchaff | *Phylloscopus collybita* | 11562 | 1627 | 0,86 |
| 13. | Eurasian Wren | *Troglodytes troglodytes* | 10306 | 1296 | 0,84 |
| 14. | Song Thrush | *Turdus philomelos* | 35786 | 1889 | 0,83 |
| 15. | Greenfinch | *Chloris chloris* | 4247 | 627 | 0,82 |
| 16. | House sparrow | *Passer domesticus* | 2351 | 384 | 0,79 |
| 17. | Eurasian Nuthatch | *Sitta europaea* | 2014 | 389 | 0,79 |
| 18. | White wagtail | *Motacilla alba* | 738 | 158 | 0,74 |
| 19. | Common Starling | *Sturnus vulgaris* | 5225 | 380 | 0,58 |
| 20. | Hawfinch | *Coccothraustes coccothraustes* | 470 | 89 | 0,55 |
| 21. | Eurasian Magpie | *Pica pica* | 241 | 56 | 0,53 |
| 22. | Common House martin | *Delichon urbicum* | 588 | 57 | 0,46 |
| 23. | Eurasian Jay | *Garrulus glandarius* | 1078 | 136 | 0,37 |
| 24. | Eurasian Tree Sparrow | *Passer montanus* | 1695 | 183 | 0,33 |
| 25. | Fieldfare | *Turdus pilaris* | 858 | 123 | 0,29 |
| 26. | Collared Dove | *Streptopelia decaocto* | 1646 | 314 | 0,28 |
| 27. | Common Wood Pigeon | *Columba palumbus* | 1460 | 265 | 0,12 |


# 2. Evaluation - species below 75% accuracy

## Common Wood Pigeon (*Columba palumbus*)
*	f1 score: 0,12
*	Usage of high-pass filter cut main part of the song frequency (song is mainly in range up to 1 kHz).
*	[sample 1 ](https://www.xeno-canto.org/489280), [sample 2 ](https://www.xeno-canto.org/487835), [sample 3 ](https://www.xeno-canto.org/502415)

<img src="https://birdwatchireland.ie/app/uploads/2019/01/Woodpigeon-05-Daragh-Owens-600x400.jpg" height="200">

## Collared Dove (*Streptopelia decaocto*)
*	f1 score: 0,28
*	Usage of high-pass filter cut main part of the song frequency (song is mainly in range up to 1 kHz).
*	[sample 1 ](https://www.xeno-canto.org/523307), [sample 2 ](https://www.xeno-canto.org/491909), [sample 3 ](https://www.xeno-canto.org/522042)
<img src="https://upload.wikimedia.org/wikipedia/commons/a/a0/Eurasian_Collared_Dove_%28Female%29_I_IMG_9674.jpg" height="200">

## Fieldfare (*Turdus pilaris*)
*	f1 score: 0,29
*	Difficulty of recognition may be caused by: single signal in one phrase at many different frequencies/with few partial tones and also relatively small number of recordings. Besides, song is quite distinguished, consists of few short and sharp/scratchy syllables with small pauses between and some higher, clear, squeaky tones.
*	[sample 1 ](https://www.xeno-canto.org/519948), [sample 2 ](https://www.xeno-canto.org/512394), [sample 3 ](https://www.xeno-canto.org/477289)
<img src="https://www.wildlifetrusts.org/sites/default/files/styles/node_hero_default/public/2017-12/Fieldfare%20cpt.Stefan%20Johansson.jpg?h=35ea520a&itok=5cwCAE8-" height="200">

## Eurasian Tree Sparrow (*Passer montanus*)
*	f1 score: 0,33
*	Reasons of low score is highly unclear - song of this species is very similar to House Sparrow that reached 0,79. Main difference may be (38%) smaller number of recordings. 
*	[sample 1 ](https://www.xeno-canto.org/497877), [sample 2 ](https://www.xeno-canto.org/440407), [sample 3 ](https://www.xeno-canto.org/360701)
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcRO0jWnTuAPrmuKdGosttmlGrPJoVGC0q5gJEapVQyTkv5IXxyS" height="200">

## Eurasian Jay (*Garrulus glandarius*)
*	f1 score: 0,37
*	Small part of the song is under 1kHz, so it could be cut by high-pass filter, however main difficulty of recognition seamed to be: quiet song, call recordings described as songs, broken and irregular rhytm, signals in one phrase at many different frequencies/with few partial tones and also relatively small number of recordings (this species is well known by their 'call' voice, but song is heard rarely).
*	[sample 1 ](https://www.xeno-canto.org/462347), [sample 2 ](https://www.xeno-canto.org/462346), [sample 3 ](https://www.xeno-canto.org/380240)
<img src="https://www.uzdrowiskozegiestow.pl/wp-content/uploads/2017/10/s%C3%B3jka-min.jpg" height="200">

## Common House Martin (*Delichon urbicum*)
*	f1 score: 0,46
*	Song over 1 kHz, difficuty of recognition can be caused by large diversity in song structure and frequencies distribution in one syllable - in one individual's song and between individuals, single syllable also very short.
*	[sample 1 ](https://www.xeno-canto.org/478995), [sample 2 ](https://www.xeno-canto.org/443565), [sample 3 ](https://www.xeno-canto.org/377793)
<img src="https://lh3.googleusercontent.com/proxy/kz8j_gr4mmoBT2KRtdJSiCRxlf1AIs4SR0NIzuDBGyr9-l1A6-1fNnNvan9Ez8qS3CQkFj24521cSbrO0DhdVE9iyTknjy5ubav4btRoKp0h_IUl3hzUJDqpuZo4u0NkanvbXTc" height="200">

## Eurasian Magpie (*Pica pica*)
*	f1 score: 0,53
*	Very small part of song is under 1kHz, so it could be cut by high-pass filter, however main difficulty of recognition may be caused by: quiet song, broken and irregular rhytm, signals in one phrase at many different frequencies/with few partial tones and also relatively small number of recordings (this species is well known by their 'call' voice, but song is heard rarely).
*	[sample 1 ](https://www.xeno-canto.org/451138), [sample 2 ](https://www.xeno-canto.org/281709), [sample 3 ](https://www.xeno-canto.org/383817)
<img src="https://download.ams.birds.cornell.edu/api/v1/asset/44605931/1800" height="200">

## Hawfinch (*Coccothraustes coccothraustes*)
*	f1 score: 0,55
*	All song over 1 kHz. Difficulty in recognition can be caused by small number of song recordings (species is known mainly of its call voice), song is rather quiet, slow, uneven and consist of short syllables. It easly blends into other bird voices, so it is also the reason of small number of recordings. All of these can have impact on quite low recognition accuracy.
*	[sample 1](https://www.xeno-canto.org/460461), [sample 2](https://www.xeno-canto.org/403252), [sample 3](https://www.xeno-canto.org/363825)
<img src="https://www.birdguides.com/cdn/gallery/birdguides/d2e3b06e-80a0-452e-bd04-f5699b625d2d.jpg" height="200">

## Common Starling (*Sturnus vulgaris*)
*	f1 score: 0,58
*	In some cases part of the song can be cut by figh-pass filter, but it applies to minority. Great diversity of sounds and other bird sounds imitations can cause problems in recognition. Song is often well distinguished and rather loud, but extremely diverse in rythm, length, type of voices in one individual and between individuals. Consists of many types of sounds - mainly whistles and jumbled warbling and rattles, often includes imitations of other species voices. 
*	[sample 1 ](https://www.xeno-canto.org/465548), [sample 2 ](https://www.xeno-canto.org/527723), [sample 3 ](https://www.xeno-canto.org/478879)
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5a/Sturnus_vulgaris_2_%28Marek_Szczepanek%29.jpg/290px-Sturnus_vulgaris_2_%28Marek_Szczepanek%29.jpg" height="200">

## White wagtail (*Motacilla alba*)
*	f1 score: 0,74
*	All song over 1 kHz. On difficulty in recognition can impact: quite small numer of song recordings and call recordings described as songs. However song consists of fast undifferentiated chirping with breaks,it is generally quiet, so it can also negatively impact on recorgnition.
*	[sample 1 ](https://www.xeno-canto.org/465382), [sample 2 ](https://www.xeno-canto.org/424991), [sample 3 ](https://www.xeno-canto.org/396506)
<img src="https://lh3.googleusercontent.com/proxy/_aUdc6UFYqWfP_Y3YNojIufxbErRn6kjQYZibHYrmLh7cHGnWFqgSgXwoMFBFQKo30BoiM57OhBNKzOcFBaCndAX5oPprvHJ9N1n3Sl8KaOW8whf2eumy9GQaljai0ohXiKt_XfUBUMqa7LdtnugnYfpzY8q-7E" height="200">

# 3. Ornithological-side summary

Sounds of bird species with accuracy below 75% are characterized by:
* low number of recordings
* some part of the song below 1 kHz - usage of high-pass filter (1 kHz) cut some song frequency - apply to pigeons (Common Wood Pigeon, Collared Dove) and corvidae (Eurasian Magpie, Eurasian Jay) 
* large diversity of song structure and frequencies in one individual's song and between individuals (Common Starling, House Martin, Fieldfare)
* quiet song (White Wagtail, Hawfinch, Eurasian Magpie, Eurasian Jay) 
* including imitations of other bird species (Common Starling)
* not properly described recordings (calls described as songs) (especially White Wagtail, but also other species) 




