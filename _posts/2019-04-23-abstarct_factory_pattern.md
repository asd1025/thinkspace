---
layout: post
title: "Abstract Factory Pattern"
comments: true
description: "How to Download or Use This Theme"
keywords: "dummy content"
---
## Code Blocks

```java
public class MachineFactoryB implements MachineFactory{

	 
	@Override
	public MachineA getMachineA() {
		return new MachineA2();
	}

	@Override
	public MachineB getMacineB() {
		return new MachineB2();
	}

}

```


### Use this theme as you main site

- Download or fork the master branch of this theme repo into your GitHub account.
- Rename the repo into something like `your_username.github.io`.
- Edit `_config.yml` file to your preferences.
- Edit `about.md` file for your About page.
- Inside `_posts` folder, there are sample of blog entries. Learn from it and start yours.
- Now, visit `http://your_username.github.io` and you should see your blog running.

### Use this theme as a project page

If you want to use this theme as a project page blog, you don't need to rename the theme repo into `your_username.github.io`.

All you need to do, open `_config.yml` file, change `baseurl` to your project name which contains this theme, e.g. `baseurl: "/myproject"`.

#### Cheers!
