node {
	def hayvan = load('/hayvan/v1.groovy')
	hayvan.run({ project, branch, repository ->
		// Run any additional checks or tests
		hayvan.autodeploy(project, branch, repository)
	})
}
