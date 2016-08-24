node('node') {


    currentBuild.result = "SUCCESS"

    try {
	   stage 'Checkout'
		    checkout scm

       stage 'Build'
            echo 'Do something'
            sh './dosomething.sh'

        }


    catch (err) {

        currentBuild.result = "FAILURE"
        echo ${err}
        throw err
    }

}
