# Jarkom-Modul-4-IUP1-2021


| Subnet  | Alias | Jumlah IP | Netmask |
| ------------- | ------------- | ------------- | ------------- |
| A1  | jipangu - pucci  | 101 | /25 |
| A2  | courtyard - calmbelt - pucci  | 2021 | /21 |
| A3  | pucci - water7 | 2 | /30 |
| A4  | cipher - water7  | 701 | /22 |
| A5  | blueno - foosha  | 1001 | /22 |
| A6  | water7 - foosha | 2 | /30 |
| A7  | foosha - guanhao  | 2 | /30 |
| A8  | jabra - guanhao  | 521 | /22 |
| A9  | guanhao - alabasta - maingate  | 502 | /23 |
| A10  | alabasta - jorge  | 13 | /28 |
| A11  | guanhao - oimo  | 2 | /30 |
| A12  | enieslobby - seastone - oimo  | 252 | /24 |
| A13  | seastone - elena  | 721 | /22 |
| Total  | -  | 5841 | /19 |

![Untitled (3)](https://user-images.githubusercontent.com/61174498/142999196-438bb788-caf6-4179-bab5-a7a2dc1de59f.png)

![Untitled (2)](https://user-images.githubusercontent.com/61174498/142999208-15716177-3ac1-4f7d-b9b9-2caec471dc9b.png)


# A.) VLSM (Variable Length Subnet Masking)

## a.) Subnetting

### a1.) Config Router


#### 1. FOOSHA

##### FA 0/0
```

```

##### FA 0/1
```

```

##### FA 1/1
```

```

##### FA 0/3/0
```

```

##### FA 1/0
```

```


#### 2. WATER7

##### FA 0/0
```

```

##### FA 0/1
```

```

##### FA 1/0
```

```


#### 3. PUCCI

##### FA 0/0
```

```

##### FA 0/1
```

```

##### FA 1/0
```

```


#### 4. GUANHAO

##### FA 0/0
```

```

##### FA 0/1
```

```

##### FA 1/0
```

```

##### FA 1/1
```

```


#### 5. ALABASTA

##### FA 0/0
```

```

##### FA 0/1
```

```


#### 6. OIMO

##### FA 0/0
```

```

##### FA 0/1
```

```

##### FA 1/0
```

```


#### 7. SEASTONE

##### FA 0/0
```

```

##### FA 0/1
```

```


### a2.) Config PC & Server

#### 1. BLUENO
```

```

#### 2. CIPHER
```

```


#### 3. JIPANGU
```

```


#### 4. COURTYARD
```

```


#### 5. CALMBELT
```

```

#### 6. JABRA
```

```

#### 7. MAINGATE
```

```

#### 8. JORGE
```

```

#### 9. FUKUROU
```

```

#### 10. ENIESLOBBY
```

```

#### 11. ELENA
```

```

#### 12. DORIKI
```

```


## Static Routing

### 1. FOOSHA
```
BLUENO
10.38.12.0 
255.255.252.0
10.38.12.2

Cipher
10.38.8.0
255.255.252.0
10.38.27.150


JIPANGU
10.38.27.0
255.255.255.128
10.38.27.150


COURTYARD & CALMBELT
10.38.0.0
255.255.248.0
10.38.27.150

Doriki
10.38.27.160
255.255.255.252
10.38.27.162

Jabra
10.38.16.0
255.255.252.0
10.38.27.154

Maingate
10.38.24.0
255.255.254.0
10.38.27.154

Jorge
10.38.27.128
255.255.255.240
10.38.27.154

EniesLobby
10.38.26.0
255.255.255.0
10.38.27.154

Elena
10.38.20.0
255.255.252.0
10.38.27.154

Fukurou
10.38.27.164
255.255.255.252
10.38.27.154

```

### 2. FOOSHA
```

```

### 3. FOOSHA
```

```

### 4. FOOSHA
```

```

### 5. FOOSHA
```

```

### 6. FOOSHA
```

```

### 7. FOOSHA
```

```



# B.) CIDR (Classless Inter Domain Routing)
