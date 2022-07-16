# Code Refactor Starter Code

A navigation tag was given to the header tabs to link to sections below the page . 


     <!-- navigation -->
    <header>
    <div class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
            <ul>
                 <!-- List item element-->
                <li>
                    <!-- Anchor element -->
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </nav>
    </div>
</header>



The sections below the page inwhich the navigating headers were linked to was also given a class to consolidate the CSS declarations. 

For instance  the "White" class 
class="white">
    <h3 class="white h3">Lead Generation</h3>
    <img src="./assets/images/lead-generation.png" class="white img" />
    
    the white class consolidated the below CSS declarations below for example: 
    
.white {
    margin-bottom: 32px;
    color: #ffffff;
}

.white h3 {
    margin-bottom: 10px;
    text-align: center;
}

.white img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

Git hub link to page. 
https://github.com/munozgit85/develop.git
