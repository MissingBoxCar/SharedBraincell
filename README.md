# SharedBraincell
Initial Commit made for web server <nl/>
Vruk has made basic model for data
//Kat-2feb23

- Experimented with data compression (vruk)
  - Not possible
  - We were able to get it close with high level optimizations, LZMA & Base64 but maths works against us on a bytes per car angle
- Site has started work
  - Train progressing and basic data works
  - Car has first setup
- Moving to Docker for site away from CF
  - We needed to move away from the initial stateless approach as can't do the query string mechanics for reasons stated above in combination with the 2048 char limit imposed by browsers
  - Docker will host DB
    - PSQL?
  - And site, how, unknown
  - NGINX?
