# data-cleaning
```import pandas as pd
df=pd.read_csv("/content/SAMPLEIDS.csv")
df
```
<img width="626" alt="image" src="https://github.com/Jeevapriya14/data-cleaning/assets/121003043/97722de6-05b1-420c-a955-8b8129d28121">

```
df.head(10)
```
<img width="434" alt="image" src="https://github.com/Jeevapriya14/data-cleaning/assets/121003043/68d55a52-2f11-45b7-89be-269204208ff5">

```
df.tail(10)
```
<img width="462" alt="image" src="https://github.com/Jeevapriya14/data-cleaning/assets/121003043/c23285b0-fc42-45f1-904c-d8f8ae79bfb1">

```
df.info
```

<img width="392" alt="image" src="https://github.com/Jeevapriya14/data-cleaning/assets/121003043/0b844bad-ee65-4667-b765-6bf6d83a1004">

```
df.describe()
```

<img width="528" alt="image" src="https://github.com/Jeevapriya14/data-cleaning/assets/121003043/ce2cfb39-b838-498e-a8ba-297412756584">

```
df.shape
```

<img width="74" alt="image" src="https://github.com/Jeevapriya14/data-cleaning/assets/121003043/60f426ff-96ad-457d-ad55-fbdbcc091db8">

```
df.nunique()
```

<img width="235" alt="image" src="https://github.com/Jeevapriya14/data-cleaning/assets/121003043/aae0bc9b-46c3-4ed7-bc24-c9bff6e5d28b">

```
df['GENDER'].value_counts()
```

<img width="156" alt="image" src="https://github.com/Jeevapriya14/data-cleaning/assets/121003043/523afb48-2acf-4fca-b503-c1b35947a2a1">

```
mn=df.TOTAL.mean()
```

<img width="174" alt="image" src="https://github.com/Jeevapriya14/data-cleaning/assets/121003043/832735c8-a21b-4fe6-8ed4-b932ff886038">

```
df.TOTAL.fillna(mn,inplace=True)
df.M4.fillna(mn,inplace=True)
df.isnull()
df
```

<img width="538" alt="image" src="https://github.com/Jeevapriya14/data-cleaning/assets/121003043/f85735cd-2c1c-4f91-838a-25db75ed203e">

```
df['cd']=pd.to_datetime(df['DOB'])
df['cd']
```

<img width="175" alt="image" src="https://github.com/Jeevapriya14/data-cleaning/assets/121003043/af175242-8154-4c4d-8c95-231078b71a91">

```
df
```

<img width="675" alt="image" src="https://github.com/Jeevapriya14/data-cleaning/assets/121003043/16e9cd23-469e-4552-be60-2b0bf539fe4d">



