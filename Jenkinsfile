node {
 stage 'Checkout'
 checkout scm

 stage 'Build'
 sh 'g++ --std=c++11 hello.cpp'

 stage 'Run'
 sh './a.out'
}
