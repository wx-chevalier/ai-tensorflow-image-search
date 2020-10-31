[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/wx-chevalier/tensorflow-image-search">
    <img src="https://s2.ax1x.com/2020/01/16/ljgpUP.png" alt="Logo" width="120" height="80">
  </a>

  <h3 align="center">tensorflow-image-search</h3>

  <p align="center">
    A reverse image search engine powered by elastic search and tensorflow
    <br />
    <a href="https://github.com/wx-chevalier/tensorflow-image-search"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/wx-chevalier/tensorflow-image-search">View Demo</a>
    ·
    <a href="https://github.com/wx-chevalier/tensorflow-image-search/issues">Report Bug</a>
    ·
    <a href="https://github.com/wx-chevalier/tensorflow-image-search/issues">Request Feature</a>
  </p>
</p>

<!-- ABOUT THE PROJECT -->

# Introduction

Fork from [sethuiyer/Image-to-Image-search](https://github.com/sethuiyer/Image-to-Image-search).

## Nav | 导航

# Getting Started

## Packages Required:

- Anaconda
- Keras with Tensorflow Backend (Python 3.6)
- Elastic Search and elasticsearch-py (Elastic Search 6.0)

For more, check out requirements.txt

## Pre-trained models

- [Flickr-8k LSTM weights (flickr8k_cnn_lstm_v1.p)](https://cs.stanford.edu/people/karpathy/neuraltalk/flickr8k_cnn_lstm_v1.zip)

Download this and paste it inside models folder.

## Output

<img src="static/screenshot-app.jpg"/>

<img src="https://github.com/sethuiyer/Image-to-Image-search/raw/bootstrap/webapp.png"/>

## Tips

- Install elasticsearch and always check if elastic search process is running before launching server.py or index_database.py.

* Instead of using the upload functionality, paste all your images inside `static/img` folder followed by `python index_database.py` to index all those images.

- If you want to delete the indexed images, do `sh delete_index.sh`

# About

<!-- ROADMAP -->

## Roadmap

See the [open issues](https://github.com/wx-chevalier/tensorflow-image-search/issues) for a list of proposed features (and known issues).

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- ACKNOWLEDGEMENTS -->

## Acknowledgements

- [sethuiyer/Image-to-Image-search](https://github.com/sethuiyer/Image-to-Image-search)

- [Sis](https://github.com/matsui528/sis)

## Copyright & More | 延伸阅读

笔者所有文章遵循[知识共享 署名 - 非商业性使用 - 禁止演绎 4.0 国际许可协议](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.zh)，欢迎转载，尊重版权。如果觉得本系列对你有所帮助，欢迎给我家布丁买点狗粮(支付宝扫码)~

![技术视野](https://s2.ax1x.com/2019/12/03/QQJLvt.png)

您还可以前往 [NGTE Books](https://ng-tech.icu/books/) 主页浏览包含知识体系、编程语言、软件工程、模式与架构、Web 与大前端、服务端开发实践与工程架构、分布式基础架构、人工智能与深度学习、产品运营与创业等多类目的书籍列表：

![NGTE Books](https://s2.ax1x.com/2020/01/18/19uXtI.png)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/wx-chevalier/tensorflow-image-search.svg?style=flat-square
[contributors-url]: https://github.com/wx-chevalier/tensorflow-image-search/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/wx-chevalier/tensorflow-image-search.svg?style=flat-square
[forks-url]: https://github.com/wx-chevalier/tensorflow-image-search/network/members
[stars-shield]: https://img.shields.io/github/stars/wx-chevalier/tensorflow-image-search.svg?style=flat-square
[stars-url]: https://github.com/wx-chevalier/tensorflow-image-search/stargazers
[issues-shield]: https://img.shields.io/github/issues/wx-chevalier/tensorflow-image-search.svg?style=flat-square
[issues-url]: https://github.com/wx-chevalier/tensorflow-image-search/issues
[license-shield]: https://img.shields.io/github/license/wx-chevalier/tensorflow-image-search.svg?style=flat-square
[license-url]: https://github.com/wx-chevalier/tensorflow-image-search/blob/master/LICENSE.txt
