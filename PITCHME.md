---?video=https://data.cyverse.org/dav-anon/iplant/home/tswetnam/train_to_graz.mp4

@snap[north span-100 text-center]
![GRAPHQL](/assets/imagery/cyverse_cmyk.png)
@fa[quote-graphql font-montserrat text-white text-11](TU Graz, Austria) 
@fa[quote-graphql font-montserrat text-white text-09](November 19, 2019)
@fa[quote-graphql font-montserrat text-white text-09](Tyson L. Swetnam) 
@snapend 

---?color=linear-gradient(180deg, white 30%, #567AD2 50%)

@snap[north]
### Key Concepts
@snapend

@snap[midpoint list-content-verbose span-100 font-montserrat text-white text-09]
@ul
- Basics of Linux Distributions
- Version Control with Git & GitHub
- Internal and External Communication
- Websites and Documentation
@ulend
@snapend

---?color=linear-gradient(180deg, white 30%, #567AD2 50%)

<img src="https://media.giphy.com/media/ize2r20ICQONq/giphy.gif" width="600">
@fa[quote-graphql font-montserrat text-white text-11 fragment](really?)

---?color=linear-gradient(180deg, white 30%, #567AD2 50%)

@fa[quote-graphql font-montserrat text-black text-12](Why are YOU here?)

<img src="https://media.giphy.com/media/b7MdMkkFCyCWI/giphy.gif" height="500">

---?image=https://media.giphy.com/media/YDj8Ot6mIbJYs/giphy.gif

@snap[north fragment]
@fa[quote-graphql font-montserrat text-white text-11](Just kidding, this is a part of the talk) 
@snapend

---?color=linear-gradient(180deg, white 30%, #567AD2 50%)
@snap[north span-100]
@fa[quote-graphql font-montserrat text-black text-11](Modern web, cloud, and HPC are dominated by Linux and its derivatives)
@snapend

@snap[west span-50]
<img src="https://upload.wikimedia.org/wikipedia/commons/8/83/World_Wide_Smartphone_Sales.png" height="400">
@snapend

@snap[east span-50]
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0d/Operating_systems_used_on_top_500_supercomputers.svg/1280px-Operating_systems_used_on_top_500_supercomputers.svg.png" height="430">
@snapend

@snap[south span-100]
<span style="font-weight: bold; font-size: 50%; color:#ffffff"> source: https://en.wikipedia.org/wiki/Usage_share_of_operating_systems </span>
@snapend

---?color=linear-gradient(180deg, white 30%, #567AD2 50%)

@snap[north-west span-50]
@fa[quote-graphql font-montserrat text-black text-11](Basics of Linux Distributions)
@fab[linux fa-lg] @fab[ubuntu fa-lg] @fab[centos fa-lg] @fab[suse fa-lg] @fab[redhat fa-lg] @fab[fedora fa-lg]
@snapend

@snap[west span-33 fragment]
@box[bg-green font-montserrat text-white text-09 rounded box-padding](Pro # Open Source, Infinitely Customizable)
@snapend

@snap[south-west span-33 fragment]
@box[bg-orange font-montserrat text-white text-09 rounded box-padding](Con # Difficult to use, Dependencies)
@snapend

@snap[north-east span-33 fragment]
@fa[quote-graphql font-montserrat text-black text-11](Run in Windows)
@fab[windows fa-lg]
@snapend

@snap[east span-50 fragment]
<img src="https://images.anandtech.com/doci/11401/wsl.png" height="400">
@snapend

@snap[south-east span-50 fragment]
@fa[quote-graphql font-montserrat text-white text-11](Windows Subsystem for Linux 2 "WSL2")
@snapend

---?color=linear-gradient(180deg, white 30%, #567AD2 50%)

@fa[quote-graphql font-montserrat text-black text-11](Change is scary!)

<img src="https://media.giphy.com/media/1CNsm9ZkHF0m4/giphy.gif" height="500">

@snap[south-west span-50 fragment]
@fa[quote-graphql font-montserrat text-white text-11](CyVerse)
@snapend

@snap[south-east span-50 fragment]
@fa[quote-graphql font-montserrat text-white text-11](Status Quo)
@snapend

---?color=linear-gradient(180deg, white 30%, #567AD2 50%)

@fa[quote-graphql font-montserrat text-black text-11](A brave colorful new place)

<img src="https://media.giphy.com/media/GkQBupPcf5b1e/giphy.gif" height="500">

---?color=linear-gradient(180deg, white 30%, #567AD2 50%)

[Alan Perlis, 1982 Epigrams on Programming](https://web.archive.org/web/19990117034445/http://www-pu.informatik.uni-tuebingen.de/users/klaeren/epigrams.html)

**54. Beware of the Turing Tarpit in which everything is possible but nothing of interest is easy.**

<img src="https://img00.deviantart.net/58af/i/2012/093/a/c/la_brea_tar_pits_by_felipenn-d4uxy05.jpg" width="400">

---?color=linear-gradient(180deg, white 30%, #567AD2 50%)

*different OS + third party software + updates/upgrades + redeployment* → 
 <span style="font-weight: bold; font-size: 100%; color:#FF0000">_Dependency Hell_ </span> 
 
<img src="https://imgs.xkcd.com/comics/python_environment_2x.png" height="400"> <!-- .element: class="fragment" --> <img src="https://pbs.twimg.com/media/DB6QcoNVYAA-w6N.jpg" height="400"> <!-- .element: class="fragment" -->

 <span style="font-weight: bold; font-size: 50%; color:#FF0000"> Source: XKCD.com, E. Dolstra 2006 https://nixos.org/~eelco/pubs/phd-thesis.pdf </span> 

---?color=linear-gradient(180deg, white 30%, #567AD2 50%)

@snap[north-west]
@fa[quote-graphql font-montserrat text-black text-11](Version Control with Git)
@fab[git fa-lg] @fab[github fa-lg] @fab[gitlab fa-lg]
@snapend

@snap[west span-33 fragment]
@box[bg-green font-montserrat text-white text-09 rounded box-padding](Pros # Reproducibility, Redundancy, Collaboration)
@snapend

@snap[south-west span-33 fragment]
@box[bg-orange font-montserrat text-white text-09 rounded box-padding](Con # Steep learning curve)
@snapend

---?image=https://media.giphy.com/media/1SMYk3HBzaK3e/giphy.gif
@snap[south-west text-smallcaps text-white]
Data Science 
@snapend

@snap[south-east text-smallcaps text-white]
Domain Science 
@snapend

---?color=linear-gradient(180deg, white 30%, #567AD2 50%)

@snap[north-west]
Productivity Software
@snapend

@snap[west list-content-verbose span-100 text-white]
@ul
- Slack @fab[slack fa-lg] vs Gitter @fab[gitter fa-lg]
- GitHub @fab[github fa-lg] vs GitLab @fab[gitlab fa-lg] vs BitBucket @fab[bitbucket fa-lg]
- ReadTheDocs vs Bookdown vs GitHub Pages
- QUBES vs Protocols.io
@ulend
@snapend

---?color=linear-gradient(180deg, white 30%, #567AD2 50%)
@fa[quote-graphql font-montserrat text-white text-11](Don't take to long)
<img src="https://media.giphy.com/media/3rgXBAKopU55wtfp6g/giphy.gif" width 500>
@fa[quote-graphql font-montserrat text-white text-11](Pick what your team needs and go)

---?color=linear-gradient(180deg, white 30%, #567AD2 50%)

---?image=https://media.giphy.com/media/WoD6JZnwap6s8/giphy.gif
@fa[quote-graphql font-montserrat text-white text-11](Welcome to the digital world)

---?image=https://media.giphy.com/media/9uI9WOCm7WCf4wwhro/giphy.gif
@snap[south text-white]
Yep.
@snapend

---?image=https://media.giphy.com/media/iOXMcT2qEiIUg/giphy.gif
@snap[north text-white]
Don't Panic
@snapend

---?color=linear-gradient(180deg, white 30%, #567AD2 50%)

@snap[north-west]
Project Management
@snapend

@snap[west list-content-verbose span-100 text-white]
@ul
- Communication: Slack @fab[slack fa-lg] vs Gitter @fab[gitter fa-lg]
- Collaboration: GitHub @fab[github fa-lg] vs GitLab @fab[gitlab fa-lg]
- Documentation: ReadTheDocs or Bookdown or Protocols.io
@ulend
@snapend

---?image=https://media.giphy.com/media/wUCgLRvDdtWs8/giphy.gif
# Have Data, Will Travel

---?color=linear-gradient(180deg, white 30%, #567AD2 50%)

### Building the "best" workflows and pipelines takes time and experience

<img src="https://d13ezvd6yrslxm.cloudfront.net/wp/wp-content/images/edgeoftomorrow-livedierepeat-cruise-blunt-postercrop.jpg" width="800">

---?color=linear-gradient(180deg, white 30%, #567AD2 50%)

### Getting stuff done.

<span style="font-size: 100%; color:#FF0000"> 1) Do the things. <!-- .element: class="fragment" -->
<span style="font-size: 120%; color:#F9FF33"> → 2) Do the things right. <!-- .element: class="fragment" -->

<span style="font-size: 200%; color:#58FF33"> → 3) Do the things well. <!-- .element: class="fragment" -->

---?color=linear-gradient(180deg, white 30%, #567AD2 50%)

---?image=https://media.giphy.com/media/uKpWZU3VXLprW/giphy.gif
@snap[north text-white]
Next Time ...
@snapend

@snap[south text-white]
Peer Review
@snapend

+++

## Acknowledgments

GIFs by Giphy.com

All digital images shown this presentation are available online and are the property of their creators, their web addresses are visible in the source code of this presentation at: https://github.com/tyson-swetnam/cyverse-tugraz/PITCHME.md 

---?image=assets/imagery/endslide.png
