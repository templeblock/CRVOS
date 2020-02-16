# CRVOS: Clue Refining Network for Video Object Segmentation

#### Suhwan Cho, MyeongAh Cho, Tae-young Chung, Heansung Lee and Sangyoun Lee

arXiv paper: [[pdf]](https://arxiv.org/pdf/2002.03651.pdf)
___


## How to run
1. Download [DAVIS17](https://davischallenge.org/davis2017/code.html) and [pre-trained model](https://drive.google.com/a/yonsei.ac.kr/file/d/19DFvKs5N8wuRzjBKNg72szyGcyvFT0x6/view?usp=sharing).

2. Modify "local_config.py".

3. Check fps of CRVOS.
```
python test.py --fps
```

4. Save the outputs of CRVOS.
```
python test.py --save
```


## How to evaluate
Official evaluation code can only deal with DAVIS17. 

If you want to evaluate the model on both DAVIS16 and DAVIS17, check my code out!


[[Official evaluation code]](https://github.com/davisvideochallenge/davis2017-evaluation)

[[My evaluation code]](https://github.com/suhwan-cho/davis-evaluation)


## Citation
```
@article{cho2020crvos,
  title={CRVOS: Clue Refining Network for Video Object Segmentation},
  author={Cho, Suhwan and Cho, MyeongAh and Chung, Tae-young and Lee, Heansung and Lee, Sangyoun},
  journal={arXiv preprint arXiv:2002.03651},
  year={2020}
}
```

## Note
The trained model, "CRVOS_best.tar", is trained on GPU device number 1.

[A-GAME](https://github.com/joakimjohnander/agame-vos) was really helpful to me. I'm pretty sure it will be so to you.
