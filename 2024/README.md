# cluster2024.github.io
- [Website preview](https://hirota-na.github.io/2024/)
- The website is base on IEEE Cluster 2023 site https://clustercomp.org/2023/
- No jekyll source files found. All the html files are manually modified.

# Main Actions:
- The items are based on https://github.com/ieeecluster/ieeecluster.github.io/blob/master/2023/README.md .

## Done
- Create a team for new year (say 2024)
- Give Team permission for repo 2024
- Create a private repo for 2024
- Clone project locally
  - git clone git@github.com:ieeecluster/ieeecluster.github.io.git
- Copy previous year (2023) into 2024
- Update robots.txt
- Update sitemap.xml


## Pending
- Waiting for IEEE Cluster 2024 logo.
- Update header photo
  - Added <p style="font-size:small;"> Photo © KOBE TOURISM BUREAU</p> to html files.
  - Better photo cropping and/or positioning needed for the responsive design HTML.
- Twitter and Facebook?
  - ``The latest news is also shown in Twitter/ieeecluster''

## Ongoing: Updating html files.
- point base on each html to 2024 instead of 2023
  - Change all files to point to new 2023
  - ```<base href="/2023/"> to <base href="/2024/">```
- Rename Cluster 22 to 23 (pointing the last conference website)
- Rename Cluster 23 to 24
- Updating venue.
  - Santa Fe (2023) to Kobe (2024).

- Progress
  - done
    - robots.txt
    - ./404.html
    - ./index.html
    - ./policy.html

  - Ongoing
    - ./contact/index.html
      - email info for public
      - Need email info
        - General Co-Chair	James Lin

    - ./committees/index.html
      - Latest status needed.

  - Do them later...
    - ./venue/index.html
  
    - ./authors/index.html
    - ./double_blind.html
    - ./keynotes/index.html
    - ./mentoring/index.html
    - ./news/index.html
    - ./papers/index.html
    - ./posters/index.html
    - ./program/at_a_glance.html
    - ./program/index.html
    - ./registration/index.html
    - ./sponsors/index.html
    - ./tutorials/index.html
    - ./workshops/call/index.html
    - ./workshops/index.html


## Todo
- Update theme color
- Updated chairs info
- Change image from previous to new image
- Change Date and location
- Update venue into dev
- Fix gmaps location
- update footer 2021 line
- Add sponsors chair
- Updated chairs in papers, posters and workshops
- Update Venue info
- Before publishing make index.html broken_index.html
- Change CPFs to TBD
- Fix Sponsor amounts
- Make sure sponsors are correctly worded
- Update Workshop CPF
- Update Committee information
- Update CFP
- Update Visa information
- Update Registration info.
- Update Poster Committee
- Update the created program.
  - Make sure u have all timeslots correctly defined. Each id in the timeslot should be unique so that your pop ups work.  
- Update author information - make sure we have all cps link, submission link, and author submission dates for main conference. workshop, and posters correctly updated.


# Info: List of html
find . -name '*.html'
- ./404.html
- ./index.html
- ./assets/fonts/iconfont-preview.html
- ./authors/index.html
- ./committees/index.html
- ./contact/index.html
- ./double_blind.html
- ./keynotes/index.html
- ./mentoring/index.html
- ./news/index.html
- ./papers/index.html
- ./policy.html
- ./posters/index.html
- ./program/at_a_glance.html
- ./program/index.html
- ./registration/index.html
- ./sponsors/index.html
- ./tutorials/index.html
- ./venue/index.html
- ./workshops/call/index.html
- ./workshops/index.html


