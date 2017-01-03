// ==UserScript==
// @name        Liste d'ami(e)s
// @include     https://code.jquery.com/jquery-3.1.1.min.js
// @version      0.0.2
// @description  Permet de voir la liste des ami(e)s qui t'on supp
// @author       Yann GRADEL
// @match        https://www.facebook.com/*/friends?lst=*
// @grant        GM_getValue
// @grant        GM_setValue
// @grant        GM_xmlhttpRequest
// ==/UserScript==

window.onscroll = function (e) {

    if(document.getElementById("pagelet_timeline_medley_likes"))
    {
        var totalFriend = parseInt(document.getElementById("u_0_1f").children[1].innerHTML);
        var toto = parseInt(document.getElementById("pagelet_timeline_medley_friends").children[1].children[0].children.length - 1) * 20;
        var divfriends = document.getElementById("pagelet_timeline_medley_friends");
        console.log(totalFriend);
        console.log(toto);
        if(toto == totalFriend)
        {
            console.log("ca descend !!");
            for(var i=0;i<=parseInt(document.getElementById("pagelet_timeline_medley_friends").children[1].children[0].children.length - 1);i++)
            {
                if(divfriends.children[1].children[0].children[i].children.length > 0)
                {
                    console.log(divfriends.children[1].children[0].children[i]);
                    for(var f = 0;divfriends.children[1].children[0].children[i].children.length;f++)
                    {
                        //console.log(divfriends.children[1].children[0].children[i].children[f].children[0].children[1].children[1].children[0].children[1].children[0].children[0].innerHTML);
                    }
                }
                //il reste plus qu'a récupérer le nom est de l'enregistrer
            }
        }
        console.log(document.getElementById("pagelet_timeline_medley_friends").children[1].children[0].children[1].children.length);
    }
};
