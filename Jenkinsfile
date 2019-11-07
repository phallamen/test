pipeline{
    agent any
    
    parameters{
        string(defaultValue: 'test', description: 'Delivery name', name: 'DELIVERY')
    }
    stages{
        stage("work"){
            steps{
                echo '${params.DELIVERY}'
            }
            
        }
    }
    
}
