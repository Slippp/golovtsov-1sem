
    <title>Отчет по лабораторным работам</title>
</head>
<body>
    <nav class="navbar navbar-light bg-light">
        <a class="navbar-brand" href="">
            Отчет по лабораторным работам
        </a>
        <a href="https://vk.com/id22872407" class="btn btn-primary btn-light btn-lg ml-auto" role="button" aria-pressed="true">
            <blockquote class="blockquote mb-0">
                <footer class="blockquote-footer">Майорко Денис. ИДМ-19-04</footer>
            </blockquote>
        </a>
    </nav>
    <div class="container-fluid d-flex mt-2">
        <div class="nav flex-column nav-pills col-2" id="v-pills-tab" role="tablist" aria-orientation="vertical">
            <a class="nav-link active" id="v-pills-lab1-tab" data-toggle="pill" href="#v-pills-lab1" role="tab" aria-controls="v-pills-lab1" aria-selected="true">Лабораторная работа №1</a>
            <a class="nav-link" id="v-pills-lab2-tab" data-toggle="pill" href="#v-pills-lab2" role="tab" aria-controls="v-pills-lab2" aria-selected="false">Лабораторная работа №2</a>
            <a class="nav-link" id="v-pills-lab3-tab" data-toggle="pill" href="#v-pills-lab3" role="tab" aria-controls="v-pills-lab3" aria-selected="false">Лабораторная работа №3</a>
            <a class="nav-link" id="v-pills-project-tab" data-toggle="pill" href="#v-pills-project" role="tab" aria-controls="v-pills-project" aria-selected="false">Командный проект</a>
        </div>
        <div class="tab-content col-10" id="v-pills-tabContent">
            <div class="tab-pane fade show active container-fluid" id="v-pills-lab1" role="tabpanel" aria-labelledby="v-pills-lab1-tab">
                <h4>Ход лабораторной:</h4>
                <ul>
                    <li>Был создан личный репозиторий на GitHub, доступный по следующей ссылке: <a href="https://github.com/DenisMayorko/DenisMayorko.github.io">ссылка</a></li>
                    <li>Был создан командный репозиторий на GitHub, доступный по следующей ссылке: <a href="https://github.com/mpoles/mpoles.github.io/tree/master/inet-2019">ссылка</a></li>
                    <li>В целях использования возможности эксплуатции GitHub в качестве хостингового сервиса в репозитории были загружены личная страница отчёта по лабораторным работам и страница командного проекта</li>
                </ul>
                <img src="content/lab1.jpg" class="rounded d-block">
            </div>
            <div class="tab-pane fade" id="v-pills-lab2" role="tabpanel" aria-labelledby="v-pills-lab2-tab">
                <h4>Ход лабораторной:</h4>
                <ul>
                    <li>Было создано веб-приложение с использованием таких инструментов, как JavaScript и jQuery.</li>
                    <li>Веб-приложение было опубликовано в GitHub и сейчас доступно по ссылке: <a href="https://mpoles.github.io/inet-2019/">ссылка</a></li>
                </ul>
                <p>Созданное веб-приложение представляет собой веб-страницу с презентацией командного проекта</p>
                <img src="content/lab2.gif" class="rounded d-block">
                <p>Скрипты используются для навигации по сайту</p>
            </div>
            <div class="tab-pane fade" id="v-pills-lab3" role="tabpanel" aria-labelledby="v-pills-lab3-tab">
                <table id="table"
                       data-pagination="true"
                       data-pagination-v-align="both"
                       data-show-fullscreen="true"
                       class="table table-dark table-striped table-hover">
                    <thead>
                        <tr>
                            <th>Параметр</th>
                            <th>LAN A</th>
                            <th>LAN B</th>
                            <th>LAN C</th>
                        </tr>
                    </thead>

                    <tbody>
                        <tr>
                            <td>Количество узлов</td>
                            <td>61</td>
                            <td>29</td>
                            <td>289</td>
                        </tr>
                        <tr>
                            <td>Ближайшая сверху степень двойки</td>
                            <td>6</td>
                            <td>5</td>
                            <td>9</td>
                        </tr>
                        <tr>
                            <td>Маска (префиксная)</td>
                            <td>26</td>
                            <td>27</td>
                            <td>23</td>
                        </tr>
                        <tr>
                            <td>Маска (десятичная)</td>
                            <td>255.255.255.224</td>
                            <td>255.255.255.192</td>
                            <td>255.255.254.0</td>
                        </tr>
                        <tr>
                            <td>Адрес</td>
                            <td>192.168.13.0</td>
                            <td>172.16.13.0</td>
                            <td>10.10.13.0</td>
                        </tr>
                        <tr>
                            <td>SUBNET</td>
                            <td>192.168.13.0</td>
                            <td>172.16.13.0</td>
                            <td>10.10.13.0</td>
                        </tr>
                        <tr>
                            <td>HOSTMIN</td>
                            <td>192.168.13.1</td>
                            <td>172.16.13.1</td>
                            <td>10.10.12.1</td>
                        </tr>
                        <tr>
                            <td>HOSTMAX</td>
                            <td>192.168.13.30</td>
                            <td>172.16.13.62</td>
                            <td>10.10.13.254</td>
                        </tr>
                        <tr>
                            <td>BROADCAST</td>
                            <td>192.168.13.31</td>
                            <td>172.16.13.63</td>
                            <td>10.10.13.255</td>
                        </tr>
                    </tbody>
                </table>
                <img src="content/lab3.jpg" class="rounded d-block mx-auto">
            </div>
            <div class="tab-pane fade" id="v-pills-project" role="tabpanel" aria-labelledby="v-pills-project-tab">
                <div class="jumbotron">
                    <div class="row">
                        <div class="col-6">
                            <h1 class="display-4">Athena.Log.Viewer</h1>
                            <p class="lead">Командный проект "Рататуй"</p>
                        </div>
                        <img src="content/project.jpg" class="img-fluid mr-3 rounded d-block ml-auto col-2">
                    </div>

                    <hr class="my-4">
                    <p class="lead">
                        <a class="btn btn-primary btn-lg" href="https://mpoles.github.io/inet-2019/" role="button">Узнать больше</a>
                    </p>
                </div>

            </div>
        </div>
    </div>
</body>
</html>
