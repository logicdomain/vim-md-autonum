# 1. Installation
```
Plug 'logicdomain/vim-md-autonum', {'do': './install.sh'}
```

# 2. How to use?
- Call in vim:
```
:Autonum
```
```
:CleanNum
```
```
:AddNum
```

# 3. How many levels?
- 5 means 1.2.3.4.5.
- Extendable: Alternate the initial_num_level to bigger range in logic-autonum file.

# 4. Sample
- Before autonum:
```
# title
## t1
### t11
## t2
```
- After autonum:
```
# 1. title
## 1.1. t1
### 1.1.1. t11
## 2.1. t2
```
