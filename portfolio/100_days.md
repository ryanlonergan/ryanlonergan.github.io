---
layout: page
title: 100 Days of Projects
description: >
  Details of my journey with completing 100 days of complex coding projects in Python
hide_description: true
sitemap: false
---

<style>

.banner {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  center;
}

.justify {
  text-align: justify;
}

.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 50%;
}

* {
  box-sizing: border-box;
}

.column25 {
  float: left;
  width: 25%;
  padding: 10px;
}

.column30 {
  float: left;
  width: 30%;
  padding: 10px;
}

.column40 {
  float: left;
  width: 40%;
  padding: 10px;
}

.column50 {
  float: left;
  width: 50%;
  padding: 10px;
}

.column60 {
  float: left;
  width: 60%;
  padding: 10px;
}

.column70 {
  float: left;
  width: 70%;
  padding: 10px;
}

.column75 {
  float: left;
  width: 75%;
  padding: 10px;
}

.row:after {
  content: "";
  display: table;
  clear: both;
}

@media screen and (max-width: 600px) {
  .column25 {
    width: 100%;
  }
  .column30 {
    width: 100%;
  }
  .column40 {
    width: 100%;
  }
  .column50 {
    width: 100%;
  }
  .column60 {
    width: 100%;
  }
  .column70 {
    width: 100%;
  }
  .column75 {
    width: 100%;
  }
}

.button_round {
  display: block;
  margin-left: auto;
  margin-right: auto;
  center;
  width: 100px;
  border-radius: 50px;
  box-shadow: 0 3px 5px 0 rgba(0, 0, 0, 0.1), 0 4px 6px 0 rgba(0, 0, 0, 0.1);
}

.button_round:hover{
  position: relative;
  top: -1px;
  box-shadow: 0 6px 10px 0 rgba(0, 0, 0, 0.15), 0 8px 12px 0 rgba(0, 0, 0, 0.15);
}

.button_rectangle {
  display: block;
  margin-left: auto;
  margin-right: auto;
  center;
  width: 175px;
}

.button_rectangle:hover{
  position: relative;
  top: -1px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.15), 0 6px 10px 0 rgba(0, 0, 0, 0.15);
}

</style>

* This unordered list will be replaced by the table of contents
{:toc}

<img src="/assets/img/100_days/100_days_cover.jpg"  alt="100_days" class="banner">

### Overview

This page documents and details my experience with the <a href="https://www.udemy.com/course/100-days-of-code" target="_blank">100 Days of Code Python course by Angela Yu</a>. The program covers various aspects of computer science and programming through project-based learning and there is an independent complete project for each day of the course that cover the breadth of what is possible with Python. To view the entire GitHub Repo, please <a href="https://github.com/ryanlonergan/100_days_of_projects" target="_blank">click here</a>, or continue reading for more details.

### Motivation

From my education and experience, I gained aptitude with Python, but there were vast gaps in my knowledge. While I could train, run, evaluate, and iterate machine learning models with scikit-learn, Keras or TensorFlow, I lacked greater exposure with object orientated programming, graphical user interfaces, user design or other areas of computer science. Although I knew about these concepts and used them, I felt like I needed to improve them to better round out my skillset and to communicate about problems from various perspectives. Thus, when I found this course, I thought it would be a perfect experience to not only better my Python skills, but to build up my talents with the foundations of computer science. While there have been days where I felt incredibly frustrated with the process, the practice and experience I have gained have become invaluable to me and I truly feel like I have become a better coder through it.

### Projects

I have listed all my projects below in descending order as the latter days are generally more complex than the earlier ones. For each project, I have linked its page on my GitHub where I have provided the code and some more information, including a short description, some quick stats and my thoughts about the project including any notes, relevant links, or other points of interest.

If you are unsure of where to start, I have singled out a few projects I think are particularly interesting or feel free to start anywhere in the full table below. More projects are still being added daily, so check back later for more of my work.

<div>
  <div class='column50'>
    <ul class='center'>
      <li><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_46_spotify_playlist_time_machine" target="_blank">Spotify Playlist Time Machine</a></li>
      <li><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_39_flight_deal_tracker" target="_blank">Flight Deal Tracker</a></li>
      <li><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_11_blackjack" target="_blank">Blackjack</a></li>
    </ul>
  </div>
  <div class='column50'>
    <ul class='center'>
      <li><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_33_iss_tracker" target="_blank">ISS Tracker</a></li>
      <li><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_33_kanye_quotes" target="_blank">Kanye Quote Generator</a></li>
      <li style="list-style-type: none"></li>
    </ul>
  </div>
</div>


<table>
  <tr>
    <th>Day</th>
    <th>Project</th>
    <th>Link</th>
  </tr>
  <tr>
    <td>46</td>
    <td><strong>Spotify Playlist Time Machine</strong> - scrapes Billboard's Top 100 Songs from a requested date with Beautiful Soup, filters the data with regular expression and then uses Spotipy to handle the Spotify API to search for the songs and add them to a playlist automatically</td>
    <td><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_46_spotify_playlist_time_machine" target="_blank"><img src="/assets/img/github_logo.png" alt="View Project on Github" class="button_round"></a></td>
  </tr>
  <tr>
    <td>45</td>
    <td><strong>Movie Web Scraper</strong> - scrapes an online list of top movies using Beautiful Soup and creates a text file with the movie titles and their rankings</td>
    <td><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_45_movie_web_scraper" target="_blank"><img src="/assets/img/github_logo.png" alt="View Project on Github" class="button_round"></a></td>
  </tr>
  <tr>
    <td>44</td>
    <td><strong>CSS Site</strong> - the final day of the web development module that created a modern looking personal website focusing primarily on CSS styling</td>
    <td><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_44_css_site" target="_blank"><img src="/assets/img/github_logo.png" alt="View Project on Github" class="button_round"></a></td>
  </tr>
  <tr>
    <td>43</td>
    <td><strong>CSS Resume</strong> - a continuation of the previous day that added CSS directly into the page and also a stylesheet, vastly improving the look of the page</td>
    <td><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_43_css_resume" target="_blank"><img src="/assets/img/github_logo.png" alt="View Project on Github" class="button_round"></a></td>
  </tr>
  <tr>
    <td>42</td>
    <td><strong>HTML Resume</strong> - a continuation of the previous day that added readibility through tables and forms</td>
    <td><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_42_html_resume" target="_blank"><img src="/assets/img/github_logo.png" alt="View Project on Github" class="button_round"></a></td>
  </tr>
  <tr>
    <td>41</td>
    <td><strong>HTML Personal Website</strong> - a simple resume or CV site that mimics the minimalistic style of some famous CS professors and serves as an introduction to HTML</td>
    <td><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_41_html_personal_site" target="_blank"><img src="/assets/img/github_logo.png" alt="View Project on Github" class="button_round"></a></td>
  </tr>  
  <tr>
    <td>40</td>
    <td><strong>Flight Deal Tracker</strong> - a continuation of the previous day with added functionality, including an independent user signup on Replit, extra error handling and automatic checking for layovers if there are limited flights due to Covid</td>
    <td><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_40_flight_deal_tracker_cont" target="_blank"><img src="/assets/img/github_logo.png" alt="View Project on Github" class="button_round"></a></td>
  </tr>
  <tr>
    <td>39</td>
    <td><strong>Flight Deal Tracker</strong> - automatically finds and manages flight deals for a user and texts them if there is a fare reduction for a location it monitors</td>
    <td><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_39_flight_deal_tracker" target="_blank"><img src="/assets/img/github_logo.png" alt="View Project on Github" class="button_round"></a></td>
  </tr>
  <tr>
    <td>38</td>
    <td><strong>Workout Tracker</strong> - asks a user about their exercise in natural language and records detailed information in a workout log on Google Sheets</td>
    <td><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_38_workout_tracker" target="_blank"><img src="/assets/img/github_logo.png" alt="View Project on Github" class="button_round"></a></td>
  </tr>
  <tr>
    <td>37</td>
    <td><strong>Habit Tracker</strong> - a program that interacts with the Pixela API to track habits through pixels and color, similar to the GitHub contribution graph</td>
    <td><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_37_habit_tracker" target="_blank"><img src="/assets/img/github_logo.png" alt="View Project on Github" class="button_round"></a></td>
  </tr>
  <tr>
    <td>36</td>
    <td><strong>Stock Alert</strong> - a SMS alert that checks a stock's closing prices and if a significant change is detected, it sends a text to the user letting them know about it along with recent news articles for the company</td>
    <td><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_36_stock_alert" target="_blank"><img src="/assets/img/github_logo.png" alt="View Project on Github" class="button_round"></a></td>
  </tr>
  <tr>
    <td>35</td>
    <td><strong>Rain Alert</strong> - a SMS alert that checks the weather forecast through the OpenWeather API and sends a text to let the user know that they may want to bring an umbrella</td>
    <td><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_35_rain_alert" target="_blank"><img src="/assets/img/github_logo.png" alt="View Project on Github" class="button_round"></a></td>
  </tr>
  <tr>
    <td>34</td>
    <td><strong>GUI Trivia Game</strong> - a trivia game that retrieves questions from the Open Trivia Database API and uses OOP to organize its functions and logic</td>
    <td><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_34_gui_trivia_game" target="_blank"><img src="/assets/img/github_logo.png" alt="View Project on Github" class="button_round"></a></td>
  </tr>
  <tr>
    <td>33</td>
    <td><strong>ISS Tracker</strong> - detects if the International Space Station (ISS) is overhead and will email the user if they should be able to see it in the night sky</td>
    <td><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_33_iss_tracker" target="_blank"><img src="/assets/img/github_logo.png" alt="View Project on Github" class="button_round"></a></td>
  </tr>
  <tr>
    <td>33</td>
    <td><strong>Kanye Quote Generator</strong> - a GUI that uses the <a href='https://kanye.rest' target="_blank">kanye.rest API</a> to retrieve and display quotes that he has said</td>
    <td><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_33_kanye_quotes" target="_blank"><img src="/assets/img/github_logo.png" alt="View Project on Github" class="button_round"></a></td>
  </tr>
  <tr>
    <td>32</td>
    <td><strong>Automatic Birthday Emailer</strong> - automatically checks for birthdays on the current date and sends out a randomized email to the birthday person preventing the user from ever forgetting a birthday again</td>
    <td><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_32_automatic_birthday_emailer" target="_blank"><img src="/assets/img/github_logo.png" alt="View Project on Github" class="button_round"></a></td>
  </tr>
  <tr>
    <td>31</td>
    <td><strong>Flashcard App</strong> - a GUI flashcard app that quizzes the user on vocabulary from a dynamically managed csv file</td>
    <td><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_31_flashcard_app" target="_blank"><img src="/assets/img/github_logo.png" alt="View Project on Github" class="button_round"></a></td>
  </tr>
  <tr>
    <td>30</td>
    <td><strong>Password Manager Expanded</strong> - an expansion of the previous day that changes the data to be stored in a json file, allows for searching through recorded data and incorporates greater error and exception handling</td>
    <td><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_30_password_manager_expanded" target="_blank"><img src="/assets/img/github_logo.png" alt="View Project on Github" class="button_round"></a></td>
  </tr>
  <tr>
    <td>29</td>
    <td><strong>Password Manager</strong> - a GUI password manager that stores security details locally and has the ability to generate strong random passwords</td>
    <td><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_29_password_manager" target="_blank"><img src="/assets/img/github_logo.png" alt="View Project on Github" class="button_round"></a></td>
  </tr>
  <tr>
    <td>28</td>
    <td><strong>Pomodoro Timer</strong> - a GUI timer that follows the Pomodoro Technique and updates its UI based on the user's progress</td>
    <td><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_28_pomodoro_timer" target="_blank"><img src="/assets/img/github_logo.png" alt="View Project on Github" class="button_round"></a></td>
  </tr>
  <tr>
    <td>20</td>
    <td><strong>Snake</strong> - a recreation of the famous Snake game using OOP to divide the logic and the Turtle module for the interface</td>
    <td><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_20_snake" target="_blank"><img src="/assets/img/github_logo.png" alt="View Project on Github" class="button_round"></a></td>
  </tr>
  <tr>
    <td>11</td>
    <td><strong>Blackjack</strong> - a recreation of blackjack that uses functions and recursion to organize the game</td>
    <td><a href="https://github.com/ryanlonergan/100_days_of_projects/tree/main/day_11_blackjack" target="_blank"><img src="/assets/img/github_logo.png" alt="View Project on Github" class="button_round"></a></td>
  </tr>      
</table>

<!--
TEMPLATE FOR TABLE ROW

<tr>
  <td>DAY</td>
  <td><strong>TITLE</strong> - <em>DESCRIPTION COMING SOON</em></td>
  <td><a href="LINK" target="_blank"><img src="/assets/img/github_logo.png" alt="View Project on Github" class="button_round"></a></td>
</tr>

-->
