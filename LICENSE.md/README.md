# rxjs-cache
使用rxjs进行cache缓存

一、首先导入 Observable
import { Observable } from "rxjs/Observable"

二、可以定义一个变量作为缓存的容器。

三、用rxjs语法糖Observable.of储存
return Observable.of(AppService.Data).delay(100);

delay(100) 延迟是为了 同步数据排列问题
