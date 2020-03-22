# react-input

## 请实现支持如下代码的InputNumber组件，可以受控和非受控。
```javascript
function App(){
    const [value,setValue] = useState('aaa')
    return (
        <div>
        <InputNumber value={value} onChange={e=>{}}/>
        <InputNumber defaultValue={value} onChange={e=>{}}/>
        </div>
    )
}
```

