
HTML CSS Git: Code Refactor home Work.

My CODE:

My code is Generally trying to refactor a company website in to a better one .that is, I have improved the code’s SEO options and have made it much more cleaner and better to follow with good and précised comments.
INSTALATION

This will just be to host the website in to any hosting sites, but I will be using the Github pages to host this website. It also requires you to have the image files with the style.css file pushed up to github before hosting. To host this site on github pages, • Open the repo which contains this file, • Go to settings at the top • Screw down to github pages or you can search in the search bar for pages • Go to where it is labeled source and change the Branch from non to master. • Continue and save your changes Then tha is great, your site is up. HTMLCODE
<title>HORISION</title>
Horision
        <div class="header h1 .seo">
            <ul>
                <li>
                    <a href="#"><i>Search Engine Optimization</i></a *\adding a litle bid of indentation to the link\*> 
                </li>
                <li>
                    <a href="#" *changing to empty links\*><i>Online Reputation Management</i></a>
                </li>
                <li>
                     <a href="#"><i>Social Media Marketing</i></a>
                  </li>
            </ul>
        </div>
    </nav>
    </div>
</header>
<main *\introducing the main element\*> 
    <article *\introducing the article element \*>
    <div class="section-image">
        <img src="../assets/images/01-HTML-Git-CSS_02-Homework_Develop_assets_images_digital-marketing-meeting.jpg" alt="image of metting"*\adding the image souce and also the altenative of the image\*/>
        <div class="content">

     <div class="search-engine-optimization">
        <img src="../assets/images/01-HTML-Git-CSS_02-Homework_Develop_assets_images_search-engine-optimization.jpg" class="float-left" alt="engine optimization img"*\adding the alt imge attribute for a better experience should in case image fails to load />
        <h2>Search Engine Optimization</h2>
        <p>
            The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
        </p>
    </div>
    <div class="online-reputation-management">
        <img src="../assets/images/01-HTML-Git-CSS_02-Homework_Develop_assets_images_online-reputation-management.jpg" class="float-right" alt="img of an online repution management"*\adding the attribute and giving the image a relative souce \*/> 
        <h2>Online Reputation Management</h2>
        <p>
            The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
        </p>
    </div>
    <div class="social-media-marketing">
        <img src="../assets/images/assets_images_social-media-marketing.jpg" class="float-left" alt="sicial media macketing img" *\ including the alt attribute here to display in case of image failure to read due to bad signal or file moved\*/> 
        <h2>Social Media Marketing</h2>
        <p>
            Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
        </p>
    </div>
</div>
<aside>
    <div class="benefit-lead">
    
        <h3>Lead Generation</h3>
        <img src="../assets/images/01-HTML-Git-CSS_02-Homework_Develop_assets_images_lead-generation.png"alt="lead-generation imge" *\adding an image relative souce and an alt attribut of the image\*/>
        <p>
            Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
        </p>
    </div>
    <div class="benefit-brand">
        <h3>Brand Awareness</h3>
        <img src="../assets/images/01-HTML-Git-CSS_02-Homework_Develop_assets_images_brand-awareness.png"alt="imge brand " />
        <p>
            Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
        </p>
    </div>
    <div class="benefit-cost">
        <h3>Cost Management</h3>
        <img src="../assets/images/01-HTML-Git-CSS_02-Homework_Develop_assets_images_cost-management.png" alt =cost management img *\ giving the image a correct src attribute and alt\*/>
        <p>
            As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
        </p>
    </div>
</aside>

<footer *\replacing the div class footer with the element footer for a cleaner code\*>
     <div class="footer h2">
        <h2>Made with ❤️️ by Horiseon</h2>
        <p>
        &copy; 2019 Horiseon Social Solution Services, Inc.

</footer> 
</article>
</main>
AFTER CORRECTION,ITS LOOKS LIKE WHAT WE SEE ABOVE.
NOW THE CSS CODE
•	{ box-sizing: border-box; padding: 0; margin: 0; } body { background-color: #c5cac0; } header, footer { background-color: #2a607c; font: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif; }
header { padding: 75px; background-color: #2a607c; color: rgb(211, 200, 200); text-align: center; width: 100%;
}
.header h1 { display: inline-block; font-size: 60px; font-weight: bold; text-align: center; float: left; color: white;
}
.header h1 .seo { color: #d9dcd6; background-color: #2a607c; text-align: left; font-size: 40px; font-weight: bold; }
.header div ul li { display: inline-block; margin-left: 100px; font-weight: bold; font-size: 15px; }
a { color: #ffffff; text-decoration: none; }
p { font-size: 16px; }
.hero { height: 10px; width: 100%; margin-bottom: 30px; background-image:url(a); background-size: cover; background-position: auto;
}
.float-left { float: left; margin-right: 0px; } .clearfix::after { content: ""; display: block; clear: both; }
.float-right { float: right; margin-left: 25px;
}
.content { width: 75%; display: inline-block; margin-left: 20px; }
aside { margin: 20px; padding: 10px; clear: both; float: right; width: 20%; height: 100%; font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; background-color: #2589bd; }
.benefit-cost, .benefit-brand,.benefit-lead { margin-bottom: 0px; color: #ffffff; background-color: #2589bd; padding: 35px; text-align: center; }
.benefit-brand h3,.benefit-lead h3,.benefit-cost h3 { margin: 10px; text-align: center; color: white; height: auto; }
.benefit-cost img,.benefit-lead img,.benefit-brand img { display: block; margin: 10px auto; max-width: 100px; }
.social-media-marketing,.search-engine-optimization,.online-reputation-management { margin: 20px; padding: 50px; height: 300px; font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; background-color: #0072bb; color: #ffffff; } .section-image { height: 50px; padding: 0px; width: 100%; box-sizing: border-box; }
.social-media-marketing img,.online-reputation-management img,.search-engine-optimization img { max-height: 200px; margin: 20px; padding: 20px; }
.social-media-marketing h2,.online-reputation-management h2,.search-engine-optimization h2 { margin-bottom: 20px; font-size: 36px; }
footer { padding: 40px; clear: both; font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif; text-align: center; background-color: #2a607c; width: 100%; margin-top: 10px; margin-bottom: 0px; color: white; }
.footer h2 { font-size: 10px; color: white; }
THE CHANGES HERE HAVE REALLY BEEN TOUGH cleaning up the css file and making it looks good and functions better too has not been easy .

CONTRIBUTIONS 

to contribute in this code is what i need, you can do this by
1.	checking the code in properly commenting while fixing some bugs which may be in the code.
2.	by reviewing the code pasted above,you can point out where and how i will need to inprove on this projects and should in case,i have wrong typos,you can point that out to be fixed. 3)taking more time on the lay out of the html will really help me out as i am not sure i have used yet the best tags ,elements and properties in this code.
FEED BACK you can give thisfeed backs by
1.	upvotting feature request , 2)follow up and coment on my code and also , 3)getting in touch through my personal github account for any correction or additions.
CODE OF CONDUCTS
the project has adupted the BERKERLY CODING BOOTCAMP AND micro soft open souce code of conducts you can visit the code of conduct site for micro soft for more.

CREDITS

i will like to thank out TA's for september 20/20 berkerley bootcamb for codding and all of the TA's assisting to make sure we suceed in this cause. i will also like to thank all those who will be contributing in this code to make it better.

