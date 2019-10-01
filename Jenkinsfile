pipeline {
  agent any
  stages {
    stage('Stagging') {
      steps {
        sh '''$!/bin/bash
echo "message"'''
      }
    }
    stage('Dev') {
      steps {
        sh '''#!/bin/bash
echo "dev"'''
      }
    }
    stage('test') {
      steps {
        sh '''#!/bin/bash
echo "test"'''
      }
    }
    stage('production') {
      steps {
        sh '''#!/bin/bash
echo "production"'''
      }
    }
  }
}