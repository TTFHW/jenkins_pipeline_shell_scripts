node('node') {


    currentBuild.result = "SUCCESS"

    try {
   echo 'Hello World 1'

        }


    catch (err) {

        currentBuild.result = "FAILURE"
        echo ${err}
        throw err
    }

}
