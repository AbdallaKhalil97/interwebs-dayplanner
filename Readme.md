in this assignment i was tasked with creating a workday planner.
to better understand the mechanics of the code i used various Jscript functions and used HTML and CSS and used third party APIs (bootstrap, google fonts and fontawesome.com) to make some of my layout work for me.
i will be including snippets and vaguely explaining what function they serve on the application.

first some HTML:
`<header class="jumbotron">
<h1 class="display-3">Abdalla's Work Day Scheduler</h1>
<p class="lead">A simple calendar app for scheduling your work day</p>
<p id="currentDay" class="lead"></p>
</header>`
in this scenario i used bootstrap's jumbotron class to create a big section in the middle
and then proceded to create containers for the actual input sections on the app.

`<div class="input-group input-group-lg" data-hour="9">
        <div class="input-group-prepend">
            <!-- Added time-block class -->
            <span class="input-group-text time-block block1"></span>
        </div>
        <input type="text" class="form-control form9" aria-label="Large">
        <!-- <input class="btn saveBtn" type="submit" value="Save"> -->
        <button class="btn saveBtn"><i class="far fa-save"></i></button>

    </div>`