# 绑定爱发电

要继续在 **GiveawayBot** 中绑定您的 **爱发电** 账户  

请**私信**发送给 **GiveawayBot** 以下内容
<code id="bind">
gbind 绑定码
</code>
<script>
````
const searchParams = new URLSearchParams(location.search);
const query = searchParams.get("code");
document.getElementById("bind").innerHTML=query ? 'gbind '+query : '无效请求'
````
</script>
