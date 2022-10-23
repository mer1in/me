### Programming Skills

- [ ] GPU basics
  - [x] [Introduction to concurrent programming with GPU](https://www.coursera.org/learn/introduction-to-concurrent-programming/home/week/1)\
    💡 [Lock, Actors, ..](https://adit.io/posts/2013-05-15-Locks,-Actors,-And-STM-In-Pictures.html)
  - [ ] [Introduction to Parallel Programming with CUDA](https://www.coursera.org/learn/introduction-to-parallel-programming-with-cuda/home/info)\
    💡 [Indexing CheatSheet](https://cs.calvin.edu/courses/cs/374/CUDA/CUDA-Thread-Indexing-Cheatsheet.pdf)
    ```
    int blockId = 
        blockIdx.x +
        blockIdx.y * gridDim.x +
        blockIdx.z * gridDim.y * gridDim.x;
    int tid = blockId * (blockDim.x * blockDim.y * blockDim.z) +
        threadIdx.z * blockDim.x * blockDim.y +
        threadIdx.y * blockDim.x +
        threadIdx.x;
    ```

- [ ] nand2tetris
  - [x] part I HW
  - [ ] part II SW

### Productivity

  - [ ] sync config
  - [ ] extend pods fzf browser: edit deployments, call describe
  - [ ] vim: try [syntasic](https://github.com/vim-syntastic/syntastic)
  - [x] [run application with shortcut on mac](https://www.computerhope.com/issues/ch002051.htm)
  - [x] file history browser w/fzf
  - [x] ssh in tmux popup

### Devops Skills
- [ ] jenkins cert
  📚 [Certification for Jenkins Engineers](https://www.cloudbees.com/jenkins/certification)
- [ ] ansible cert
- [ ] k8s cert
  📚 [tutorials w/sandbox](https://kubernetes.io/docs/tutorials/)
- [ ] terraform cert
