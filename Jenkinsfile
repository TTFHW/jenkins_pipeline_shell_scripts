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

            mail body: "project build error: ${err}" ,
            from: 'xxxx@yyyy.com',
            replyTo: 'yyyy@yyyy.com',
            subject: 'project build failed',
            to: 'zzzz@yyyyy.com'

        throw err
    }

}
Contact GitHub API Training Shop Blog About
