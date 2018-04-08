Jenkins
=======

1. Uruchom jenkins-a:

   ::

     make build_jenkins
     make run_jenkins

     jeśli nie działa to: strona https://github.com/wojciech11/se_teaching_vm_images/blob/master/vagrant/centos/Vagrantfile
     linia od 107 do 114 skopiować i zainstalowac na root.

2. Otwórz w przeglądarce 127.0.0.1:8080, jeśli zostaniesz poproszony o hasło dla admina, wybierz:

   ::

     cat jenkins/secrets/initialAdminPassword // WSZYSTKO NA ROOT wpisac w konsoli, wygeneruje sie hasło, wpisac je na stronie 127.0.0.1:8080

     HASŁO: 2a97df40dfaf48e9b41d9abfb8726fdf
     LOGIN: admin


3. Wybierz *Suggested plugins*. //INSTALACJA SUGEROWANYCH WTYCZEK
   Potem mkontynuuj jako administrator!!


Related
-------

- https://github.com/sheehan/job-dsl-gradle-example

4. W jankinsie:
  - klik nowy projekt,
  - wpisz nazwę projektu,
  - wybierz organization,
  - OWNER - nazwa uzytkownika z githuba
  - klik Add wybierz Jankins
  - wpisz uzytkownika i hasło z githuba (wymarz to co jest) bez ID i description
  - klik Add
  - klik save

5. Zbudowało się
  - klik na status
  - klik na projekt
  - klik na master
