+++
date = "2016-07-20T03:30:00+00:00"
description = ""
draft = true
tags = []
title = "How can I control which GitHub repositories Forestry has access to?"

+++
Many users have restrictions on what repositories they can expose to forestry. While the GitHub API does not allow fine grain control over which repositories Forestry gets access to, there is a solution. The solution involves creating a "machine user" (really just a new GitHub account) and give it access to only the repositories you wish to expose to Forestry.

You can get more information on how to do this by reading [Githubs official guide](https://developer.github.com/guides/managing-deploy-keys/#machine-users) on how to do this.

Once you've completed this, simply use this machine account with Forestry.