# CTF Training

经典赛题复现环境

I need your help!!!

## 环境说明 Explain

- docker-ce version 18.09+
- docker-compose version 1.23+

### Installation

```bash
# Install pip
curl -s https://bootstrap.pypa.io/get-pip.py | python3

# Install the latest version docker
curl -s https://get.docker.com/ | sh

# Run docker service
service docker start

# Install docker compose
pip install docker-compose
```

## 版权说明

项目内题目源码均从网络收集，如果侵权，请联系本人删除（ virink@outlook.com ）

## 致谢及贡献者 Credits & Contributor

- [CoColi](https://github.com/CoColizdf)
    + [hbctf_2017_dameixian](https://github.com/CTFTraining/hbctf_2017_dameixian)
    + [hctf_2018_warmup](https://github.com/CTFTraining/hctf_2018_warmup)
- [Tiaonmmn](https://github.com/Tiaonmmn)
    + [insomniteaser_2019_l33t_hoster](https://github.com/Tiaonmmn/insomniteaser_2019_l33t_hoster)
    + [meepwn_2018_pycalx](https://github.com/Tiaonmmn/meepwn_2018_pycalx)
    + [insomniteaser_2019_phuck2](https://github.com/Tiaonmmn/insomniteaser_2019_phuck2)
    + [asis_2019_unicorn_shop](https://github.com/Tiaonmmn/asis_2019_unicorn_shop)
- [glzjin](https://github.com/glzjin)
    + [qwb_2019_upload](https://github.com/glzjin/qwb_2019_upload)
    + [qwb_2019_supersqli](https://github.com/glzjin/qwb_2019_supersqli)
    + [qwb_2019_smarthacker](https://github.com/glzjin/qwb_2019_smarthacker)
    + [ciscn_2019_web_northern_china_day1_web1](https://github.com/glzjin/CISCN_2019_northern_China_day1_web1)
    + [ciscn_2019_web_northern_china_day1_web2](https://github.com/glzjin/CISCN_2019_northern_China_day1_web2)
    + [ciscn_2019_web_northern_china_day2_web1](https://github.com/glzjin/CISCN_2019_northern_China_day2_web1)
    + [buuctf_2018_online_tool](https://github.com/glzjin/buuctf_2018_online_tool)
    + [fbctf_2019_products_manager](https://github.com/glzjin/fbctf_2019_products_manager)
- [blus](https://github.com/851579181)
    + [qwb_2019_crypto_copperstudy](https://github.com/851579181/qwb_2019_crypto_copperstudy)



## 贡献指南 Contribution Guide

### Repository Rules

#### Name Rules

比赛名称_年份_题目类型_题目名称_其他 GameName_Year_ChallengeName_Others `/\w+_\d{4}_\w+_(\w+)+/`

eg. `westerns_2018_web_shrine` and `ctf473831530_2018_web_virink`

#### Description Rules

Able to describe clearly what the challenge is.

**eg.**

- **护网杯 2018 WEB (4) easy_laravel**
- **CTF学习交流入群题 Web 20180626**

#### File Rules

- **Dockerfile (require)**
- **docker-compose.yml (require)**
- **README.md (require)**
- **SourceCode file or directory (require)**
- vhost.conf
- .gitignore
- LICENSE

Just like other challenge.

### How to contribute challenge

1. Create a challenge repository on GitHub
2. Create a new issue in this repository
3. Waiting for the audit
4. We will fork your repository after approval

### How to update existing challenge

1. Update your repository
2. Pull Request
3. Waiting for the audit
4. We will merge your repository after approval
