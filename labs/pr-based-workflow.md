# Pull Request based workflow

The defacto-standard workflow now-adays is the Pull Request workflow (also known as the [GitHub flow](https://guides.github.com/introduction/flow/))

There are some functions that you can use in the declarative pipeline.

```
        stage('Change request') {
          when { changeRequest() }
          steps {
            sh 'echo "this is a change request"'
          }
        }
```