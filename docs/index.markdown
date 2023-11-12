---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<center><h1>MaxMasterCoder</h1></center>
<center><a href="/mods/"><img src="/images/MaxMasterCoder.png" width=230 height = 230></a></center>
<center><h1>Visit my <a href="/mods/">Mods</a></h1></center>
<br>
<br>
<br>
<br>
<br>
<center><h1><p id="totaldownloads">Loading Downloads...</p></h1><center>

<a href="https://modrinth.com/user/MaxMasterCoder" target="_blank"><img src="/images/modrinth_tiny.png"></a>
<a href="https://legacy.curseforge.com/members/maxmastercoder/projects" target="_blank"><img src="/images/curseforge_tiny.png"></a>

<script>
    function ModrinthUserDownloads(id) {
        var Modrinthrequest = new XMLHttpRequest();
        Modrinthrequest.open("GET", "http://api.modrinth.com/v2/user/"+id+"/projects", false);
        Modrinthrequest.send(null);
        var downloads = 0;
        var user = JSON.parse(Modrinthrequest.responseText);
        for (var project in user) {
            downloads += user[project]["downloads"];
        }
        return downloads;
    }
    var totaldownloads = document.getElementById("totaldownloads");
    totaldownloads.innerHTML = "Total Modrinth Downloads: "+ModrinthUserDownloads("vyGa4JgX");
</script>