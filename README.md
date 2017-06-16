# lagradlejavadev
## 5.Gradle Tasks
```
gradle -q projects
```

### 3 Create new Gradle tasks
```
task showDate{
  doLast{
    println 'Date: ' + new Date()
  }
}
```
