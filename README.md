# qa_guru_10_20

1. Скачала Gradle 4.2.1 - https://gradle.org/next-steps/?version=4.2.1&format=bin
2. В проекте указала все что было вроде в https://daggerok.github.io/soapui-runner/
3. Собрала, предварительно в Idea изменила место откуда брать гредл и джаву
![image](https://user-images.githubusercontent.com/15326661/160134066-c0bf2f97-84b0-4cf4-9745-2acc6fa77fba.png)
4. Далее запускаю testrunner, в котором указан .xml файл из SoapUI
<code>
  testrunner {
    projectFile = 'qa-guru-soap-10-20-soapui-project.xml'
    outputFolder = 'build/soapui/'
}
  </code>
  
 Результат работы раннера, 6 тестов было у меня в xml вроде как успешно прошло.
  ![image](https://user-images.githubusercontent.com/15326661/160134416-e8bfea80-63d1-4444-94de-e94ab1648e75.png)
  
  
С мавеном не особо легче, так как указано что Maven 2.X(https://www.soapui.org/docs/test-automation/maven/maven-2-x/) у меня стоит 3.8, его тоже придется занижать перед запуском(пробовать уже не стала).
