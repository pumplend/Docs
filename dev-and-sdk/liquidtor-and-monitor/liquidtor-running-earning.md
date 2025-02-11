---
description: Earn SOL by running liquidtor
---

# Liquidtor Running Earning

Every 3th part liquditor will earn `0.5%` position size as liqudtion profite .&#x20;

Details can be found in [our repo](https://github.com/pumplend/pumplend-liquidator) .

## How to run my local liquidtor ?&#x20;

It's not difficult .&#x20;

### Step 1 :  you will have to prepare your local ENV&#x20;

Install&#x20;

* Mongodb
* Node.js

### Step 2 : pull and install

pull the repo to local&#x20;

```
git clone https://github.com/pumplend/pumplend-liquidator
```

now install

```
npm install
npm install -g pm2
```

remeber to reconfig your local env by&#x20;

```
cp .env.exmapl .env
```

star the monitor first&#x20;

```
pm2 start monitor.js
```

now you can run the liquditor now !

```
pm2 start executor.js
```



### Step 3 : keep the executor wallet balance enough . and earn .

You will have to keep executor have enought balance as gas fee .

Now you can earn from the liqudtion .&#x20;
