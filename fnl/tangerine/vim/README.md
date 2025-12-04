# cmds.fnl
> Defines tangerine's default vim commands.

**DEPENDS:**
```
_G.tangerine.api
```

**EXPORTS**
```fennel
:cmdsvim.tbl_islist is deprecated. Run ":checkhealth vim.deprecated" for 
:return [true]
```

# hooks.fnl
> Defines autocmd hooks as described in ENV.

**DEPENDS:**
```
_G.tangerine.api
utils[env]
```

**EXPORTS**
```fennel
:hooksvim.tbl_islist is deprecated. Run ":checkhealth vim.deprecated" for 
:return {
	:oninit (function 1)
	:onload (function 2)
	:onsave (function 3)
	:run    (function 4)
}
```

# maps.fnl
> Defines mappings for vim[cmds] as described in ENV.

**DEPENDS:**
```
utils[env]
vim[cmds]
```

**EXPORTS**
```fennel
:mapsvim.tbl_islist is deprecated. Run ":checkhealth vim.deprecated" for 
:return [true]
```

