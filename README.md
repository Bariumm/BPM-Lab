# BPM-Lab Group 14

## Products

```
<product>
  <id>44162d90-9315-4acc-980e-cf975c6b9397</id>
  <name>PICEA MARIANA RESIN</name>
  <producer>Zooxo</producer>
  <weight>11A</weight> 
  <price>77.92</price>
</product> 
```

```
<product>
  <id>66968a93-4ec6-4fa2-bf2d-3b0f59e56738</id>
  <name>Ursodiol</name>
  <producer>Mudo</producer>
  <weight>4.5</weight>
  <price>17.18</price>
</product>
```

```
<product>
  <id>479e8b20-3697-4609-9ed6-bde2a4b22e41</id>
  <name>Potassium Chloride</name>
  <producer>Zoomcast</producer>
  <weight>12.1</weight>
  <price>94.05</price>
</product>
```

```
<product>
  <id>3bae3778-8577-4b36-9572-a0b020931ba5</id>
  <name>Menthol, Methyl Salicylate</name>
  <producer>Yozio</producer>
  <weight>10.8</weight>
  <price>32.28</price>
</product>
```

```
<product>
  <id>1d1d5dcf-de65-44d7-bda3-7a25ee222bde</id>
  <name>Robitussin Sugar Free Cough</name>
  <producer>0yondu</producer>
  <weight>3.5</weight>
  <price>12.14</price>
</product>
```


## Example

### Normal

```
<tns:FlowSOGProcessRequest xmlns:tns="http://iaas.uni-stuttgart.de/labs/FlowSOG" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
  <tns:products>
    <tns:product>
      <tns:productId>1d1d5dcf-de65-44d7-bda3-7a25ee222bde</tns:productId>
      <tns:numberOfItems>10</tns:numberOfItems>
    </tns:product>
  </tns:products>
  <tns:customerID>1111</tns:customerID>
  <tns:shippingAddress>Stuttgart</tns:shippingAddress>
  <tns:paymentDetails>
    <tns:bankName>BW Bank</tns:bankName>
    <tns:bankAddress>Stuttgart</tns:bankAddress>
    <tns:accountNumber>2222</tns:accountNumber>
    <tns:accountHolderName>Max</tns:accountHolderName>
  </tns:paymentDetails>
  <tns:status>tns:status</tns:status>
</tns:FlowSOGProcessRequest>
```

### Asynchron

```
 <tns:WebShopAsyncRequest xmlns:tns="http://iaas.uni-stuttgart.de/labs/FlowSOG" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"> 
  <tns:products> 
    <tns:product> 
      <tns:productID>1d1d5dcf-de65-44d7-bda3-7a25ee222bde</tns:productID> 
      <tns:numberOfItems>10</tns:numberOfItems> 
    </tns:product> 
  </tns:products> 
  <tns:customerID>1111</tns:customerID> 
  <tns:shippingAddress>Stuttgart</tns:shippingAddress> 
  <tns:paymentDetails> 
    <tns:bankName>BW Bank</tns:bankName> 
    <tns:bankAddress>Stuttgart</tns:bankAddress> 
    <tns:accountNumber>2222</tns:accountNumber> 
    <tns:accountHolderNameMax</tns:accountHolderName> 
  </tns:paymentDetails> 
  <tns:status>tns:status</tns:status> 
  <tns:callbackUrl>http://localhost:32890/ode/processes/WebShopAsyncCallback</tns:callbackUrl> 
</tns:WebShopAsyncRequest>
```
