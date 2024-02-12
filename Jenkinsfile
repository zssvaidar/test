
node {


    currentBuild.result = "SUCCESS"

    try {

       stage('Checkout'){

            echo 'Checkout'
       }

      stage('Test'){


            echo 'Test'
      }

       stage('Build Docker'){

            echo 'dockerBuild.sh'
       }

       stage('Deploy'){

         echo 'Push to Repo'

         echo 'ssh to web server and tell it to pull new image'

       }

       stage('Cleanup'){

         echo 'prune and cleanup'
       }



    }
    catch (err) {


        throw err
    }

}