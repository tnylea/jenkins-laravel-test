node {
   // Install dependencies
   stage 'Install dependencies'
   // Run Composer
   sh 'composer install'
   // Test stage
   stage 'Test'
   // Run the tests
   sh "vendor/bin/phpunit"
}