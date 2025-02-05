# Incredibox V9CODE PORT TEMPLATE
this was made to make sure you dont have to go thru a hassle lol

# THE GUIDE
I recommend using this site first then you can go back to this: https://boogoxseal.xyz/tools/appjs
![versionexamplev9code](https://github.com/user-attachments/assets/3c61c50a-1232-41e4-90c7-5a5f3f2cae7d)
can be found in the `js/script.min.js` file

to change what version you want it on you can change the "versions.v1" to like "versions.v2", "versions.v3", "versions.v4" and so on all the way up to "versions.v9" unless if you want to add a custom version
that requires some css coding and stuff

# FOR POLOS
![poloanimearrayexamplev9code](https://github.com/user-attachments/assets/818364f3-4eed-4a7a-9e2f-e2afc274d139)
can be found in the `js/script.min.js` file

# FOR BONUSES
![bonusexamplev9code](https://github.com/user-attachments/assets/a67e339e-330e-42be-8501-bd2731867c5d)
can be found in the `js/script.min.js` file



# TO CHANGE THE CHECKMARK COLOR
go to css/style.min.css and find the color
its "colV1:" and you can set it to anything like this for example colV1: "#84DCC6" which will change it
but you can set it to anything that fits that versions color

# TO ADD A NEW VERSION
go under the line of 297 and press enter and add this under it for example (change the number to whatever you want like if you want it on v2 change the number to 2) in the script min js file
   ```
   versions.v6 = { // ALIVE
  name: "Alive",
  version: "6",
  date: "2018",
  folder: "asset-v6/",
  looptime: 7111,
  bpm: 135,
  totalframe: 342,
  nbpolo: 7,
  bonusloopA: false,
  bonusendloopA: false,
  colBck: "#110521",
  col0: "#A07DFA",
  col1: "#825FD2",
  col2: "#5F3CA0",
  col3: "#371464",
  col4: "#230A41",
  animearray: [
    {
      name: "1_kick",
      color: "1e96be",
      uniqsnd: true,
    },
    {
      name: "2_snare",
      color: "1e96be",
      uniqsnd: true,
    },
    {
      name: "3_kanye",
      color: "1e96be",
      uniqsnd: true,
    },
    {
      name: "4_tuctuc",
      color: "1e96be",
      uniqsnd: true,
    },
    {
      name: "5_break",
      color: "1e96be",
      uniqsnd: true,
    },
    {
      name: "6_cribasse",
      color: "825fd2",
      uniqsnd: true,
    },
    {
      name: "7_distotut",
      color: "825fd2",
      uniqsnd: true,
    },
    {
      name: "8_screw",
      color: "825fd2",
      uniqsnd: true,
    },
    {
      name: "9_shaolin",
      color: "825fd2",
      uniqsnd: true,
    },
    {
      name: "10_shower",
      color: "825fd2",
      uniqsnd: true,
    },
    {
      name: "11_basse",
      color: "e11419",
      uniqsnd: true,
    },
    {
      name: "12_hou",
      color: "e11419",
      uniqsnd: true,
    },
    {
      name: "13_clav",
      color: "e11419",
      uniqsnd: true,
    },
    {
      name: "14_synth",
      color: "e11419",
      uniqsnd: true,
    },
    {
      name: "15_yah",
      color: "e11419",
      uniqsnd: true,
    },
    {
      name: "16_hurry",
      color: "f06400",
      uniqsnd: true,
    },
    {
      name: "17_good",
      color: "f06400",
      uniqsnd: true,
    },
    {
      name: "18_mind",
      color: "f06400",
      uniqsnd: true,
    },
    {
      name: "19_haha",
      color: "f06400",
      uniqsnd: true,
    },
    {
      name: "20_wow",
      color: "f06400",
      uniqsnd: true,
    },
  ],
  bonusarray: [
    {
      name: "Alive",
      src: "v6-b1-alive-hb",
      code: "4,6,9,14,18",
      sound: "bonus-alive",
      loop: 3,
    },
    {
      name: "Busta",
      src: "v6-b2-busta-hb",
      code: "1,2,8,11,16",
      sound: "bonus-busta",
      aspire: "aspire-busta",
      loop: 3,
    },
    {
      name: "VR",
      src: "v6-b3-vr-hb",
      code: "3,8,11,12,20",
      sound: "bonus-vr",
      aspire: "aspire-vr",
      loop: 3,
    },
  ],
};
   ```

# FOR VERSION ICON MANAGEMENT
find the sp select thing and go to sp line and find something like this
   ```
          <div class="vicon" id="icon1">
           <div class="img"></div>
           <div class="txt"></div>
           <div class="bul">
            <svg class="icn-svg"><use xlink:href="#ic-check"></use></svg>
               </div>
            </div>
  ```

that is a version icon thingy are whatever for the index and app html thats what you remove if you have extras

# ONLY HAVING ONE VERSION
it should be something like this
```
                <div id="sp-select">
                    <div class="sp-line">
                        <div class="vicon" id="icon1">
                            <div class="img"></div>
                            <div class="txt"></div>
                            <div class="bul">
                                <svg class="icn-svg"><use xlink:href="#ic-check"></use></svg>
                            </div>
                        </div>
                </div>
```

# TO ADD A VERSION
make sure its in the sp select thing or it wont work
``` 
                <div id="sp-select">
                    <div class="sp-line">
                        <div class="vicon" id="icon1">
                            <div class="img"></div>
                            <div class="txt"></div>
                            <div class="bul">
                                <svg class="icn-svg"><use xlink:href="#ic-check"></use></svg>
                            </div>
                        </div>
                        <div class="vicon" id="icon2">
                            <div class="img"></div>
                            <div class="txt"></div>
                            <div class="bul">
                                <svg class="icn-svg"><use xlink:href="#ic-check"></use></svg>
                            </div>
                        </div>
                </div>
```

its a example but just use a text editor like notepad++ or VS Code it will be helpful editing how version you want!

# MAKE YOUR MOD SUPPORTED FOR IOS?
simple in the `js/script.min.js` file find the sndext = "ogg" and vidext = "webm" and change ogg to mp3 and webm to mp4 (BUT IT DOES REQUIRE YOU TO CONVERT STUFF)

# WHAT I RECOMMEND FOR CONVERTING (to make your mod have ios support)
for audio i recommend https://online-audio-converter.com/ the reason is because you dont have a limit used it before and it was great!

for video i recommend https://www.freeconvert.com/webm-to-mp4

# NOTE 
I will make a YT tutorial of how your supposed to mod this version of incredibox so then you can do it too!

# MAIN QUESTION FOR PORTING V8 CODED MODS TO V9?
will the !0 or the !1 work?
The answer to that is yes I think I never tested that but when putting it in the script.min.js file it should work
But I highly still recommend putting the app js thru the vercel js site to get a more accurate result!
