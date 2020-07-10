# echo-version
simple echo-python


## make docker image
  ```
  $ docker image build -t echo:python .
  ```

## run docker container
  ```
  $ docker container rum -it --rm -p 8080:8080 --name echo echo:python
  ```
