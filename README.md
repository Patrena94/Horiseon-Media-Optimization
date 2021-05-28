# Code Refactor Starter Code
In review of the Horiseon, the search engine optimization heading at the top was inactive. Activated the link by adding <div id="search-engine-optimization" class = "search-engine-optimization">
Cleaned up the index.html by adjusting the positions of the /> at the end of the following items

Removed the following lines of code:
.search-engine-optimization h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

.online-reputation-management h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

.social-media-marketing h2 {
    margin-bottom: 20px;
    font-size: 36px;
}
The above lines of code consolidated into the following code: .hero h2{ 
    margin-bottom: 20px;
    font-size: 36px;
}
Removed the following lines of code:
.search-engine-optimization img {
    max-height: 200px;
}

.online-reputation-management img {
    max-height: 200px;
}

.social-media-marketing img {
    max-height: 200px;
}
The removed code was consolidated into the following code: 
.content img {
    max-height: 200px;
}
The following lines of code were removed:

.benefit-lead {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-brand {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}
The removed code was intergrated into the following code:
.benefits {
    margin-right: 20px;
    padding: 20px;
    clear: both;
    float: right;
    width: 20%;
    height: 100%;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #2589bd;
    margin-bottom: 32px;
    Color: #ffffff
}
The following lines of code were removed:
.benefit-lead h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-brand h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
}
The removed code was consolidated into the following code:

.benefits h3{ 
    margin-bottom: 10px;
    text-align: Center;
}
The following code was removed:


.benefit-lead img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}


.benefit-brand img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}
The code was consolidated into the following code:
.benefits img{
    display: block;
    margin: 10px auto;
    max-width: 150px;
} red