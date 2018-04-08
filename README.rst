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

3. Wybierz *Suggested plugins*.


Related
-------

- https://github.com/sheehan/job-dsl-gradle-example
