My website was to make an art gallery for my paintings. 

I commented using HTML commenters <!-- --> in this readme file to point out where I used some of the less obvious things. 

Find it on GitHUB https://github.com/benburw3ll/SBA1

HTML
Use HTML tables <<--Used on many pages, index is a good example-->
Implement at least two uses for forms - <<!--This is found on contact me page-->
Dropped Down Menu <<!--This is found on the contact form and about me --->>


CSS - Inline, internal, and external styling 
<<!-- inline found on index.html blog table,internal found on index.html backround gradient, external found on mystyles.css->

Javascript- External scripts
<!--To hide the Art Pieces text details (while viewing in full size from gallery) this was used.-->


function myFunction() {
    var x = document.getElementById("artCaption");
    if (x.style.display === "none") {
        x.style.display = "block";
    } else {
        x.style.display = "none";
    }
}
