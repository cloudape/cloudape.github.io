
This is a training kit containing the essential skills for **Cloud Native** professionals. The content covers the following job roles:
- Cloud Associates
- Cloud Engineer
- Devops Engineer
- Cloud Architect

The content for each role contains a practical hands-on courses consists of micro-learning units. Each unit is designed with clear learning objectives so that the learner can immediately apply the skills learned to the job.

## Cloud Associates
The Cloud associates need to be familiar with interacting with source repository, familiar with Linux, understand web technologies and be familiar with containers as a foundation. On top of that, the associates need to understand the fundamentals of Cybersecurity, understand cloud-native approaches, able to develop Terraform Infra-As-Code and understand the concepts of Agile Practices.

### CA0101: Working with Git
Git is a version control software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. 

|Unit|Topic|
|----|-----|
|01|[Getting Started with Git](/CA0101/U01)|
|02|[Git Commands](/CA0101/U02)|
|03|[Branching and Merging](/CA0101/U03)|
|04|[Git Housekeeping](/CA0101/U04)|
|05|[GitOps](/CA0101/U05)|


### CA0102: Linux Basics

### CA0103: Web Fundamentals

### CA0104: Working with Containers

### CA0105: Cybersecurity Fundamentals

### CA0106: Cloud Native Foundation

### CA0107: Mastering Terraform IaC

### CA0108: Agile Practices


## Cloud Engineer (PL2)

### CB0101: Computer Networks

### CB0102: Advance Linux

### CB0103: Network Security

### CB0104: Windows Basic 

### CB0105: Windows Server

### CB0106: Cloud Databases

### CB0107: Cloud Security

### CB0108: Cloud Infrastructure Solutions

## Devops Engineer (PL2)

### CC0101: Mastering Python

### CC0102: Frontend Development

### CC0103: Backend Development

### CC0104: Web Vulnerabilities


## Cloud Architect

### CA0107: Product Management 


# Contribution
The content are created using (Google CodeLab)[https://github.com/googlecodelabs/tools]. Follow the guide in the link to create Google doc content.

## Install Claat on Your Mac
To generate static web pages from the Google Doc, you will need to first install `claat`.

1. Install (Go)[https://go.dev/doc/install]

2. Install Claat
```
$ go install github.com/googlecodelabs/tools/claat@latest

```

3. The claat binary should be found in the Go bin directory within your home directory:
   
```
$ find ~/go -name claat
/Users/xxxx/go/bin/claat
/Users/xxxx/go/pkg/mod/cache/download/github.com/googlecodelabs/tools/claat
/Users/xxxx/go/pkg/mod/github.com/googlecodelabs/tools@v2.2.5+incompatible/site/app/js/claat
```

## Generate Static Web Page
To generate the static web page for the [example doc](https://docs.google.com/document/d/1rpHleSSeY-MJZ8JvncvYA8CFqlnlcrW8-a4uEaqizPY/), run `claat export` for the document ID: 
```
$ ~/go/bin/claat export 1rpHleSSeY-MJZ8JvncvYA8CFqlnlcrW8-a4uEaqizPY 
ok      your-first-pwapp

$ ls your-first-pwapp/
codelab.json	img		index.html
```



