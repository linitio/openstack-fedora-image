<div id="top"></div>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/linitio/openstack-fedora-image">
    <img src="images/logo.png" alt="Logo" width="150" height="150">
  </a>

<h3 align="center">Fedora image for OpenStack</h3>

  <p align="center">
    Simple port of Fedora cloud image for OpenStack environments.
    <br />
    <a href="https://github.com/linitio/openstack-fedora-image/wiki"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/linitio/openstack-fedora-image/issues">Report Bug</a>
    ·
    <a href="https://github.com/linitio/openstack-fedora-image/issues">Request Feature</a>
  </p>
</div>

<!-- ABOUT THE PROJECT -->
## About The Project

This project is a simple port of Fedora Cloud images from Fedora repository for OpenStack environments.  
This image is strictly the same that the original, the only changes has been made are:

- Patch network_manager.py (cloud-init) to use /128 instead of /64

This image is updated when Fedora released a new version on their public repository [here](https://alt.fedoraproject.org/en/cloud/ "Fedora Cloud Images Repository").



<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### How to use this image

1. Set your OpenStack environment variables
2. Download the latest image from [release page](https://github.com/linitio/openstack-fedora-image/releases "Release page")
3. Upload image to your OpenStack environment
   ```sh
   openstack image create --disk-format=qcow2 --container-format=bare --file Fedora-Cloud-Base-37-1.7.x86_64.qcow2 'Fedora Cloud 37'
   ```

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the GPL-3.0 License. See `LICENSE.md` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Kevin Allioli - [@linit_io](https://twitter.com/linit_io) - kevin@linit.io

Project Link: [https://github.com/linitio/openstack-fedora-image](https://github.com/linitio/openstack-fedora-image)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/linitio/openstack-fedora-image.svg?style=for-the-badge
[contributors-url]: https://github.com/linitio/openstack-fedora-image/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/linitio/openstack-fedora-image.svg?style=for-the-badge
[forks-url]: https://github.com/linitio/openstack-fedora-image/network/members
[stars-shield]: https://img.shields.io/github/stars/linitio/openstack-fedora-image.svg?style=for-the-badge
[stars-url]: https://github.com/linitio/openstack-fedora-image/stargazers
[issues-shield]: https://img.shields.io/github/issues/linitio/openstack-fedora-image.svg?style=for-the-badge
[issues-url]: https://github.com/linitio/openstack-fedora-image/issues
[license-shield]: https://img.shields.io/github/license/linitio/openstack-fedora-image.svg?style=for-the-badge
[license-url]: https://github.com/linitio/openstack-fedora-image/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/kevinallioli

