# va-inv-rl

<img src="https://raw.githubusercontent.com/dwyl/repo-badges/master/highresPNGs/start-with-why-HiRes.png" height="20" width="100">

- Python 3.6
- torch==1.4.0 (PyTorch)

This is a Pytorch tutorial on the paper Variational Adversarial Inverse Reinforcement Learning by Xue Bin Peng & Angjoo Kanazawa & Sam Toyer & Pieter Abbeel & Sergey Levine. 

[VARIATIONAL DISCRIMINATOR BOTTLENECK:
IMPROVING IMITATION LEARNING, INVERSE RL, AND GANS BY
CONSTRAINING INFORMATION FLOW](https://arxiv.org/pdf/1810.00821.pdf)

<img src="https://image.slidesharecdn.com/vdb-181125215953/95/variational-discriminator-bottleneck-7-638.jpg">

# Set up instructions:

1. in your terminal `cd` into a folder you want to work from and `git clone https://github.com/clam004/va-irl.git` 
2. `cd` into `va-irl` and create a virtual environment `python3 -m venv env`
3. install dependencies `pip3 install -r requirements.txt`
4. `jupyter notebook` will open a new tab in your browser
5. install any additional depemdencies you need
6. add any new dependences to requirements.txt `pip3 freeze > requirements.txt
`
