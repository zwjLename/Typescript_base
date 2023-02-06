# interface 
1、同名接口自动合并

```typescript
  interface Animal {
    name: string
  }
  interface Animal {
    age: number;
    name: string
  }
```

2、扩展操作符号extends

3、使用interface定义函数，也可以给函数定义其他额外属性
```typescript
interface Plus {
  (init: number): number;
  revoke: (init: number) => number;
}
```

# type
1、使用type不能声明相同的类型别名
2、type声明的对象类型使用“&”符号进行扩展操作