
Based on article from http://coffeecoders.de/2011/09/using-github-as-a-personal-maven-repository/



=New file can be delpyoed like this:

mvn deploy:deploy-file -DgroupId=de.greenrobot -DartifactId=event -Dversion=2.0.1 -Dpackaging=jar -Dfile="EventBus-2.0.1.jar" -Durl=file:releases