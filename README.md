[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YFgwt0yY)
# MiniTorch Module 2

<img src="https://minitorch.github.io/minitorch.svg" width="50%">


* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module2/module2/

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/scalar.py minitorch/scalar_functions.py minitorch/module.py project/run_manual.py project/run_scalar.py project/datasets.py


SIMPLE - PTS = 111, HIDDEN = 3, RATE = 0.1, EPOCHS = 500, Time per epoch = 0.108s

Epoch: 0/500, loss: 0, correct: 0
Epoch: 10/500, loss: 80.10963868520463, correct: 53
Epoch: 20/500, loss: 78.34519331400756, correct: 53
Epoch: 30/500, loss: 77.04633702616563, correct: 53
Epoch: 40/500, loss: 76.00609123734162, correct: 53
Epoch: 50/500, loss: 75.0703943863683, correct: 53
Epoch: 60/500, loss: 74.12526790791921, correct: 53
Epoch: 70/500, loss: 73.08826865489443, correct: 74
Epoch: 80/500, loss: 71.88890590156257, correct: 83
Epoch: 90/500, loss: 70.4595541280087, correct: 87
Epoch: 100/500, loss: 68.73569840670474, correct: 90
Epoch: 110/500, loss: 66.67025659240565, correct: 90
Epoch: 120/500, loss: 64.26362904942458, correct: 91
Epoch: 130/500, loss: 61.50625751210693, correct: 93
Epoch: 140/500, loss: 58.427939590251626, correct: 95
Epoch: 150/500, loss: 55.16371252084332, correct: 96
Epoch: 160/500, loss: 51.82796810894496, correct: 97
Epoch: 170/500, loss: 48.54015597160824, correct: 97
Epoch: 180/500, loss: 45.41153156710642, correct: 98
Epoch: 190/500, loss: 42.4681688302979, correct: 101
Epoch: 200/500, loss: 39.715841497713726, correct: 103
Epoch: 210/500, loss: 37.28304010175519, correct: 103
Epoch: 220/500, loss: 35.121474354752095, correct: 104
Epoch: 230/500, loss: 33.15663896017255, correct: 105
Epoch: 240/500, loss: 31.402958018138083, correct: 107
Epoch: 250/500, loss: 29.85245185859181, correct: 107
Epoch: 260/500, loss: 28.459318014013675, correct: 107
Epoch: 270/500, loss: 27.196679120112776, correct: 107
Epoch: 280/500, loss: 26.05358534584916, correct: 107
Epoch: 290/500, loss: 24.998366058095893, correct: 107
Epoch: 300/500, loss: 24.029077198029015, correct: 108
Epoch: 310/500, loss: 23.138554526700528, correct: 108
Epoch: 320/500, loss: 22.310292090595993, correct: 108
Epoch: 330/500, loss: 21.538472817899677, correct: 108
Epoch: 340/500, loss: 20.817989509158238, correct: 109
Epoch: 350/500, loss: 20.1443276459653, correct: 109
Epoch: 360/500, loss: 19.51347806050197, correct: 110
Epoch: 370/500, loss: 18.921863915860175, correct: 111
Epoch: 380/500, loss: 18.366690137295446, correct: 111
Epoch: 390/500, loss: 17.84900582073393, correct: 111
Epoch: 400/500, loss: 17.362248482051637, correct: 111
Epoch: 410/500, loss: 16.90344259682001, correct: 111
Epoch: 420/500, loss: 16.470432900146275, correct: 111
Epoch: 430/500, loss: 16.061248731297855, correct: 111
Epoch: 440/500, loss: 15.674086195883072, correct: 111
Epoch: 450/500, loss: 15.3174190883838, correct: 111
Epoch: 460/500, loss: 14.983945431430884, correct: 111
Epoch: 470/500, loss: 14.66616747790815, correct: 111
Epoch: 480/500, loss: 14.362983698544118, correct: 111
Epoch: 490/500, loss: 14.073391449352497, correct: 111
Epoch: 500/500, loss: 13.796474054387819, correct: 111

![Simple Plot](/simpleplot.png)


DIAG - PTS = 111, HIDDEN = 6, RATE = 0.1, EPOCHS = 500, Time per epoch = 0.264s

Epoch: 10/500, loss: 33.75804271848908, correct: 99
Epoch: 20/500, loss: 30.812800486817753, correct: 99
Epoch: 30/500, loss: 29.490814894894278, correct: 99
Epoch: 40/500, loss: 28.54013885886151, correct: 99
Epoch: 50/500, loss: 27.795620271287113, correct: 99
Epoch: 60/500, loss: 27.134420897386924, correct: 99
Epoch: 70/500, loss: 26.465986850222738, correct: 99
Epoch: 80/500, loss: 25.804494147131717, correct: 99
Epoch: 90/500, loss: 25.164255569299616, correct: 99
Epoch: 100/500, loss: 24.4985906438986, correct: 99
Epoch: 110/500, loss: 23.85036249235253, correct: 99
Epoch: 120/500, loss: 23.228376890438486, correct: 99
Epoch: 130/500, loss: 22.609744704050055, correct: 99
Epoch: 140/500, loss: 21.98802288392315, correct: 99
Epoch: 150/500, loss: 21.35834154881071, correct: 99
Epoch: 160/500, loss: 20.730113197894134, correct: 99
Epoch: 170/500, loss: 20.105614341252192, correct: 99
Epoch: 180/500, loss: 19.502820447379555, correct: 99
Epoch: 190/500, loss: 18.904173749255648, correct: 100
Epoch: 200/500, loss: 18.30028114797969, correct: 100
Epoch: 210/500, loss: 17.7025548981055, correct: 102
Epoch: 220/500, loss: 17.11616170517927, correct: 102
Epoch: 230/500, loss: 16.54761848641296, correct: 102
Epoch: 240/500, loss: 16.01156847078501, correct: 103
Epoch: 250/500, loss: 15.504646998517607, correct: 103
Epoch: 260/500, loss: 15.02211234385185, correct: 103
Epoch: 270/500, loss: 14.560761708319431, correct: 105
Epoch: 280/500, loss: 14.124284223220906, correct: 105
Epoch: 290/500, loss: 13.731794063746536, correct: 105
Epoch: 300/500, loss: 13.353022515547053, correct: 105
Epoch: 310/500, loss: 12.987915181570996, correct: 105
Epoch: 320/500, loss: 12.636909892375812, correct: 105
Epoch: 330/500, loss: 12.325812725983594, correct: 105
Epoch: 340/500, loss: 12.043975886863608, correct: 106
Epoch: 350/500, loss: 11.770207452607593, correct: 106
Epoch: 360/500, loss: 11.507491154966475, correct: 106
Epoch: 370/500, loss: 11.253888775810992, correct: 106
Epoch: 380/500, loss: 11.008790550858667, correct: 107
Epoch: 390/500, loss: 10.778906003793116, correct: 107
Epoch: 400/500, loss: 10.558550284870742, correct: 107
Epoch: 410/500, loss: 10.3462375629436, correct: 107
Epoch: 420/500, loss: 10.140773897739782, correct: 107
Epoch: 430/500, loss: 9.94435102150192, correct: 107
Epoch: 440/500, loss: 9.758363943708998, correct: 107
Epoch: 450/500, loss: 9.578119888429324, correct: 108
Epoch: 460/500, loss: 9.406988292942945, correct: 108
Epoch: 470/500, loss: 9.241737598341231, correct: 108
Epoch: 480/500, loss: 9.081370019705789, correct: 108
Epoch: 490/500, loss: 8.9264486222145, correct: 108
Epoch: 500/500, loss: 8.776103352620257, correct: 108

![Diag Plot](/diagplot.png)


SPLIT - PTS = 111, HIDDEN = 7, RATE = 0.1, EPOCHS = 800, Time per epoch = 0.335s

Epoch: 0/800, loss: 0, correct: 0
Epoch: 10/800, loss: 71.67168590154147, correct: 70
Epoch: 20/800, loss: 71.29900635552485, correct: 70
Epoch: 30/800, loss: 71.08818800236077, correct: 70
Epoch: 40/800, loss: 70.90267658696841, correct: 70
Epoch: 50/800, loss: 70.72116002434515, correct: 70
Epoch: 60/800, loss: 70.53669487843854, correct: 70
Epoch: 70/800, loss: 70.34331553656004, correct: 70
Epoch: 80/800, loss: 70.13323794407162, correct: 70
Epoch: 90/800, loss: 69.89629398488592, correct: 70
Epoch: 100/800, loss: 69.61879644527674, correct: 70
Epoch: 110/800, loss: 69.3274996048764, correct: 70
Epoch: 120/800, loss: 69.02802293181836, correct: 71
Epoch: 130/800, loss: 68.73180981674628, correct: 75
Epoch: 140/800, loss: 68.42822229316074, correct: 76
Epoch: 150/800, loss: 68.09153988577162, correct: 76
Epoch: 160/800, loss: 67.7046437551723, correct: 76
Epoch: 170/800, loss: 67.30949700768765, correct: 80
Epoch: 180/800, loss: 66.80259654762759, correct: 81
Epoch: 190/800, loss: 66.20490634352645, correct: 84
Epoch: 200/800, loss: 65.61371910270827, correct: 85
Epoch: 210/800, loss: 65.02287540253066, correct: 85
Epoch: 220/800, loss: 64.44587099279137, correct: 85
Epoch: 230/800, loss: 63.876694329077075, correct: 86
Epoch: 240/800, loss: 63.29340555219902, correct: 87
Epoch: 250/800, loss: 62.68236836270196, correct: 89
Epoch: 260/800, loss: 62.041624687191714, correct: 89
Epoch: 270/800, loss: 61.374477248740526, correct: 89
Epoch: 280/800, loss: 60.68154601750344, correct: 89
Epoch: 290/800, loss: 59.96169807223179, correct: 89
Epoch: 300/800, loss: 59.20999797894987, correct: 89
Epoch: 310/800, loss: 58.42112166724038, correct: 89
Epoch: 320/800, loss: 57.5888106758731, correct: 89
Epoch: 330/800, loss: 56.70365161232496, correct: 89
Epoch: 340/800, loss: 55.75618078563385, correct: 89
Epoch: 350/800, loss: 54.74105028537125, correct: 89
Epoch: 360/800, loss: 53.65459810463089, correct: 89
Epoch: 370/800, loss: 52.48905976291596, correct: 89
Epoch: 380/800, loss: 51.27175148310352, correct: 89
Epoch: 390/800, loss: 50.13263860733273, correct: 89
Epoch: 400/800, loss: 49.00902481054757, correct: 89
Epoch: 410/800, loss: 47.89338334609129, correct: 89
Epoch: 420/800, loss: 46.7689599902598, correct: 89
Epoch: 430/800, loss: 45.64767767743938, correct: 89
Epoch: 440/800, loss: 44.53806716811158, correct: 89
Epoch: 450/800, loss: 43.442545189975, correct: 89
Epoch: 460/800, loss: 42.36215173824636, correct: 89
Epoch: 470/800, loss: 41.29085903618157, correct: 89
Epoch: 480/800, loss: 40.22357457328099, correct: 89
Epoch: 490/800, loss: 39.169447605933044, correct: 89
Epoch: 500/800, loss: 38.143078816697965, correct: 89
Epoch: 510/800, loss: 37.136934618935946, correct: 89
Epoch: 520/800, loss: 36.16295485456965, correct: 89
Epoch: 530/800, loss: 35.215877582394484, correct: 89
Epoch: 540/800, loss: 34.30388757264942, correct: 89
Epoch: 550/800, loss: 33.41427978031837, correct: 100
Epoch: 560/800, loss: 32.53807070686077, correct: 101
Epoch: 570/800, loss: 31.687315918149753, correct: 101
Epoch: 580/800, loss: 30.882274289805515, correct: 101
Epoch: 590/800, loss: 30.09890992175148, correct: 102
Epoch: 600/800, loss: 29.34184195755017, correct: 103
Epoch: 610/800, loss: 28.613943539718335, correct: 104
Epoch: 620/800, loss: 27.910243006117142, correct: 104
Epoch: 630/800, loss: 27.22845119816775, correct: 104
Epoch: 640/800, loss: 26.57304587001976, correct: 104
Epoch: 650/800, loss: 25.940852791011345, correct: 104
Epoch: 660/800, loss: 25.330726479276002, correct: 106
Epoch: 670/800, loss: 24.741899607163667, correct: 106
Epoch: 680/800, loss: 24.173074963390857, correct: 106
Epoch: 690/800, loss: 23.624034111062254, correct: 106
Epoch: 700/800, loss: 23.092622119656976, correct: 107
Epoch: 710/800, loss: 22.582560033308475, correct: 107
Epoch: 720/800, loss: 22.101414150090122, correct: 107
Epoch: 730/800, loss: 21.629618859860837, correct: 107
Epoch: 740/800, loss: 21.17099283899934, correct: 107
Epoch: 750/800, loss: 20.728732547835133, correct: 107
Epoch: 760/800, loss: 20.30542933825065, correct: 107
Epoch: 770/800, loss: 19.9058414895963, correct: 107
Epoch: 780/800, loss: 19.517637144512886, correct: 107
Epoch: 790/800, loss: 19.144022920897974, correct: 108
Epoch: 800/800, loss: 18.785252702345996, correct: 108

![Split Plot](/splitplot.png)


XOR - PTS = 111, HIDDEN = 8, RATE = 0.1, EPOCHS = 800, Time per epoch = 0.414s

Epoch: 0/800, loss: 0, correct: 0
Epoch: 10/800, loss: 73.21878445232711, correct: 55
Epoch: 20/800, loss: 71.82358756840193, correct: 76
Epoch: 30/800, loss: 70.79562420125836, correct: 77
Epoch: 40/800, loss: 69.62852758682939, correct: 76
Epoch: 50/800, loss: 68.87579896554797, correct: 78
Epoch: 60/800, loss: 68.16515829638227, correct: 78
Epoch: 70/800, loss: 67.44814316877915, correct: 78
Epoch: 80/800, loss: 66.70394691948728, correct: 78
Epoch: 90/800, loss: 65.93041302763605, correct: 78
Epoch: 100/800, loss: 65.13220262585742, correct: 78
Epoch: 110/800, loss: 64.30143283092646, correct: 78
Epoch: 120/800, loss: 63.43347581370299, correct: 78
Epoch: 130/800, loss: 62.520772370173425, correct: 82
Epoch: 140/800, loss: 61.56253566157494, correct: 86
Epoch: 150/800, loss: 60.54421808671989, correct: 92
Epoch: 160/800, loss: 59.47783478112997, correct: 93
Epoch: 170/800, loss: 58.354694526856996, correct: 94
Epoch: 180/800, loss: 57.168776078181, correct: 94
Epoch: 190/800, loss: 55.91303129269489, correct: 97
Epoch: 200/800, loss: 54.586418737978796, correct: 98
Epoch: 210/800, loss: 53.18813455237985, correct: 98
Epoch: 220/800, loss: 51.7134980869588, correct: 100
Epoch: 230/800, loss: 50.16918965696756, correct: 102
Epoch: 240/800, loss: 48.56423249220756, correct: 102
Epoch: 250/800, loss: 46.89994885081191, correct: 104
Epoch: 260/800, loss: 45.17592896768725, correct: 105
Epoch: 270/800, loss: 43.43472330207421, correct: 105
Epoch: 280/800, loss: 41.71177657949803, correct: 107
Epoch: 290/800, loss: 40.01074748519162, correct: 108
Epoch: 300/800, loss: 38.35308796964192, correct: 107
Epoch: 310/800, loss: 36.75079276404011, correct: 107
Epoch: 320/800, loss: 35.2198682775875, correct: 107
Epoch: 330/800, loss: 33.75350493048015, correct: 108
Epoch: 340/800, loss: 32.33824640771785, correct: 108
Epoch: 350/800, loss: 31.015098275569127, correct: 109
Epoch: 360/800, loss: 29.800071015362416, correct: 108
Epoch: 370/800, loss: 28.67901005627928, correct: 109
Epoch: 380/800, loss: 27.635226152447565, correct: 109
Epoch: 390/800, loss: 26.6579139990945, correct: 109
Epoch: 400/800, loss: 25.74088393611086, correct: 109
Epoch: 410/800, loss: 24.882098918886772, correct: 109
Epoch: 420/800, loss: 24.073415129117674, correct: 109
Epoch: 430/800, loss: 23.311876060772903, correct: 109
Epoch: 440/800, loss: 22.594275149069727, correct: 109
Epoch: 450/800, loss: 21.917184476391842, correct: 109
Epoch: 460/800, loss: 21.27748365772483, correct: 109
Epoch: 470/800, loss: 20.673472143538557, correct: 109
Epoch: 480/800, loss: 20.103969131821973, correct: 109
Epoch: 490/800, loss: 19.564162752415374, correct: 109
Epoch: 500/800, loss: 19.05181201947967, correct: 109
Epoch: 510/800, loss: 18.562495966548724, correct: 109
Epoch: 520/800, loss: 18.099085400550102, correct: 109
Epoch: 530/800, loss: 17.662495409408205, correct: 109
Epoch: 540/800, loss: 17.24685407733013, correct: 109
Epoch: 550/800, loss: 16.851229178929092, correct: 109
Epoch: 560/800, loss: 16.473770669767895, correct: 109
Epoch: 570/800, loss: 16.113321632662768, correct: 109
Epoch: 580/800, loss: 15.771599693912075, correct: 109
Epoch: 590/800, loss: 15.444191899399613, correct: 109
Epoch: 600/800, loss: 15.132695881409958, correct: 109
Epoch: 610/800, loss: 14.833690007036022, correct: 109
Epoch: 620/800, loss: 14.547016614167566, correct: 109
Epoch: 630/800, loss: 14.271727489569672, correct: 109
Epoch: 640/800, loss: 14.007277130687639, correct: 109
Epoch: 650/800, loss: 13.753041986024765, correct: 109
Epoch: 660/800, loss: 13.508456595321164, correct: 109
Epoch: 670/800, loss: 13.272862311249167, correct: 109
Epoch: 680/800, loss: 13.046051962457176, correct: 109
Epoch: 690/800, loss: 12.828066002139229, correct: 109
Epoch: 700/800, loss: 12.618857265772634, correct: 109
Epoch: 710/800, loss: 12.418292206887587, correct: 109
Epoch: 720/800, loss: 12.225649513445857, correct: 109
Epoch: 730/800, loss: 12.038575828499342, correct: 109
Epoch: 740/800, loss: 11.860508155204055, correct: 109
Epoch: 750/800, loss: 11.68924112281742, correct: 109
Epoch: 760/800, loss: 11.52308592832351, correct: 109
Epoch: 770/800, loss: 11.36108372566164, correct: 109
Epoch: 780/800, loss: 11.204613667693808, correct: 109
Epoch: 790/800, loss: 11.049713509761604, correct: 109
Epoch: 800/800, loss: 10.900269524126244, correct: 109

![XOR Plot](/xorplot.png)

CIRCLE - PTS = 111, HIDDEN = 8, RATE = 0.1, EPOCHS = 800, Time per epoch = 0.414s

Epoch: 0/800, loss: 0, correct: 0
Epoch: 10/800, loss: 69.63436811454986, correct: 71
Epoch: 20/800, loss: 68.8085564790751, correct: 67
Epoch: 30/800, loss: 68.32201452780275, correct: 66
Epoch: 40/800, loss: 67.85805472570995, correct: 65
Epoch: 50/800, loss: 67.40665409421996, correct: 65
Epoch: 60/800, loss: 66.95859177180603, correct: 65
Epoch: 70/800, loss: 66.5189181571896, correct: 65
Epoch: 80/800, loss: 66.0794927866155, correct: 65
Epoch: 90/800, loss: 65.64453832884436, correct: 66
Epoch: 100/800, loss: 65.20511506669206, correct: 67
Epoch: 110/800, loss: 64.76902916753073, correct: 67
Epoch: 120/800, loss: 64.3186460013359, correct: 67
Epoch: 130/800, loss: 63.84538819618201, correct: 66
Epoch: 140/800, loss: 63.33725335716174, correct: 69
Epoch: 150/800, loss: 62.72047209737445, correct: 70
Epoch: 160/800, loss: 61.98246727157575, correct: 72
Epoch: 170/800, loss: 61.25102911752209, correct: 73
Epoch: 180/800, loss: 60.629791413826176, correct: 73
Epoch: 190/800, loss: 60.05881490985663, correct: 75
Epoch: 200/800, loss: 59.43643328646331, correct: 75
Epoch: 210/800, loss: 58.779206932899015, correct: 77
Epoch: 220/800, loss: 58.14027259186875, correct: 78
Epoch: 230/800, loss: 57.508585158331, correct: 80
Epoch: 240/800, loss: 56.869822635083366, correct: 79
Epoch: 250/800, loss: 56.226076374892145, correct: 80
Epoch: 260/800, loss: 55.549887886528396, correct: 83
Epoch: 270/800, loss: 54.86612934945339, correct: 84
Epoch: 280/800, loss: 54.14892848934406, correct: 84
Epoch: 290/800, loss: 53.39143443925639, correct: 86
Epoch: 300/800, loss: 52.67078148537005, correct: 87
Epoch: 310/800, loss: 51.93394678414343, correct: 88
Epoch: 320/800, loss: 51.145598704057335, correct: 90
Epoch: 330/800, loss: 50.35224895889346, correct: 91
Epoch: 340/800, loss: 49.56551683654912, correct: 91
Epoch: 350/800, loss: 48.73164013276314, correct: 94
Epoch: 360/800, loss: 47.84968997814523, correct: 96
Epoch: 370/800, loss: 46.996313509046885, correct: 96
Epoch: 380/800, loss: 46.21455512715182, correct: 96
Epoch: 390/800, loss: 45.41671658972409, correct: 94
Epoch: 400/800, loss: 44.70733424132274, correct: 94
Epoch: 410/800, loss: 44.015662175679694, correct: 94
Epoch: 420/800, loss: 43.400811516085234, correct: 93
Epoch: 430/800, loss: 42.81614359067646, correct: 93
Epoch: 440/800, loss: 42.21001448553851, correct: 93
Epoch: 450/800, loss: 41.53946731500443, correct: 96
Epoch: 460/800, loss: 40.923840997015816, correct: 97
Epoch: 470/800, loss: 40.34170407567744, correct: 96
Epoch: 480/800, loss: 39.72087047351322, correct: 96
Epoch: 490/800, loss: 39.10112706603711, correct: 96
Epoch: 500/800, loss: 38.504691675390895, correct: 96
Epoch: 510/800, loss: 37.92016028049157, correct: 96
Epoch: 520/800, loss: 37.273848979081166, correct: 97
Epoch: 530/800, loss: 36.65233892718392, correct: 98
Epoch: 540/800, loss: 36.041426084641294, correct: 99
Epoch: 550/800, loss: 35.4300325135856, correct: 99
Epoch: 560/800, loss: 34.819486106422275, correct: 99
Epoch: 570/800, loss: 34.23124272231235, correct: 100
Epoch: 580/800, loss: 33.663111776712945, correct: 99
Epoch: 590/800, loss: 33.03883656884224, correct: 98
Epoch: 600/800, loss: 32.38745507588042, correct: 98
Epoch: 610/800, loss: 31.632693659828302, correct: 99
Epoch: 620/800, loss: 30.7823625085629, correct: 100
Epoch: 630/800, loss: 30.00687998782739, correct: 100
Epoch: 640/800, loss: 29.25492415848183, correct: 100
Epoch: 650/800, loss: 28.528852868411256, correct: 99
Epoch: 660/800, loss: 27.69170263500967, correct: 100
Epoch: 670/800, loss: 26.84808149382904, correct: 100
Epoch: 680/800, loss: 26.015581525884706, correct: 101
Epoch: 690/800, loss: 25.263622631510955, correct: 102
Epoch: 700/800, loss: 24.595767002091165, correct: 103
Epoch: 710/800, loss: 23.980511524082402, correct: 104
Epoch: 720/800, loss: 23.350484341460422, correct: 105
Epoch: 730/800, loss: 22.761519264674206, correct: 105
Epoch: 740/800, loss: 22.20477816515895, correct: 105
Epoch: 750/800, loss: 21.677006479316884, correct: 105
Epoch: 760/800, loss: 21.124342676612883, correct: 106
Epoch: 770/800, loss: 20.59122692216949, correct: 106
Epoch: 780/800, loss: 20.068768682297645, correct: 107
Epoch: 790/800, loss: 19.580277620938322, correct: 107
Epoch: 800/800, loss: 19.09428957568455, correct: 108

![Circle Plot](/circleplot.png)


SPIRAL - PTS = 110, HIDDEN = 9, RATE = 0.1, EPOCHS = 800, Time per epoch = 0.498s


