stage("Get source code"){
	node("master"){
		git 'https://github.com/jpenekusu/my-sample-java-project.git'
	}
}

stage("Build"){
	node("master"){
		sh "mvn compile -DskipTests"
	}
}


stage("Build"){
	node("master"){
		sh "mvn test"
	}
}
