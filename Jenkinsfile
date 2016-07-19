 //Print the paylod and Hello World
import hudson.model.*
echo("Hello from Pipeline")
echo ("test")
echo ("Added new line")
currentBuild.description = "CI Build job for Pipeline_Demo/Master branch"
properties ( [[$class: 'ParametersDefinitionProperty', parameterDefinitions: [[$class: 'TextParameterDefinition', defaultValue: 'CI Build Job for Pipeline_Demo\\master branch', description: '', name: 'Description']]]] )
