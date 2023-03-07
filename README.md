<a name="readme-top"></a>
![ProgLang](https://img.shields.io/badge/Language-C%2B%2B-9cf?style=for-the-badge)
![IntToolkit](https://img.shields.io/badge/Interface-Qt5-green?style=for-the-badge)
![Issues](https://img.shields.io/github/issues/nevfuxon/starlight?color=yellow&style=for-the-badge)
![License](https://img.shields.io/github/license/nevfuxon/starlight?color=red&style=for-the-badge)
<br />
<div align="center">
  <a href="https://github.com/nevfuxon/starlight">
    <img src="https://raw.githubusercontent.com/nevfuxon/starlight/extras/resc/logo.png" alt="Starlight Logo" width="80" height="80">
  </a>

  <h3 align="center">Dynastix: Qt5 Music Player</h3>

  <p align="center">
    A simple Qt5 music player reworked from <a href="https://github.com/andreisergiu98/music-player-qt5">MPQt5</a>
    <br />
    <a href="https://github.com/revoscode/dynastix/wiki"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://raw.githubusercontent.com/revoscode/dynastix/extras/resc/logo.png">View Demo</a>
    ·
    <a href="https://github.com/revoscode/dynastix/issues">Report Bug</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

![SQt5 Preview](https://user-images.githubusercontent.com/83752061/200165308-92e3715d-c903-4a1d-ab48-1a914dba8a0e.png)

This is `starlight`; a supposed-to-be revival of [MPQt5](https://github.com/andreisergiu98/music-player-qt5) and is also my starting point on Qt5/C++ programming.

Alongside my small projects, this is probably the most promising one out of all of them. While being terrible at first, I'll try to improve it over time :)

But why? We already have better music players; like [`rhythmbox`](https://gitlab.gnome.org/GNOME/rhythmbox), or [`audacious`](https://github.com/audacious-media-player/audacious), or [`juk`](https://github.com/KDE/juk)???

Here's why:
* Boredom.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [Termux](https://termux.dev/en/)
* [Ubuntu](https://ubuntu.com/)
* [QMake](https://doc.qt.io/qt-6/qmake-manual.html)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Since I did not have setup the workflow for this repository for an automated build, you'll have to build the package yourself for now.

### Prerequisites

Get dependencies
* GCC, Make, and Git
  ```sh
  sudo apt-get install gcc g++ gdb cmake make build-essential git
  ```
* Qt5 (including dependencies for `multimedia5`)
  ```
  sudo apt-get install qtbase5-dev qtdeclarative5-dev qtmultimedia5-dev libqt5multimediawidgets5 libqt5multimedia5-plugins libqt5multimedia5 qtwebengine5-dev
  ```
On source version 0.2 or newer, the project is being rebased to the Vvave project
* QT: websockets, KConfigCore, KNotifications, KI18n, webenginewidgets (extra: taglib)
  ```
  sudo apt-get install libkf5i18n-dev libqt5webenginewidgets5 libkf5notifications-dev libkf5config-dev libqt5websockets5-dev libtagc0-dev
  ```


### Installation
1. Clone the repository
   ```sh
   git clone https://github.com/revoscode/dynastix
   ```
2. Change to source directory
   ```sh
   cd dynastix/src
   ```
3. Generate makefile and build the binary
   ```sh
   qmake;make
   ```
4. Test run if it works:
   ```sh
   ./QtMusicPlayer
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

No additional arguments are needed when running from the Terminal, but I'll add some. Someday.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [x] redo README
- [x] Refactor source files
- [ ] Add optional arguments for running in terminal
- [ ] Revamp user interface 
- [ ] Multi-language Support
    - [ ] Chinese
    - [ ] Spanish
- [ ] MPD integration
- [ ] ...and more

See this [issue](https://github.com/nevfuxon/starlight/issues/1) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what makes this project better. Any contributions you make are **greatly appreciated**.


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Twitter - [@veuxTW](https://twitter.com/veuxTW)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Acknowledging the following for this project:

* [andreisergiu98/music-player-qt5](https://github.com/andreisergiu98/music-player-qt5)
* [Cantata Music Player: for MPD integration investigation](https://github.com/CDrummond/cantata)
* [Qt5 Toolkit](https://www.qt.io/)
* [FFMPeG wrapper for QT](https://code.google.com/archive/p/qtffmpegwrapper/)
* [GitHub Pages](https://pages.github.com)
* [the entirety of the MIT license](https://opensource.org/licenses/MIT)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



# Babe
## Tiny Qt Babe Music Player

#### Babe is a tiny Qt music player to keep your favorite songs at hand

https://milohr.github.io/BabeIt/

Babe will handle your whole music collection, letting you create custom playlists to organize your music.

You can also filter your music by artist, title, album, genre, date and location. Babe let's you babe-mark your favorite YouTube music videos into your local collection by using the Chromium extension. 

Think of Babe as the playlist where all your favorite tracks at the moment are. And when needed you also have an integrated collection manager.


(a previous unfinished gtk3 version is still in my repository and I plan to turn it into a simple version of Noise for the Pantheon desktop of elementaryOS) 



##### you need to have [ taglib - knotification lib - ki18n lib - qt 5.8 libs ]installed in order to compile this app from source
any extra help to package this app is welcome and I'm willing to solve any doubts or questions about it.


<h3> To run: </h3>
qmake-qt5 && make && ./Babe

<h3> To try the Youtube Chromium extension</h3>
In Chrome/mium go to chrome://extensions/, then enable the Developer mode check box in the right upper corner, after that click on "Load unpacked extension..." and select the BabeExtension folder.

* Planned Features :
  * [5%] youtube-dl streamming
  * [90%] babe chrome-chromium extension for youtube-dl supported sites
  * [0%] krunner integration

* Expected Features :
  * [100%] simple music collection manager 
  * [100%] artist and lyrics info 
  
  
<h3> Features : </h3> 

    -Babe has three different view modes: 
    * the mini mode keeps on top of the windows and its size is just 200x200 px ,just displaying the art and playback controls
    * the playlist mode is unobtrusive and displays a list of your songs
    * the collection view let's you browse your whole music collection by tracks, artists and albums, also let's you get information about the current song playing.
    
    -search keys to filter the results: 
    
    * location:  (example: to see all the tracks from the YouTube extension: "location:youtube")
    * artist: (get all matching artists)
    * album: (get all matching albums)    
    * title: (get all matching titles)
    * genre: (get all matching genres)
    
    -quickly append search results, albums, artists and tracks to the main playlist or save them to a specific playlist
    
    -create colored mood tags for tracks that modify the main playlist color
    
    -use the chromium extension to babe your favorite youtube music videos and Babe will fetch the art and metadata of the track
    
    -quickly move between albums/artists with the playAll button that shows on hover in all the artworks
    
    -get native kde notifications for the plasma desktop
    
    -add songs to a queued special playlist if you want to play some track next
    

![alt tag](https://raw.githubusercontent.com/milohr/babe-qt/master/screenshots/playlist_mode.png)


![alt tag](https://raw.githubusercontent.com/milohr/babe-qt/master/screenshots/mini_mode.png)


![alt tag](https://raw.githubusercontent.com/milohr/babe-qt/master/screenshots/collection_view.png)


![alt tag](https://raw.githubusercontent.com/milohr/babe-qt/master/screenshots/albums_view.png) 


![alt tag](https://raw.githubusercontent.com/milohr/babe-qt/master/screenshots/artists_view.png) 


![alt tag](https://raw.githubusercontent.com/milohr/babe-qt/master/screenshots/playlists_view.png) 


![alt tag](https://raw.githubusercontent.com/milohr/babe-qt/master/screenshots/settings_view.png) 


![alt tag](https://raw.githubusercontent.com/milohr/babe-qt/master/screenshots/about_view.png) 


![alt tag](https://raw.githubusercontent.com/milohr/babe-qt/master/screenshots/chromium_extension.png) 

