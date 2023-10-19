<!DOCTYPE html>
<html>
<head>
    <title>vSchoolTrend - 教育平台</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to vSchoolTrend</h1>
        <nav>
            <ul>
                <li><a href="#">首页</a></li>
                <li><a href="#">课程</a></li>
                <li><a href="#">教师</a></li>
                <li><a href="#">关于我们</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>热门课程</h2>
            <div class="course">Course 1</div>
            <div class="course">Course 2</div>
            <div class="course">Course 3</div>
        </section>
        <section>
            <h2>最新动态</h2>
            <div class="news">News 1</div>
            <div class="news">News 2</div>
            <div class="news">News 3</div>
        </section>
    </main>
    <footer>
        &copy; 2023 vSchoolTrend
    </footer>
    <script src="script.js"></script>

    /* Reset some default styles */
body, h1, h2, p {
    margin: 0;
    padding: 0;
}

/* Basic styling for the header and navigation */
header {
    background-color: #007bff;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}

nav ul {
    list-style-type: none;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

/* Basic styling for the main content */
main {
    padding: 20px;
}

.course, .news {
    border: 1px solid #ddd;
    margin: 10px;
    padding: 10px;
}

/* Basic styling for the footer */
footer {
    background-color: #007bff;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}

</body>
</html>
