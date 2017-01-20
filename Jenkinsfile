#!groovy
node {
   // Mark the code checkout 'stage'....
   stage 'Checkout'

   // Checkout code from repository
   checkout scm

   // Get the maven tool.
   // ** NOTE: This 'M3' maven tool must be configured
   // **       in the global configuration.
   echo 'I am a tool'

   // Mark the code build 'stage'....
   stage 'Build'
   // Run the maven build
   echo 'I am building...'
}
