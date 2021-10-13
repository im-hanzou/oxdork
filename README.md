# Repo Under Maintenance!!
**Use the Pypi version to avoid errors**

<code> **$ pip install oxdork**</code>

<code> **$ oxdork --help**</code>













![Screenshot_20210827-111909-removebg-preview](https://user-images.githubusercontent.com/74001397/131107876-db415339-0c1d-4876-8665-fe9b76c4518c.png)

![Python Version](https://img.shields.io/badge/python-3.x-blue?style=flat&logo=python)
![OS](https://img.shields.io/badge/OS-GNU%2FLinux-red?style=flat&logo=linux)
![GitHub](https://img.shields.io/github/license/rlyonheart/oxdork?ystyle=flat)
![CodeFactor](https://www.codefactor.io/repository/github/rlyonheart/0xdork/badge)
[![Downloads](https://static.pepy.tech/personalized-badge/oxdork?period=total&units=international_system&left_color=black&right_color=orange&left_text=Downloads)](https://pepy.tech/project/oxdork)
![Lines of code](https://img.shields.io/tokei/lines/github/rlyonheart/0xdork)
![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/rlyonheart/oxdork?include_prereleases)
![GitHub repo size](https://img.shields.io/github/repo-size/rlyonheart/oxdork)
![0xdork](images/0xdork.gif)



![IMG_20210922_200225](https://user-images.githubusercontent.com/74001397/134488831-a82c78b4-4dd0-41ad-ac71-e14e53b85f13.jpg)


 # Google dorking
 Google hacking, also named Google dorking, is a hacker technique that uses Google Search and other Google applications to find security holes in the configuration and computer code that websites are using. Google dorking could also be used for OSINT(Open Source Intelligence).

 **oxdork** *uses Google dorking techniques and Google dorks to find security holes and misconfigurations in web servers*.

# Basic Google dorks
| Dork         | Usage     | Example |
| ------------- |:---------:|:-------:|
| <code>allintext:</code> | *finds all specified terms in the title of a page* |  **allintext:passwords** |
| <code>inurl:</code> | *finds a specified string in the url of a page*      |   **inurl:index.php?id=1** |
| <code>site:</code> |  *locks a search on a specified site or domain*  |  **site:example.com**  |
| <code>intitle:</code> |  *finds a specified strings in the title of a page* |  **intitle:"your text here"** |
| <code>link:</code> | *searches for all links to a specified site or domain* | **link:example.com** |
| <code>cache:</code> | *returns Google's cached copy of a specified url page* | **cache:www.example.com** |
| <code>info:</code> | *returns summary information about a specified url* | **info:https://example.com** |

# Installation & Usage
**Clone this repo**:
> <code>$ git clone https://github.com/rlyonheart/oxdork.git</code>

> <code>$ cd oxdork</code>

> <code>$ python oxdork -h</code>

**Or Install from Pypi**:

> <code>$ pip install oxdork</code>

> <code>$ oxdork -h</code>

# Optional Arguments

| Flag           | Or            |MetaVar|                 Usage|
| ------------- |:-------------:|:----------------------:|:---------:|
| <code>-c</code>           | <code>--count</code>    | **NUMBER** |  *number of dork results to return (default is 50)* |
| <code>-o</code>      | <code>--outfile</code>      |   **FILENAME** |  *output filename*  |
| <code>-v</code> | <code>--verbose</code>  |  |  *run program in verbose mode*  |


# Notes
* *Use VPN for better experience.*

* *If search query contains spaces, it should be put inside quote* **" "** *symbols.*

* *Sending more than 5 requests in less than 5 minutes will return a 429 error code. That is why using VPN is recommemded.*


# oxlite
*A lightweight faster version of **oxdork** with no verbosity.*
![0xdork_lite_1](https://user-images.githubusercontent.com/74001397/134694843-72b7a12d-9f67-4e3d-9fae-a7480200da97.gif)


# Optional Arguments
| Flag           | Or            |MetaVar|                 Usage|
| ------------- |:-------------:|:----------------------:|:---------:|
| <code>query</code>           |     | **SEARCH QUERY** |  *search query* |
| <code>-o</code>      | <code>--outfile</code>      |   **OUTFILE** |  *Output filename with extension*  |
| <code>-h</code> | <code>--help</code>  |  **HELP**  |  *View help message*  |

# oxlite.sh

*A bash version of the python oxlite*

* *Run* <code>$ bash oxlite.sh</code>
* *then enter query*


# Queries
A collection of 5,568 common dork queries [here](https://github.com/rlyonheart/oxdork/tree/master/dork_queries)

  
*by* [Richard Mwewa](https://about.me/rlyonheart)
 



