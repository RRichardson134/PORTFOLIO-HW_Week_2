PORTFOLIO_PROJECT_HW_WEEK_2

Created online portfolio to display current and future projects.

-HTML
-CSS

/*Created nav bar with working links to about me, contact, resume*/

    <nav>
            <ul>
                <li>
                    <a href="#about_me">About Me</a>
                <li>
                    <a href="#Work">Work</a>
                <li>
                    <a href="mailto: rhettmrichardson@gmail.com">Contact Me</a>
                <li>
                    <a href="./Assets/Resume_July_2021.docx.pdf">Resume</a>
            </ul>
        </nav>


/*Utilized multiple selectors in CSS to adjust image spacing/sizing:*/

#pic1 {
  height: 500px;
  width: 500px;
  margin-top: 1%;
  margin-bottom: 1%;
  margin-left: -10%;
  margin-right: -10%;
}

/*Created flex-boxes for additional adjustments to sections*/

.header {
    display: flex;
    padding: 10px;
    font-family: "Trebuchet MS", "Lucida Sans Unicode", "Lucida Grande", "Lucida Sans", Arial, sans-serif;
    background-color: #0f0901;    
    justify-content: space-between;
    
}

.flexboxP {
  flex-direction: row;
  flex-wrap: wrap;
  justify-content:space-evenly ;
  height: 100%;
  width: auto;
}

.flexboxchild {

