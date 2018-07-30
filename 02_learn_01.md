- redis设置密码  
  可以在redis环境下设置密码，  
  >127.0.0.1:6379> config set requirepass \<password>  
  >OK  
  >127.0.0.1:6379> config get requirepass  
  >(error) NOAUTH Authentication required.  
  >127.0.0.1:6379> auth \<password>  
  >OK  
  >127.0.0.1:6379> set key1 shaw_wg  
  >OK  
  >127.0.0.1:6379> get key1  
  >"shaw_wg"  
- 远程访问
  暂无
- 基础操作
  增/改  
  >127.0.0.1:6379> set \<key> \<value>  
  删  
  >127.0.0.1:6379> del \<key>  
  查  
  >127.0.0.1:6379> get \<key>  
  
