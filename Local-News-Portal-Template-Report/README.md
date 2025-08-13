# Local News Portal Template

## Team Members
- **Jyothika Merin Babu** (2462334)  
- **Maxine Danica M** (2462342)  
- **Sanjukta Banik** (2462361)  

**College Email ID:**  
- jyothika.merin@btech.christuniversity.in  
- maxine.danica@btech.christuniversity.in  
- sanjukta.banik@btech.christuniversity.in  

**Course:** UI/UX Design Fundamentals  
**Instructor Name:** Dr Nagaveena  
**Institution:** Christ University  
**Date of Submission:** 13/08/2025  

---

## Abstract
This project aims to design and develop a responsive local news portal template using only HTML and CSS. The website provides a structured platform to display news categories, featured headlines, and breaking news banners. The focus was on clean UI, intuitive navigation, and responsiveness across devices. The core technologies used are HTML5 for content structure and CSS3 for styling and layout. The final outcome is a professional, accessible, and easy-to-navigate template suitable for local news agencies or blogs.

---

## Objectives
- Design a user-friendly interface using modern UI principles  
- Develop a fully responsive layout using only HTML and CSS  
- Implement structured HTML5 semantic elements  
- Apply CSS styling for branding, layout, and responsive behavior  
- Ensure accessibility and readability across devices  

---

## Scope of the Project
- Focused on front-end design only  
- No JavaScript or server-side integration  
- Intended for desktop, tablet, and mobile viewports  
- Used only open-source tools and pure code (no libraries)  

---

## Tools & Technologies Used
| Tool / Technology | Purpose |
| --- | --- |
| HTML5 | Markup and content structure |
| CSS3 | Styling and layout management |
| VS Code | Code editor |
| Chrome DevTools | Testing and debugging |

---

## HTML Structure Overview
- Used semantic tags: `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`  
- Structured into reusable sections: About, Projects, Contact  
- Navigation menu using `<ul>` and anchor links for smooth scrolling  

---

## CSS Styling Strategy
- Used external CSS file (`style.css`)  
- Organized with comments and sections  
- Techniques used:  
  - Flexbox and Grid for layout  
  - Media Queries for responsiveness  

---

## Sample Code

### HTML
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>News Portal</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.0/css/all.min.css" integrity="sha512-DxV+EoADOkOygM4IR9yXP8Sb2qwgidEmeqAEmDKIOfPRQZOWbXCzLC6vjbZyy0vPisbH2SyW27+ddLVCN+OMzQ==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="logo-ad">
        <div class="logo"><h1 class="blue">NEWS PORTAL</h1></div>
        <div class="advert">For Advertisement</div>
    </div>

    <div class="navbar">
        <div class="panelops">
            <div class="panel-all">
                <i class="fa-solid fa-bars"></i> All
            </div>
            <p>HOME</p>
            <p>CATEGORY</p>
            <p>SINGLE NEWS</p>
            <p>DROPDOWN</p>
            <p>CONTACT</p>
        </div>
        <div class="search-box">
            <select>
                <option>All</option>
            </select>
            <input type="text" placeholder="Search here..">
            <div class="search-icon">
                <i class="fa-solid fa-magnifying-glass"></i>
            </div>
        </div>
    </div>

    <div class="breaking-news">
        <span class="label">Breaking News</span>
        <marquee>STAY INFORMED WITH THE LATEST HEADLINES AND UPDATES FROM AROUND THE WORLD...</marquee>
    </div>

    <div class="main-news">
        <div class="left-big">
            <img src="breakingnews.jpg" alt="Breaking News">
            <div class="news-title">
                <span class="tag">Business</span> Aug 13, 2025
                <h2>STAY INFORMED WITH THE LATEST HEADLINES AND UPDATES FROM AROUND THE WORLD...</h2>
            </div>
        </div>
        <div class="right-small">
            <div class="small-news">
                <img src="liberty.jpg" alt="">
                <span class="tag">Business</span> <p class="date">Aug 13, 2025</p>
                <p class="text">RESTORATION PLANS ANNOUNCED FOR THE <i>STATUE OF LIBERTY</i> AHEAD OF ANNIVERSARY...</p>
            </div>
            <div class="small-news">
                <img src="biharvoter.webp" alt="">
                <span class="tag">Business</span> <p class="date">Aug 13, 2025</p>
                <p class="text">SUPREME COURT ISSUES LANDMARK VERDICT ON CONSTITUTIONAL AMENDMENT..</p>
            </div>
            <div class="small-news">
                <img src="DONALD.jpg" alt="">
                <span class="tag">Business</span> <p class="date">Aug 13, 2025</p>
                <p class="text">TRUMP SIGNALS STRONG POLITICAL COMEBACK IN FIERY SPEECH...</p>
            </div>
            <div class="small-news">
                <img src="football.jpg" alt="">
                <span class="tag">Business</span> <p class="date">Aug 13, 2025</p>
                <p class="text">CRYSTAL PALACE STUNS OPPONENT WITH THRILLING VICTORY AT HOME GROUND...</p>
            </div>
        </div>
    </div>

</body>
</html>
```
### CSS
```css
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
}

.top-bar {
    background: #333;
    color: white;
    font-size: 14px;
    padding: 5px 20px;
    display: flex;
    justify-content: space-between;
}

.search-icon {
    color: white;
    margin-right: 10px;
    justify-content: center;
    align-items: center;
}

.top-right a {
    color: white;
    margin-left: 10px;
    text-decoration: none;
}

.logo-ad {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 15px;
    background: rgb(201, 196, 196);
}

.logo {
    font-size: 20px;
    font-weight: bold;
}

.logo .blue {
    color: #00aaff;
}

.advert {
    background: #0e99de;
    padding: 10px 30px;
    color: white;
    font-size: 20px;
}

.navbar {
    background: #201919;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 20px;
    height: 50px;
}

.panelops p {
    display: inline;
    color: white;
    margin-left: 10px;
}

.panelops p:hover {
    color: orange;
    border: 2px solid white;
}

.panelops {
    font-size: 0.9rem;
    display: flex;
    gap: 10px;
}

.panel-all:hover {
    color: orange;
    border: 2px solid white;
}

.panel-all {
    color: white;
    display: flex;
    align-items: center;
    gap: 10px;
}

.search-box {
    display: flex;
}

.search-box input {
    padding: 5px;
}

.search-box button {
    background: #00aaff;
    border: none;
    color: white;
    padding-left: 50px;
    cursor: pointer;
}

.breaking-news {
    display: flex;
    align-items: center;
    background: #111;
    color: white;
    padding: 5px 20px;
}

.breaking-news .label {
    background: #00aaff;
    padding: 5px 10px;
    margin-right: 10px;
}

.main-news {
    display: flex;
    gap: 20px;
    padding: 15px;
}

.main-news:hover {
    border: 3px solid gray;
}

.text:hover {
    text-decoration: underline;
    color: indigo;
}

.date:hover {
    color: blue;
}

.left-big {
    flex: 2;
    background: white;
}

.left-big img {
    width: 100%;
}

.news-title {
    padding: 15px;
}

.news-title .tag {
    background: #00aaff;
    color: white;
    padding: 3px 8px;
    font-size: 12px;
}

.news-title h2 {
    margin: 10px 0 0;
}

.right-small {
    flex: 1;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 10px;
}

.small-news {
    background: white;
    padding: 5px;
    height: 400px;
    display: grid;
}

.small-news:hover {
    border: 2px solid gray;
}

.small-news img {
    width: 100%;
}

.small-news .tag {
    background: #00aaff;
    color: white;
    font-size: 10px;
    padding: 2px 5px;
}
```

## Conclusion
The **Local News Portal Template** successfully demonstrates how a clean, responsive, and accessible news platform can be created using only HTML and CSS. It prioritizes user experience, ensuring that readers can easily navigate through different news categories, view breaking headlines, and consume content comfortably across devices. By leveraging semantic HTML and organized CSS, the project provides a scalable base for future enhancements such as JavaScript interactivity and backend integration.

---

## References
- L&T LMS: https://learn.lntedutech.com/Landing/MyCours  
- MDN Web Docs – HTML & CSS References  
- Google Fonts – Web Typography Guidelines  

