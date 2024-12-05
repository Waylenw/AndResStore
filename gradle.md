
```
project.gradle.taskGraph.whenReady { graph ->
    project.tasks.findAll().forEach { task ->
        println("task.name:"+task.name+" "+task.project)
//        if (task.name.contains("<your-text>")) {
//            task.enabled = false
//        }
    }
}
```
