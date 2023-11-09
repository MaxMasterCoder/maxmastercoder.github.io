---
layout: page
title: Mods
permalink: /mods/
---

<style>

    .switch {
    position: relative;
    display: inline-block;
    width: 60px;
    height: 34px;
    }

    .switch input { 
    opacity: 0;
    width: 0;
    height: 0;
    }

    .slider {
    position: absolute;
    cursor: pointer;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-color: #1bd86a;
    -webkit-transition: .4s;
    transition: .4s;
    }

    .slider:before {
    position: absolute;
    content: "";
    height: 26px;
    width: 26px;
    left: 4px;
    bottom: 4px;
    background-color: #2c2c2c;
    -webkit-transition: .4s;
    transition: .4s;
    }

    input:checked + .slider {
    background-color: #f16436;
    }

    input:focus + .slider {
    box-shadow: 0 0 1px #f16436;
    }

    input:checked + .slider:before {
    -webkit-transform: translateX(26px);
    -ms-transform: translateX(26px);
    transform: translateX(26px);
    }

    /* Rounded sliders */
    .slider.round {
    border-radius: 34px;
    }

    .slider.round:before {
    border-radius: 50%;
    }
    
</style>

<img src="/images/modrinth_tiny.png">
<label class="switch">
  <input type="checkbox" id="toggle" onclick="myFunction()">
  <span class="slider round"></span>
</label>
<img src="/images/curseforge_tiny.png">

<script>
function myFunction() {
  var checkBox = document.getElementById("toggle");
  var cloakingfeatured = document.getElementById("cloakingfeatured");
  var cloakingversions = document.getElementById("cloakingversions");
  var fps_essentialsfeatured = document.getElementById("fps_essentialsfeatured");
  var fps_essentialversions = document.getElementById("fps_essentialversions");
  if (checkBox.checked == true){
    cloakinglink.href = "https://www.curseforge.com/minecraft/mc-mods/cloaking";
    cloakingfeatured.href = "https://www.curseforge.com/minecraft/mc-mods/cloaking/files/4816672";
    cloakingfeatured.style = "color:#f16436;";
    cloakingversions.href = "https://www.curseforge.com/minecraft/mc-mods/cloaking/files";
    cloakingversions.style = "color:#f16436;";
    fps_essentialslink.href  = "https://www.curseforge.com/minecraft/modpacks/fps-essentials";
    fps_essentialsfeatured.href = "https://www.curseforge.com/minecraft/modpacks/fps-essentials/files/4768470";
    fps_essentialsfeatured.style = "color:#f16436;";
    fps_essentialsversions.href = "https://www.curseforge.com/minecraft/modpacks/fps-essentials/files";
    fps_essentialsversions.style = "color:#f16436;";
    capechangerlink.href = "https://www.curseforge.com/minecraft/mc-mods/capechanger";
    capechangerfeatured.href = "https://www.curseforge.com/minecraft/mc-mods/capechanger/files/4809188";
    capechangerfeatured.style = "color:#f16436;";
    capechangerversions.href = "https://www.curseforge.com/minecraft/mc-mods/capechanger/files";
    capechangerversions.style = "color:#f16436;";
    cloakerlink.href = "https://www.curseforge.com/minecraft/mc-mods/cloaker";
    cloakerfeatured.href = "https://www.curseforge.com/minecraft/mc-mods/cloaker/files/4768332";
    cloakerfeatured.style = "color:#f16436;";
    cloakerversions.href = "https://www.curseforge.com/minecraft/mc-mods/cloaker/files";
    cloakerversions.style = "color:#f16436;";
  } else {
    cloakinglink.href = "https://modrinth.com/mod/cloaking";
    cloakingfeatured.href = "https://modrinth.com/mod/cloaking/version/3.0.0-1.20.2";
    cloakingfeatured.style = "color:#1bd86a;";
    cloakingversions.href = "https://modrinth.com/mod/cloaking/versions";
    cloakingversions.style = "color:#1bd86a;";
    fps_essentialslink.href  = "https://modrinth.com/modpack/fps-essentials";
    fps_essentialsfeatured.href = "https://modrinth.com/modpack/fps-essentials/version/1.20.2";
    fps_essentialsfeatured.style = "color:#1bd86a;";
    fps_essentialsversions.href = "https://modrinth.com/modpack/fps-essentials/versions";
    fps_essentialsversions.style = "color:#1bd86a;";
    capechangerlink.href = "https://modrinth.com/mod/capechanger";
    capechangerfeatured.href = "https://modrinth.com/mod/capechanger/version/2.0.0";
    capechangerfeatured.style = "color:#1bd86a;";
    capechangerversions.href = "https://modrinth.com/mod/capechanger/versions";
    capechangerversions.style = "color:#1bd86a;";
    cloakerlink.href = "https://modrinth.com/datapack/cloaker";
    cloakerfeatured.href = "https://modrinth.com/datapack/cloaker/version/w5aQuity";
    cloakerfeatured.style = "color:#1bd86a;";
    cloakerversions.href = "https://modrinth.com/datapack/cloaker/versions";
    cloakerversions.style = "color:#1bd86a;";
  }
}
</script>



<table>
    <tr>
        <th>Projects</th>
    </tr>
    <tr>
        <td><big><a href="#cloaking">#Cloaking</a></big></td>
    </tr>
    <tr>
        <td><big><a href="#fps-essentials">#Fps Essentials</a></big></td>
    </tr>
    <tr> 
        <td><big><a href="#capechanger">#CapeChanger</a></big></td>
    </tr>
    <tr>
        <td><big><a href="#cloaker">#Cloaker</a></big></td>
    </tr>
</table>
<hr>
<hr>
<hr>

<p>
<h1><div><a href="#cloaking" id="cloaking">Cloaking (Forge & Fabric) </a><a href="https://modrinth.com/mod/cloaking" id="cloakinglink">➲</a></div></h1>
<img src="https://cdn-raw.modrinth.com/data/PCGwziNW/558391aa6ff9fb987e2c7ba1e4d184ce65428b3c.png" width=100 height =100>
</p>
Adds a new enchantment which<br>
hides your name tag if you're<br>
wearing it on your helmet.<br>
<h4><a href="https://modrinth.com/mod/cloaking/version/3.0.0-1.20.2" style="color:#1bd86a;" id="cloakingfeatured">Download Featured Version</a><h4>
<h4><small><a href="https://modrinth.com/mod/cloaking/versions" style="color:#1bd86a;" id="cloakingversions">See more versions</a></small></h4>

<hr>
<hr>
<hr>

<p>
<h1><div><a href="#fps-essentials" id="fps-essentials">Fps Essentials </a><a href="https://modrinth.com/modpack/fps-essentials" id="fps_essentialslink">➲</a></div></h1>
<img src="https://cdn-raw.modrinth.com/data/WeGC6tLm/c8baf21ba1d0dbc28d81d164f09a2250a8b57a6b.jpeg" width=100 height =100>
</p>
A modpack full of the main FPS<br>
boosters in the community. Perfect<br>
for low-end laptops and computers.<br>
It also allows running shaders with<br>
little to no lag.<br>
<br>
<h4><a href="https://modrinth.com/modpack/fps-essentials/version/1.20.2" style="color:#1bd86a;" id="fps_essentialsfeatured">Download Featured Version</a><h4>
<h4><small><a href="https://modrinth.com/modpack/fps-essentials/versions" style="color:#1bd86a;" id="fps_essentialsversions">See more versions</a></small></h4>

<hr>
<hr>
<hr>

<p>
<h1><div><a href="#capechanger" id="capechanger">CapeChanger </a><a href="https://modrinth.com/mod/capechanger" id="capechangerlink">➲</a></div></h1>
<img src="https://cdn-raw.modrinth.com/data/g2igxsu3/13de9d1440aab44b63da63652a46e2e27da8a75e.png" width=100 height =100>
</p>
Allows you to put a custom cape or<br>
change your current capes texture<br>
through a resource pack.<br>
<br>
<h4><a href="https://modrinth.com/mod/capechanger/version/2.0.0" style="color:#1bd86a;" id="capechangerfeatured">Download Featured Version</a><h4>
<h4><small><a href="https://modrinth.com/mod/capechanger/versions" style="color:#1bd86a;" id="capechangerversions">See more versions</a></small></h4>

<hr>
<hr>
<hr>

<p>
<h1><div><a href="#cloaker" id="cloaker">Cloaker (Forge, Fabric & Quilt) </a><a href="https://modrinth.com/datapack/cloaker" id="cloakerlink">➲</a></div></h1>
<img src="https://cdn-raw.modrinth.com/data/qTtyWxGO/9d8c88b530943e1bf0e4cd82592b6e197592ee5f.jpeg" width=100 height =100>
</p>
Hides your player tag if you're<br>
wearing a leather cap.<br>
<br>
<h4><a href="https://modrinth.com/datapack/cloaker/version/w5aQuity" style="color:#1bd86a;" id="cloakerfeatured">Download Featured Version</a><h4>
<h4><small><a href="https://modrinth.com/datapack/cloaker/versions" style="color:#1bd86a;" id="cloakerversions">See more versions</a></small></h4>