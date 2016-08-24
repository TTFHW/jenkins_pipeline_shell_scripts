node('node') {


    currentBuild.result = "SUCCESS"

    try {

       stage 'Do Something'



            echo 'Do something'
            sh './dosomething.sh'

       stage 'Do Something Else'

            echo 'Do something else'
            sh './dosomethingelse.sh'

        }


    catch (err) {

        currentBuild.result = "FAILURE"
        echo ${err}
        throw err
    }

}
