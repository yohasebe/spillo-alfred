# Spillo for Alfred

An Alfred workflow that lets you search your bookmarks in [Spillo](http://bananafishsoftware.com/products/spillo).

You can download the latest version of the workflow from [here](https://github.com/ddeville/spillo-alfred/releases/latest) or from [Packal](http://www.packal.org/workflow/spillo).

## Usage

You can invoke the workflow by using the `spl` command in Alfred.

You can search in two different ways:

### Global

Just type some text after the `spl` command and Spillo will search against the title, URL and description of your bookmarks. Simple.

```
spl objective-c atomics
```

### Specific

If you want more control, you can specify various parameters for your search. The following parameters are supported:

- `-n`: The name of the bookmark
- `-u`: The URL of the bookmark
- `-d`: The description of the bookmark
- `-t`: The tags of the bookmark

You can use multiple parameters at the same time.

```
spl -n nullability -t objc swift
```

## Actions

When you have found the bookmark you are looking for, you can open it in your default browser. Just hit Return or click on the bookmark in the Alfred search results.

Alternatively, you can open the bookmark in the background by holding the option key.

You can also open the bookmark in Spillo by holding the command key.

## Notes

Note that Spillo need to be installed and authenticated on your machine for the workflow to work.
