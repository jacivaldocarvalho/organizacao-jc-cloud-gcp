# Organização JC Cloud Solutions
---
## Utilizando o cloud shell

---

### Iniciando o cloud shell e o open editor

<p align="center">
 <img src="Abrindo-cloudshell-openeditor.gif?raw=true" alt="cloudshell openeditor" width="80%" height="50%" />
</p>

### Clonando o repositório do GCP 

```shell
git clone https://github.com/GoogleCloudPlatform/java-docs-samples.git
```

<p align="center">
 <img src="baixando-repositorio-gcp.gif?raw=true" alt="repositorio gcp" width="80%" height="50%" />
</p>

### Realizando o build do projeto exemplo quarkus-helloworld

Acessando a pasta quarkus-helloworld e realizando o build.

```shell
cd java-docs-samples/appengine-java11/quarkus-helloworld
mvn clean install 

```

<p align="center">
 <img src="build-quarkus-helloworld.gif?raw=true" alt="build quarkus" width="80%" height="50%" />
</p>

### Rodando o projeto quarkus helloworld

``` shell
cd target/
java -jar quarkus-helloworld-1.0-SNAPSHOT-runner.jar
```

<p align="center">
 <img src="run-quarkus-helloworld.gif?raw=true" alt="Run quarkus" width="80%" height="50%" />
</p>


### Web  preview do projeto quarkus helloworld


<p align="center">
 <img src="web-preview-quarkus.gif?raw=true" alt="Run quarkus" width="80%" height="50%" />
</p>


