### Programming Skills

- [ ] GPU basics
  - [x] [Introduction to concurrent programming with GPU](https://www.coursera.org/learn/introduction-to-concurrent-programming/home/week/1)\
    💡 [Lock, Actors, ..](https://adit.io/posts/2013-05-15-Locks,-Actors,-And-STM-In-Pictures.html)
  - [x] [Introduction to Parallel Programming with CUDA](https://www.coursera.org/learn/introduction-to-parallel-programming-with-cuda/home/info)\
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
  - [ ] [CUDA at Scale for the Enterprise](https://www.coursera.org/learn/cuda-at-scale-for-the-enterprise)
    - [x]  [final project](https://github.com/mer1in/jhGPUPSc3w5)

- [ ] [nand2tetris](https://www.nand2tetris.org/)
  - [x] part I HW
  - [ ] part II SW

### Productivity

  - [ ] sync config
  - [ ] extend pods fzf browser:
    - [ ] edit deployments
    - [x] call describe
  - [x] vim: try [syntasic](https://github.com/vim-syntastic/syntastic)
  - [x] [run application with shortcut on mac](https://www.computerhope.com/issues/ch002051.htm)
  - [x] file history browser w/fzf
  - [x] ssh in tmux popup

### Devops Skills

- [ ] jenkins cert \
  📚 [Certification for Jenkins Engineers](https://www.cloudbees.com/jenkins/certification) \
    💡 https://github.com/jenkinsci/configuration-as-code-plugin/tree/master/demos \
    💡 https://cloud.google.com/architecture/jenkins-on-kubernetes-engine \
    💡 https://www.jenkins.io/projects/jcasc/ \
    💡 `kubectl exec --namespace default -it svc/myjenkins -c jenkins -- /bin/cat /run/secrets/additional/chart-admin-password && echo`
- [ ] ansible cert
- [ ] k8s cert \
  📚 [tutorials w/sandbox](https://kubernetes.io/docs/tutorials/)
  📚 [killer](https://killer.sh/)
- [ ] terraform cert \
  📚 [tutorials](https://developer.hashicorp.com/terraform/tutorials)
 
### Fun

- [ ] tic-tac-toe 2.0 in browser
- [ ] translatemix
