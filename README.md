## VSCode Snippets For Web Developers

 (User Snippet)


```
"div": {
		"prefix": "div",
		"body": [
		  "<div className=''></div>"
		],
		"description": "Basic div element with className"
	  },

```





```
<div className=''></div>
```


	  "compt": {
		"prefix": "cons",
		"body": [
		  "const ${1:${TM_FILENAME_BASE/(.)(.*)/${1:/capitalize}${2}/}} = () => {",
		  "  return (",
		  "    <div className=''>${1:${TM_FILENAME_BASE/(.)(.*)/${1:/capitalize}${2}/}}</div>",
		  "  )",
		  "}",
		  "",
		  "export default ${1:${TM_FILENAME_BASE/(.)(.*)/${1:/capitalize}${2}/}}"
		],
		"description": "Create a component with tailwind classname"
	  }

```
const Page = () => {
  return (
    <div className=''>Page</div>
  )
}

export default Page

```
