# 1. How to use?
- Place the logic-autonum(executor) into your PATH.
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

# 2. How many levels?
- 5 means 1.2.3.4.5.
- Extendable: Alternate the initial_num_level to bigger range in logic-autonum file.

# 3. Sample
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
## 1.2. t2
```
