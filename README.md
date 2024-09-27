# Xianjing_Huang_Mini_Proj_4
[![CI](https://github.com/nogibjj/Xianjing_Huang_Mini_Proj_4/actions/workflows/ci.yml/badge.svg)](https://github.com/nogibjj/Xianjing_Huang_Mini_Proj_4/actions/workflows/ci.yml)

### Directory Tree Structure
```
Xianjing_Huang_Mini_Proj_4/
├── .devcontainer/
│   ├── devcontainer.json
│   └── Dockerfile
├── .github/
│   └── workflows/
│       └── ci.yml
├── imgs/
├── .gitignore
├── main.py
├── Makefile
├── README.md
├── requirements.txt
└── test_main.py
```

### Requirements
* Set up a Gitlab Actions workflow
* Test across at least 3 different Python versions


### Preparation
1. Open codespaces
2. Wait for container to be built and pinned requirements from `requirements.txt` to be installed
3. If running locally, `git clone` the repository and use `make install`
   ![0](/imgs/000.png)

### Check format and test errors
1. Format code `make format`
   ![1](/imgs/001.png)
2. Lint code `make lint`
   ![2](/imgs/002.png)
3. Test code `make test`
   ![3](/imgs/003.png)

### Github actions with matrix strategy
   <img src="/imgs/004.png" alt="0" height="350">
