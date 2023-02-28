pipeline{
     // 全部的cicd流程在这里定义

     // 如果是在集群 那个机器闲着就可以执行
     agent any
     // 环境信息

     //定义流水线的加工流程
    stages{
        // 流水线的所有流程
    // 编译
        stage('compile'){
            steps {
                echo "compile"
            }
        }
        // 测试
        stage('test'){
            steps {
                echo "test"
                }
        }
        stage('package'){
             steps {
                echo "package"
                }
            }
           // 部署
        stage('deploy'){
             steps {
                echo "deploy1"
                }
            }
    }
}
