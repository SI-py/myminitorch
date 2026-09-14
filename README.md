# Task 1.5: Training

## Test 1 — Simple

Configuration:

- Dataset: Simple
- Points: 50
- Hidden units: 2
- Learning rate: 0.5
- Epochs: 500

Training logs:

```text
Epoch  10  loss 34.60138468321855    correct 24
Epoch  20  loss 34.35268094213447    correct 30
Epoch  30  loss 34.07901081319081    correct 31
Epoch  40  loss 33.60713583875621    correct 31
Epoch  50  loss 32.67778523676158    correct 35
Epoch  60  loss 30.752841844905415   correct 40
Epoch  70  loss 26.738241637153887   correct 42
Epoch  80  loss 20.17191475649189    correct 46
Epoch  90  loss 14.464226456887268   correct 50
Epoch 100  loss 10.84316019584276    correct 49
Epoch 110  loss 11.816156809491204   correct 46
Epoch 120  loss 11.331825253305903   correct 45
Epoch 130  loss 6.393774464186775    correct 50
Epoch 140  loss 4.768959297350302    correct 50
Epoch 150  loss 4.220908514524682    correct 50
Epoch 160  loss 4.668153881819263    correct 49
Epoch 170  loss 6.1610072460326615   correct 46
Epoch 180  loss 6.5900852695712375   correct 46
Epoch 190  loss 2.277892304369495    correct 50
Epoch 200  loss 2.029218704991138    correct 50
Epoch 210  loss 1.8278215289452897   correct 50
Epoch 220  loss 1.6603567475387382   correct 50
Epoch 230  loss 1.5215400619895922   correct 50
Epoch 240  loss 1.4003766497213945   correct 50
Epoch 250  loss 1.2954183539541073   correct 50
Epoch 260  loss 1.2042286134842823   correct 50
Epoch 270  loss 1.124615372093208    correct 50
Epoch 280  loss 1.0540407000920604   correct 50
Epoch 290  loss 0.9911136686148626   correct 50
Epoch 300  loss 0.9347071851873836   correct 50
Epoch 310  loss 0.8838993766968818   correct 50
Epoch 320  loss 0.8379297551176157   correct 50
Epoch 330  loss 0.7961660195676245   correct 50
Epoch 340  loss 0.7580849845554534   correct 50
Epoch 350  loss 0.7232328800558951   correct 50
Epoch 360  loss 0.6912303318715309   correct 50
Epoch 370  loss 0.6617537532626728   correct 50
Epoch 380  loss 0.6345284802048102   correct 50
Epoch 390  loss 0.6093144344223966   correct 50
Epoch 400  loss 0.5859040405919679   correct 50
Epoch 410  loss 0.56411701194219     correct 50
Epoch 420  loss 0.54379581706538     correct 50
Epoch 430  loss 0.5248010708641783   correct 50
Epoch 440  loss 0.5070124255925871   correct 50
Epoch 450  loss 0.4903225177773996   correct 50
Epoch 460  loss 0.4746351678039207   correct 50
Epoch 470  loss 0.4598654481405618   correct 50
Epoch 480  loss 0.4459365070929227   correct 50
Epoch 490  loss 0.4327822375078081   correct 50
Epoch 500  loss 0.4203412740150817   correct 50
```

Result:

- Final loss: `0.4203`
- Correct predictions: `50/50`
- Accuracy: `100%`

## Test 2 — Diag

Configuration:

- Dataset: Diag
- Points: 50
- Hidden units: 4
- Learning rate: 0.5
- Epochs: 500

Training logs:

```text
Epoch  10  loss 14.249064905254466   correct 46
Epoch  50  loss 11.802413262310996   correct 46
Epoch 100  loss 7.014044022876888    correct 46
Epoch 150  loss 2.4060962415398093   correct 50
Epoch 200  loss 1.141056214372181    correct 50
Epoch 250  loss 0.6812066078724082   correct 50
Epoch 300  loss 0.4597327825142324   correct 50
Epoch 350  loss 0.3351020976253773   correct 50
Epoch 400  loss 0.2576967215637179   correct 50
Epoch 450  loss 0.207187989265228    correct 50
Epoch 500  loss 0.1713162841360846   correct 50
```

Final result:

- Final loss: `0.1713`
- Correct predictions: `50/50`
- Accuracy: `100%`

## Tensor Test 1 — Simple

Configuration:

- Dataset: Simple
- Points: 50
- Hidden units: 2
- Learning rate: 0.5
- Epochs: 500

```text
Epoch  10  loss 34.3263  correct 28
Epoch 100  loss 31.3953  correct 28
Epoch 200  loss 3.2234   correct 50
Epoch 300  loss 1.2513   correct 50
Epoch 400  loss 0.7738   correct 50
Epoch 500  loss 0.5479   correct 50
```

Final result:

- Final loss: `0.5479`
- Correct: `50/50`
- Accuracy: `100%`
