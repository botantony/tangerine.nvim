# clean.fnl
> Functions to clean stale lua files in target dirs.

**DEPENDS:**
```
output[logger]
utils[diff]
utils[env]
utils[fs]
utils[path]
```

**EXPORTS**
```fennel
:cleanvim.tbl_islist is deprecated. Run ":checkhealth vim.deprecated" for 
:return {
	:orphaned (function 1)
	:rtp      (function 2)
	:target   (function 3)
}
```

# compile.fnl
> Functions to diff compile fennel files.

**DEPENDS:**
```
fennel
output[err]
output[log]
utils[diff]
utils[env]
utils[fs]
utils[path]
```

**EXPORTS**
```fennel
:compilevim.tbl_islist is deprecated. Run ":checkhealth vim.deprecated" for 
:return {
	:all    (function 1)
	:buffer (function 2)
	:custom (function 3)
	:dir    (function 4)
	:file   (function 5)
	:rtp    (function 6)
	:string (function 7)
	:vimrc  (function 8)
}
```

# eval.fnl
> Functions for interactive fennel evaluation.

**DEPENDS:**
```
fennel
output[display]
output[error]
utils[fs]
utils[path]
```

**EXPORTS**
```fennel
:evalvim.tbl_islist is deprecated. Run ":checkhealth vim.deprecated" for 
:return {
	:buffer (function 1)
	:file   (function 2)
	:peek   (function 3)
	:string (function 4)
}
```

