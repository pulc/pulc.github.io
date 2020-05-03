---
layout: page_min
title: Projects
bigimg: /assets/img/percy.png
subtitle: Projects I took part in
---

<head>

<style>

  .contbody {
    margin-left: 20%;
    margin-right: 20%;
    height: 80%;
}

#overlay{
    position: fixed; 
    width: 100%; 
    height: 100%; 
    top: 0px; 
    left: 0px; 
    background-color: #000; 
    opacity: 0.7;
    filter: alpha(opacity = 70) !important;
    display: none;
    z-index: 100;
}
#overlayContent{
    position: fixed; 
    width: 100%;
    top: 75px;
    text-align: center;
    display: none;
    overflow: hidden;
    z-index: 100;
    max-width: 100vw;
    max-height: 90vh;
}
#contentGallery{
    margin: 0px auto;
}
.imgBig, .imgSmall, .imgLong{
    cursor: pointer;
}
.imgLong{
    height:100%;
    width: 100%;
}
.imgSmall{
    height:200px;
    width: 100%
}
* {
  box-sizing: border-box;
}

body {
  background-color: #f1f1f1;
}

/* Center website */
.main {
  max-width: 1000px;
  margin: auto;
}

h1 {
  font-size: 50px;
  word-break: break-all;
}

.row {
  margin: 8px -16px;
}

/* Add padding BETWEEN each column */
.row,
.row > .column {
  padding: 8px;
}


.row,
.row > .columnPercy {
  padding: 20px;
}

/* Create four equal columns that floats next to each other */
.column {
  float: left;
  width: 33.33%;
}

/* Create four equal columns that floats next to each other */
.columnPercy {
  float: left;
  width: 20%;
}

/* Clear floats after rows */ 
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Content */
.content {
  background-color: white;
  padding: 10px;
}
.center{
      text-align: center;
}
h4{
      text-align: center;
}
/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 900px) {
  .column, .columnPercy {
    width: 50%;
  }
  .contbody {
    margin-left: 20%;
    margin-right: 20%;
    height: 80%;
}

}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column, .columnPercy {
    width: 100%;
  }
  .contbody {
    margin-left: 10%;
    margin-right: 10%;
    height: 80%;
}
}

</style>
</head>

<div id="overlay"></div>
<div id="overlayContent">
    <img class="imgBig" src="" alt="" />
</div>

<div class="contbody">
                <div id="grid">

<p>
    So far, I did not take part in many projects. (But I would like to!)
</p>
<p>
    Here is a small overview of th- past projects I participated in. Most of my work is university related stuff.
</p>
        <h2>Zeiterfassung Pierburg</h2>
        <p>
            Zeiterfassung Pierburg was the first big project I worked independently on. I developed an application that was used in production in <a href="https://www.rheinmetall-automotive.com/marken/pierburg/"> Pierburg Berlin</a>. Pierburg is a subsidiary of Rheinmetall Automotive. In their factory in Berlin, they produce car parts such as electric throttles. 
            The app was developed for the workers on assembly lines to mark their working times and write down the number of items they produced in their shift.
        </p>
        <p>
            The application has also an access layer for the managing directors for the calculation of productivity for certain assembly lines.
        </p>
        <p>
            The application was developed using <b><i>ASP.NET MVC</i></b> and <b><i>SQL Server</i></b> database system.
        </p>
    <div class="row">
        <div class="column">
            <div class="content">
                    <img class="imgSmall" src="/assets/img/pierburg/img4.jpg" alt="Mountains">
                    <h4>Dashboard</h4>
            </div>
        </div>
        <div class="column">
            <div class="content">
                <img class="imgSmall" src="/assets/img/pierburg/img1.jpg" alt="Lights">
                <h4>Overview</h4>
            </div>
        </div>
        <div class="column">
            <div class="content">
                <img class="imgSmall" src="/assets/img/pierburg/img3.jpg" alt="Lights">
                <h4>Register</h4>
            </div>
        </div>
        </div>
        <h2>Percy - The Social Racoon</h2>
        <p>
            Percy is a <i><b>Progressive Web App</b></i> developed for a university project. The project was a collaboration of 6 people:
            <i>Rommy Haacke</i>, <i>Kevin Klaus</i>, <i>Gülcan Kurkut</i>, <i>Markus Westphaal</i>, <i>Katharina Wunder</i> and myself, supervised by <i>David Koschnick</i> from FU in Berlin.
        </p>
        <p>
            Percy is a social assistant app. It reminds you to get in contact with the people you choose based on individual criteria. Feel free to test the project on <a href="https://percy-app.herokuapp.com/">https://percy-app.herokuapp.com/ </a>.
        </p>
        <p>
            The app was built with <i><b>Django</b></i> using <i><b>React</b></i> + <i><b>Redux</b></i> JS libraries. The UI was designed using <i><b>Material UI</b></i> design.
            The biggest part of the app was developed by Romy while the UI design by Kevin. I did not contribute very much but was still an active member of the team. <a href="https://docs.google.com/document/d/1VcY1tI6jBWmjm4MhTef9jwusBKpyH4SK4l7AqdNp4UQ/edit?usp=sharing/">Here </a> you can read the whole documentatoin (in German).
        </p>
        <p>
        </p>
    <div class="row">
        <div class="columnPercy">
            <div class="content">
                    <img class="imgLong" src="/assets/img/percy/percy0.png" alt="Mountains">
                    <h4>Login</h4>
            </div>
        </div>
        <div class="columnPercy">
            <div class="content">
                    <img class="imgLong" src="/assets/img/percy/percy01.png" alt="Mountains">
                <h4>Onboarding</h4>
            </div>
        </div>
        <div class="columnPercy">
            <div class="content">
                    <img class="imgLong" src="/assets/img/percy/percy1.png" alt="Mountains">
                <h4>Contact View</h4>
            </div>
        </div>
                <div class="columnPercy">
            <div class="content">
                    <img class="imgLong" src="/assets/img/percy/percy2.png" alt="Mountains">
                <h4>Settings</h4>
            </div>
        </div>
                <div class="columnPercy">
            <div class="content">
                    <img class="imgLong" src="/assets/img/percy/percy3.png" alt="Mountains">
                <h4>Dashboard</h4>
            </div>
        </div>
        <!-- END GRID -->
    </div>


<h2>Game Development</h2>
        <p>
            I took two game development classes at the university: <b><i>Game Engines</i></b> and <b></b>Advanced Game Programming
        </p>
        <p>
            I wouldn't say I got good at it but it was definitely fun! If getting a job in game development wouldn't be so difficult, I might go for it!
        </p>
        <p>
            I am putting some gifs here. I don't think I should really showcase the results. I studied mostly <b><i>Unity</i></b> but developed also a game in <b><i>Unreal Engine</i></b>. 
        </p>
    <div class="row">
        <div class="column">
            <div class="content">
                    <img class="imgSmall" src="/assets/img/gameengines/unity.gif" alt="Mountains">
                    <h4>Unity</h4>
            </div>
        </div>
        <div class="column">
            <div class="content">
                <img class="imgSmall" src="/assets/img/gameengines/unreal.gif" alt="Lights">
                <h4>Unreal</h4>
            </div>
        </div>
        <div class="column">
            <div class="content">
                <img class="imgSmall" src="/assets/img/gameengines/vfx.gif" alt="Lights">
                <h4>VFX in Unity</h4>
            </div>
        </div>
        </div>
        <h2>Mattermost Translator</h2>
        <p>
            As my Bachelor's Thesis, I developed an automatic translator for the <a href="https://mattermost.com/">Mattermost</a> app. Mattermost is an open-souce alternative to Slack or Microsoft Teams. You can read it <a target="_blank" rel="noopener noreferrer" href="/assets/Thesis_Ulc.pdf">here</a>.
        </p>
        <p>
            I am not super proud as it wasn't a substantional programming effort. I integrated the <a href="https://mymemory.translated.net/">MyMemory Translated API </a> as a webhook and processed it in a <b><i>Node.js</i></b> webservice.
        </p>
        <p>
            I didn't know what to put in the screenshots, it doesn't look impressive. I added a state diagram, <b>prooving</b> how capable I am of creating them.
        </p>
    <div class="row">
        <div class="column">
            <div class="content">
                    <img class="imgSmall" src="/assets/img/thesis/thesis1.png" alt="Mountains">
                    <h4>Screenshot 1</h4>
            </div>
        </div>
        <div class="column">
            <div class="content">
                <img class="imgSmall" src="/assets/img/thesis/thesis2.png" alt="Lights">
                <h4>Screenshot 2</h4>
            </div>
        </div>
        <div class="column">
            <div class="content">
                <img class="imgSmall" src="/assets/img/thesis/thesis3.png" alt="Lights">
                <h4>State Diagram</h4>
            </div>
        </div>
        </div>
        </div>
        <hr>
        I am hoping to add more projects in the future!
        


<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.bundle.min.js"></script>
<!-- Third party plugin JS-->
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery-easing/1.4.1/jquery.easing.min.js"></script>


<script>
    $("#grid img").click(function() {
        $(".imgBig").attr("src", $(this).prop('src'));
        $("#overlay").show('slow');
        $("#overlayContent").show('slow');
    });
    $(".imgBig").click(function() {
        $(".imgBig").attr("src", "");
        $("#overlay").hide();
        $("#overlayContent").hide();
    });
    $(document).ready(function() {
        var small = {
            width: "800px",
            height: "424px"
        };
        var large = {
            width: "1600px",
            height: "849px"
        };
        var count = 1;
        $("#imgtab").css(small).on('click', function() {
            $(this).animate((count == 1) ? large : small);
            count = 1 - count;
        });
    });
</script>