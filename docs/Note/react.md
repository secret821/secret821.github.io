# React å­¦ä¹ ç¬è®° ð

ç¬¬ 1 ç« . React åºç¡

## 1.1. React ç®ä»

### 1.1.1. å®ç½

\1. è±æå®ç½:https://reactjs.org/

\2. ä¸­æå®ç½: https://react.docschina.org/

1.1.2. ä»ç»æè¿°

\1. ç¨äºå¨ææå»ºç¨æ·çé¢ç JavaScript åº(åªå³æ³¨äºè§å¾)

\2. ç± Facebook å¼æº

1.1.3. React çç¹ç¹

\1. å£°æå¼ç¼ç 

\2. ç»ä»¶åç¼ç 

\3. React Native ç¼ååçåºç¨

\4. é«æï¼ä¼ç§ç Diffing ç®æ³ï¼

1.1.4. React é«æçåå 

\1. ä½¿ç¨èæ(virtual)DOM, ä¸æ»æ¯ç´æ¥æä½é¡µé¢çå® DOMã

\2. DOM Diffing ç®æ³, æå°åé¡µé¢éç»ã

## 1.2. React çåºæ¬ä½¿ç¨

### 1.2.1. ææ

### 1.2.2. ç¸å³ js åº

\1. react.jsï¼React æ ¸å¿åºã

\2. react-dom.jsï¼æä¾æä½ DOM ç react æ©å±åºã

\3. babel.min.jsï¼è§£æ JSX è¯­æ³ä»£ç è½¬ä¸º JS ä»£ç çåºã

### 1.2.3. åå»ºèæ DOM çä¸¤ç§æ¹å¼

\1. çº¯ JS æ¹å¼(ä¸è¬ä¸ç¨)

\2. JSX æ¹å¼,

### 1.2.4. èæ DOM ä¸çå® DOM

\1. React æä¾äºä¸äº API æ¥åå»ºä¸ç§ âç¹å«â çä¸è¬ js å¯¹è±¡

l **const\*\***VDOM\***\*=\*\***React\***\*.createElement('xx', {id:'xx'}, 'xx')**

l ä¸é¢åå»ºçå°±æ¯ä¸ä¸ªç®åçèæ DOM å¯¹è±¡

\2. èæ DOM å¯¹è±¡æç»é½ä¼è¢« React è½¬æ¢ä¸ºçå®ç DOM

\3. æä»¬ç¼ç æ¶åºæ¬åªéè¦æä½ react çèæ DOM ç¸å³æ°æ®, react ä¼è½¬æ¢ä¸ºçå® DOM ååèæ´æ°çã

## 1.3. React JSX

### 1.3.1. ææ

### 1.3.2. JSX

\1. å¨ç§°: JavaScript XML

\2. react å®ä¹çä¸ç§ç±»ä¼¼äº XML ç JS æ©å±è¯­æ³: JS + XML æ¬è´¨æ¯**React**.**createElement**(**component, props**, ...children\*\*)æ¹æ³çè¯­æ³ç³

\3. ä½ç¨: ç¨æ¥ç®ååå»ºèæ DOM

\1) åæ³ï¼**var\*\***ele\***\*=\*\***<h1>**\*\*\*\***Hello JSX!</h1>\*\*

\2) æ³¨æ 1ï¼å®ä¸æ¯å­ç¬¦ä¸², ä¹ä¸æ¯ HTML/XML æ ç­¾

\3) æ³¨æ 2ï¼å®æç»äº§ççå°±æ¯ä¸ä¸ª JS å¯¹è±¡

\4. æ ç­¾åä»»æ: HTML æ ç­¾æå¶å®æ ç­¾

\5. æ ç­¾å±æ§ä»»æ: HTML æ ç­¾å±æ§æå¶å®

\6. åºæ¬è¯­æ³è§å

\1) éå° <å¼å¤´çä»£ç , ä»¥æ ç­¾çè¯­æ³è§£æ: html ååæ ç­¾è½¬æ¢ä¸º html åååç´ , å¶å®æ ç­¾éè¦ç¹å«è§£æ

\2) éå°ä»¥ { å¼å¤´çä»£ç ï¼ä»¥ JS è¯­æ³è§£æ: æ ç­¾ä¸­ç js è¡¨è¾¾å¼å¿é¡»ç¨{ }åå«

\7. babel.js çä½ç¨

\1) æµè§å¨ä¸è½ç´æ¥è§£æ JSX ä»£ç , éè¦ babel è½¬è¯ä¸ºçº¯ JS çä»£ç æè½è¿è¡

\2) åªè¦ç¨äº JSXï¼é½è¦å ä¸ type="text/babel", å£°æéè¦ babel æ¥å¤ç

### 1.3.3. æ¸²æèæ DOM(åç´ )

\1. è¯­æ³: **ReactDOM\*\***.render(virtualDOM, \*\* **containerDOM\*\***)\*\*

\2. ä½ç¨: å°èæ DOM åç´ æ¸²æå°é¡µé¢ä¸­ççå®å®¹å¨ DOM ä¸­æ¾ç¤º

\3. åæ°è¯´æ

\1) åæ°ä¸: çº¯ js æ jsx åå»ºçèæ dom å¯¹è±¡

\2) åæ°äº: ç¨æ¥åå«èæ DOM åç´ ççå® dom åç´ å¯¹è±¡(ä¸è¬æ¯ä¸ä¸ª div)

#### åç´ æ¸²æ

åç´ æ¯ææ React åºç¨çæå°ç å, æ¯å¦:

const ele = <h1>hello, world</h1>

ä¸æµè§å¨ç DOM åç´ ä¸åï¼React åç´ æ¯åå»ºå¼éæå°çæ®éå¯¹è±¡ãReact DOM ä¼è´è´£æ´æ° DOM æ¥ä¸ React åç´ ä¿æä¸è´

ä¸èè¯¾ç ReactDOM.render()å¶å®å°±æ¯å¨æ¸²æ DOM èç¹

#### **æ´æ°å·²æ¸²æçåç´ **

React åç´ æ¯**ä¸å¯åå¯¹è±¡**, ä¸æ¦è¢«åå»º, æ å¦¨æ´æ¹å®çå­åç´ æèå±æ§

è®¡æ¶å¨çä¾å­

``` html
function tick() {   const element = (     <div>       <h1>Hello, world!</h1>       <h2>{new Date().toLocaleTimeString()}.</h2>     </div>   );   ReactDOM.render(element, document.querySelector('#root')); } setInterval(tick, 1000);
```

å¤§å¤æ°æåµä¸, React åºç¨åªä¼è°ç¨ä¸æ¬¡ ReactDOM.render()

**React åªéè¦æ´æ°å®éè¦æ´æ°çé¨å**

React DOM ä¼å°åç´ åå®çå­åç´ ä¸å®ä»¬ä¹åçç¶æè¿è¡æ¯è¾, å¹¶åªä¼è¿è¡å¿è¦çæ´æ°æ¥ä½¿ DOM è¾¾å°é¢æçç¶æ

#### å¾ªç¯ç»å®åç´ 

å½æ°æ®ä»åç«¯è¯·æ±åæ¥ä¹å, å¨ React ä¸­, ä¸è¬é½éè¦å¾ªç¯ç»å®åç´ 

##### map ç»å®

å¨ React ä¸­, å¾ªç¯ç»å®åç´ é½æ¯ä½¿ç¨ map æ¹æ³, ä¸è½ä½¿ç¨ forEach æ¯å ä¸º forEach æ²¡æè¿åå¼

```
let ul = (<ul>   { arr.map((item, index)=>{     return <li key={index}>{item}</li>   }) } </ul>)
```

ç»æä¼æ¯ä¸ä¸ª JSX åç´ ç»æçæ°ç»ï¼æ¾å¥é¡µé¢ä¸­ï¼ä¸ä¼ä½¿ç¨éå·åéå¼ã

å¾ªç¯ç»å®ç JSX åç´ ï¼**å¿é¡»è¦æ key å±æ§**ï¼æ¥åºåä¸åçåç´ ï¼å¦åä¼æ¥éã

##### è¿æ»¤åç´ 

åæ ·éè¿ map æ¹æ³, åªè¦æä¸ç¬¦åæ¡ä»¶çåç´ , è¿åä¸º null å³å¯, åå å¨äº, null ä¼è¢«è¡¨ç¤ºä¸ºç©º. å¦æä½¿ç¨ filter, é£ä¹å°±æ²¡æåæ³å¯¹åç´ è¿è¡å¤ç, åªè½è¿æ»¤, è¿æ¯éè¦ä½¿ç¨ map è¿è¡å¤ç

```
let ul = (<ul>   { arr.map((item, index)=>{     return (       item.price < 1000 ? null : <li key={index}>{item}</li>;     )   }) } </ul>)
```

### 1.3.4. JSX ç»ä¹ 

éæ±: å¨æå±ç¤ºå¦ä¸åè¡¨

## 1.4. æ¨¡åä¸ç»ä»¶ãæ¨¡ååä¸ç»ä»¶åççè§£

### 1.4.1. æ¨¡å

\1. çè§£ï¼åå¤æä¾ç¹å®åè½ç js ç¨åº, ä¸è¬å°±æ¯ä¸ä¸ª js æä»¶

\2. ä¸ºä»ä¹è¦æææ¨¡åï¼éçä¸å¡é»è¾å¢å ï¼ä»£ç è¶æ¥è¶å¤ä¸å¤æã

\3. ä½ç¨ï¼å¤ç¨ js, ç®å js çç¼å, æé« js è¿è¡æç

### 1.4.2. ç»ä»¶

\1. çè§£ï¼ç¨æ¥å®ç°å±é¨åè½ææçä»£ç åèµæºçéå(html/css/js/image ç­ç­)

\2. ä¸ºä»ä¹è¦ç¨ç»ä»¶ï¼ ä¸ä¸ªçé¢çåè½æ´å¤æ

\3. ä½ç¨ï¼å¤ç¨ç¼ç , ç®åé¡¹ç®ç¼ç , æé«è¿è¡æç

### 1.4.3. æ¨¡åå

å½åºç¨ç js é½ä»¥æ¨¡åæ¥ç¼åç, è¿ä¸ªåºç¨å°±æ¯ä¸ä¸ªæ¨¡ååçåºç¨

### 1.4.4. ç»ä»¶å

å½åºç¨æ¯ä»¥å¤ç»ä»¶çæ¹å¼å®ç°, è¿ä¸ªåºç¨å°±æ¯ä¸ä¸ªç»ä»¶åçåºç¨

# ç¬¬ 2 ç« ï¼React é¢åç»ä»¶ç¼ç¨

## 2.1. åºæ¬çè§£åä½¿ç¨

### 2.1.1. ä½¿ç¨ React å¼åèå·¥å·è°è¯

### 2.1.2. ææ

å½æ°å¼ç»ä»¶ï¼

ç±»å¼ç»ä»¶ï¼

### 2.1.3. æ³¨æ

\1. ç»ä»¶åå¿é¡»é¦å­æ¯å¤§å

\2. èæ DOM åç´ åªè½æä¸ä¸ªæ ¹åç´ 

\3. èæ DOM åç´ å¿é¡»æç»ææ ç­¾

### 2.1.4. æ¸²æç±»ç»ä»¶æ ç­¾çåºæ¬æµç¨

\1. React åé¨ä¼åå»ºç»ä»¶å®ä¾å¯¹è±¡

\2. è°ç¨ render()å¾å°èæ DOM, å¹¶è§£æä¸ºçå® DOM

\3. æå¥å°æå®çé¡µé¢åç´ åé¨

## 2.2. ç»ä»¶ä¸å¤§æ ¸å¿å±æ§ 1: state

### 2.2.1. ææ

_éæ±**:**å®ä¹ä¸ä¸ªå±ç¤ºå¤©æ°ä¿¡æ¯çç»ä»¶_
_1.**é»è®¤å±ç¤ºå¤©æ°çç­**æ\*\*åç½_
_2. ç¹å»æå­åæ¢å¤©æ°_

### 2.2.2. çè§£

\1. state æ¯ç»ä»¶å¯¹è±¡æéè¦çå±æ§, å¼æ¯å¯¹è±¡(å¯ä»¥åå«å¤ä¸ª key-value çç»å)

\2. ç»ä»¶è¢«ç§°ä¸º"ç¶ææº", éè¿æ´æ°ç»ä»¶ç state æ¥æ´æ°å¯¹åºçé¡µé¢æ¾ç¤º(éæ°æ¸²æç»ä»¶)

### 2.2.3. å¼ºçæ³¨æ

\1. ç»ä»¶ä¸­ render æ¹æ³ä¸­ç this ä¸ºç»ä»¶å®ä¾å¯¹è±¡

\2. ç»ä»¶èªå®ä¹çæ¹æ³ä¸­ this ä¸º undefined ï¼å¦ä½è§£å³ï¼

a) å¼ºå¶ç»å® this: éè¿å½æ°å¯¹è±¡ç bind()

b) èµå¼è¯­å¥+ç®­å¤´å½æ°

\3. ç¶ææ°æ®ï¼ä¸è½ç´æ¥ä¿®æ¹ææ´æ°ï¼å¿é¡»éè¿ this.setState è¿è¡ä¿®æ¹

### 2.2.4 è¡¥å

#### -ç»ä»¶ç¶æ

ç»ä»¶ä¸­æ°æ®çæ¥æº

* å±æ§: æ¯ç±å¤æ¥ä¼ éè¿æ¥ç
* ç¶æ: æ¯èªå·±ç, åªè½éè¿ setState æ¥æ¹åç¶æ

åªæç±»å£°æçç»ä»¶ä¸­, ææç¶æ

#### -ä¿®æ¹ç¶æ

é¤äº constructor ä¹å¤çå¶å®å°æ¹, å¦æéè¦ä¿®æ¹ç¶æ, é½åªè½éè¿ this.setState æ¹æ³

è¿ä¸ªæ¹æ³ä¼ å¥çç¬¬ä¸ä¸ªåæ°, å¯ä»¥æ¯ä¸ä¸ªå¯¹è±¡, ä¹å¯ä»¥æ¯ä¸ä¸ªå½æ°

* æ¯ä¸ä¸ªå¯¹è±¡ï¼è¿ä¸ªå¯¹è±¡ä¸­åå«éè¦æ¹åçå±æ§ï¼å®ä¼ä¸åæçç¶æè¿è¡åå¹¶
* æ¯ä¸ä¸ªå½æ°ï¼æ¥æ¶ç¬¬ä¸ä¸ªåæ°æ¯ prevStateï¼ä¸ä¸ä¸ªç¶æå¯¹è±¡ï¼ç¬¬äºä¸ªåæ°æ¯ props

è¿ä¸ªæ¹æ³çç¬¬äºä¸ªåæ°ï¼æ¯ä¸ä¸ªåè°å½æ°ï¼å¨ç¶ææ¹åä¹åæ§è¡ã

å¦æä¸ä¸ä¸ªç¶æä¾èµäºä¸ä¸ä¸ªç¶æï¼éè¦åæå½æ°çæ¹å¼

#### -å³äº setState

* å¨ react ç»ä»¶ççå½å¨ææäºä»¶çç»å®ä¸­ï¼setState æ¯å¼æ­¥ç
* å¨å®æ¶å¨æåççäºä»¶ä¸­ï¼setState ä¸ä¸å®æ¯å¼æ­¥ç

// state.count å½åä¸º 0

componentDidMount(){ this.setState({count: this.state.count + 1}); 

console.log(this.state.count) } // è¾åº 0

å¨åç´ æ¸²æç« èä¸­ï¼æä»¬åªäºè§£äºä¸ç§æ´æ° UI çé¢çæ¹æ³ãéè¿è°ç¨ ReactDOM.render() æ¥ä¿®æ¹æä»¬æ³è¦æ¸²æçåç´ 

```
function tick() {   const element = (     <div>       <h1>Hello, world!</h1>       <h2>{new Date().toLocaleTimeString()}.</h2>     </div>   );   ReactDOM.render(element, document.querySelector('#root')); } setInterval(tick, 1000);
```

æ¬èå­¦ä¹ å¦ä½å°è£çæ­£å¯å¤ç¨ç Clock ç»ä»¶

```jsx
import React, { Component } from "react"
import ReactDOM from "react-dom" // å­¦ä¹ å¦ä½å°è£çæ­£å¯å¤ç¨çClockç»ä»¶ã 
class Clock extends Component {     constructor(props) {         super(props);         this.state = {             date: new Date().toLocaleString()         }     }
     componentDidMount() {         this.timer = setInterval(() => {             // æ³¨æ1 ä¸è½ç´æ¥ä¿®æ¹state             // 
     this.state.date = new Date(); //éè¯¯             // æ³¨æ2ï¼ setState()æ¯å¼æ­¥ç             
     this.setState({                 date: new Date().toLocaleString()             })         }, 1000);     }
          componentWillUnmount() {         clearInterval(this.timer);     }     render() {
                     // ä¿®æ¹ç¶æä¹å,ä¼éæ°è°ç¨
                     render         return (             <div>                 <h3>å½åæ¶é´ä¸º:{this.state.date}</h3>             </div>         );     } } ReactDOM.render(<Clock />, document.querySelector('#root'));
```

### çå½å¨æ

ä½èï¼åç«¯å¼åå°é©¬å¥
é¾æ¥ï¼https://juejin.cn/post/6898512934100533261
æ¥æºï¼æé
èä½æå½ä½èææãåä¸è½¬è½½è¯·èç³»ä½èè·å¾ææï¼éåä¸è½¬è½½è¯·æ³¨æåºå¤ã

## 2.3. ç»ä»¶ä¸å¤§æ ¸å¿å±æ§ 2: props

### 2.3.1. ææ

_éæ±**:**èªå®ä¹ç¨æ¥æ¾ç¤ºä¸ä¸ªäººåä¿¡æ¯çç»ä»¶_

_1.\*\*å§åå¿é¡»æå®ï¼ä¸ä¸ºå­ç¬¦ä¸²ç±»åï¼_

_2.\*\*æ§å«ä¸ºå­ç¬¦ä¸²ç±»åï¼å¦ææ§å«æ²¡ææå®ï¼é»è®¤ä¸ºç·_

_3.**å¹´é¾ä¸ºå­ç¬¦ä¸²ç±»åï¼ä¸ä¸ºæ°å­ç±»åï¼é»è®¤å¼ä¸º**18_

### 2.3.2. çè§£

\1. æ¯ä¸ªç»ä»¶å¯¹è±¡é½ä¼æ props(properties çç®å)å±æ§

\2. ç»ä»¶æ ç­¾çææå±æ§é½ä¿å­å¨ props ä¸­

### 2.3.3. ä½ç¨

\1. éè¿æ ç­¾å±æ§ä»ç»ä»¶å¤åç»ä»¶åä¼ éååçæ°æ®

\2. æ³¨æ: ç»ä»¶åé¨ä¸è¦ä¿®æ¹ props æ°æ®

### 2.3.4. ç¼ç æä½

\1. åé¨è¯»åæä¸ªå±æ§å¼

**this**.**props**.**name**

\2. å¯¹ props ä¸­çå±æ§å¼è¿è¡ç±»åéå¶åå¿è¦æ§éå¶

ç¬¬ä¸ç§æ¹å¼ï¼React v15.5 å¼å§å·²å¼ç¨ï¼ï¼

_Person_.**propTypes** = { **name**: **React**.**PropTypes**.**string**.isRequired, **age**: **React**.**PropTypes**.**number** }

ç¬¬äºç§æ¹å¼ï¼æ°ï¼ï¼ä½¿ç¨ prop-types åºè¿éå¶ï¼éè¦å¼å¥ prop-types åºï¼

_Person_.**propTypes** = { **name**: **PropTypes**.**string**.isRequired, **age**: **PropTypes**.**number**. }

\3. æ©å±å±æ§: å°å¯¹è±¡çææå±æ§éè¿ props ä¼ é

<**Person** {...**\*person**\*\*\*\*\*}/>

\4. é»è®¤å±æ§å¼ï¼

Person.**defaultProps** = { **age**: 18, **sex**:**'\*\***ç·' \*\* }

\5.

**constructor**(props){ **super**(props) **console**.log(props)_//**æå°ææå±æ§** _ }

ç»ä»¶ç±»çæé å½æ°

## 2.4. ç»ä»¶ä¸å¤§æ ¸å¿å±æ§ 3: refs ä¸äºä»¶å¤ç

### 2.4.1. ææ

_éæ±**:**èªå®ä¹ç»ä»¶**, **åè½è¯´æå¦ä¸\*\*:_

_1.**ç¹å»æé®**, \*\*æç¤ºç¬¬ä¸ä¸ªè¾å¥æ¡ä¸­çå¼_

\*2.**å½ç¬¬\*\***2\***\*ä¸ªè¾å¥æ¡å¤±å»ç¦ç¹æ¶**, \*_æç¤ºè¿ä¸ªè¾å¥æ¡ä¸­çå¼_

ææå¦ä¸ï¼

### 2.4.2. çè§£

ç»ä»¶åçæ ç­¾å¯ä»¥å®ä¹ ref å±æ§æ¥æ è¯èªå·±ï¼ç¸å½äºåç idï¼å¯ä»¥éè¿ this.refs. XX è·åæ°æ®

### 2.4.3. ç¼ç 

\1. å­ç¬¦ä¸²å½¢å¼ç ref

**<input\*\***ref\***\*="input1"/>**

\2. åè°å½¢å¼ç ref

**<input\*\***ref\***\*={(c)=>{this.input1** **=\*\***c\***\*}}/>**

\3. createRef åå»º ref å®¹å¨Â·

**myRef\*\***=\***\*React\*\***.createRef()\*\* **<input\*\***ref\***\*={this.myRef}/>**

### 2.4.4. äºä»¶å¤ç

\1. éè¿ onXxx å±æ§æå®äºä»¶å¤çå½æ°(æ³¨æå¤§å°å)

\1) React ä½¿ç¨çæ¯èªå®ä¹(åæ)äºä»¶, èä¸æ¯ä½¿ç¨çåç DOM äºä»¶

\2) React ä¸­çäºä»¶æ¯éè¿äºä»¶å§ææ¹å¼å¤çç(å§æç»ç»ä»¶æå¤å±çåç´ )

\2. éè¿ event.target å¾å°åçäºä»¶ç DOM åç´ å¯¹è±¡

## 2.5. æ¶éè¡¨åæ°æ®

### 2.5.1. ææ

_éæ±**:**å®ä¹ä¸ä¸ªåå«è¡¨åçç»ä»¶_

_è¾å¥ç¨æ·åå¯ç å**, **ç¹å»ç»å½æç¤ºè¾å¥ä¿¡æ¯_

### 2.5.2. çè§£

åå«è¡¨åçç»ä»¶åç±»

\1. åæ§ç»ä»¶

\2. éåæ§ç»ä»¶

## 2.6. ç»ä»¶ççå½å¨æ

### 2.6.1. ææ

\*éæ±\***\*:\*\***å®ä¹ç»ä»¶å®ç°ä»¥ä¸åè½ï¼\*

_1.**è®©æå®çææ¬åæ¾ç¤º**/\*\*éèçæ¸åå¨ç»_

_2.**ä»å®å¨å¯è§ï¼å°å½»åºæ¶å¤±ï¼èæ¶**2S_

_3.\*\*ç¹å»âä¸æ´»äºâæé®ä»çé¢ä¸­å¸è½½ç»ä»¶_

### 2.6.2. çè§£

\1. ç»ä»¶ä»åå»ºå°æ­»äº¡å®ä¼ç»åä¸äºç¹å®çé¶æ®µã

\2. React ç»ä»¶ä¸­åå«ä¸ç³»åå¾å­å½æ°(çå½å¨æåè°å½æ°), ä¼å¨ç¹å®çæ¶å»è°ç¨ã

\3. æä»¬å¨å®ä¹ç»ä»¶æ¶ï¼ä¼å¨ç¹å®ççå½å¨æåè°å½æ°ä¸­ï¼åç¹å®çå·¥ä½ã

### 2.6.3. çå½å¨ææµç¨å¾(æ§)

ä¸æ³å¯¹ç¶æè¿è¡æ´æ¹ï¼å¼ºå¶æ´æ° forceUpdate()

æ­£å¸¸æ´æ°ï¼setState()

ç¶ç»ä»¶ render:

**render**(){

return(

ææ¯ A ç»ä»¶

æ¢è½¦

```jsx
<B carName={this.state.carName}/>
```

</div>

)

}

**çå½å¨æçä¸ä¸ªé¶æ®µï¼æ§ï¼**

\1. åå§åé¶æ®µ: ç± ReactDOM.render()è§¦å---åæ¬¡æ¸²æ

\1. constructor()

\2. componentWillMount()

\3. render()

\4. componentDidMount() =====> å¸¸ç¨

ä¸è¬å¨è¿ä¸ªé©å­ä¸­åä¸äºåå§åçäºï¼ä¾å¦ï¼å¼å¯å®æ¶å¨ãåéç½ç»è¯·æ±ãè®¢éæ¶æ¯

\2. æ´æ°é¶æ®µ: ç±ç»ä»¶åé¨ this.setSate()æç¶ç»ä»¶ render è§¦å

\1. shouldComponentUpdate()

\2. componentWillUpdate()

\3. render() =====> å¿é¡»ä½¿ç¨çä¸ä¸ª

\4. componentDidUpdate()

\3. å¸è½½ç»ä»¶: ç± ReactDOM.unmountComponentAtNode()è§¦å

\1. componentWillUnmount() =====> å¸¸ç¨

ä¸è¬å¨è¿ä¸ªé©å­ä¸­åä¸äºæ¶å°¾çäºï¼ä¾å¦ï¼å³é­å®æ¶å¨ãåæ¶è®¢éæ¶æ¯

### 2.6.4. çå½å¨ææµç¨å¾(æ°)

çå½å¨æçä¸ä¸ªé¶æ®µï¼æ°ï¼

**1.\*\***åå§åé¶æ®µ:\*\* ç± ReactDOM.render()è§¦å---åæ¬¡æ¸²æ

\1. constructor()

**2.\*\***getDerivedStateFromProps =>\***\*è¿åç¶æå¯¹è±¡æè nullï¼è½æ¶å°åæ°** **props\*\***ï¼éç¨äºå¨ state å¼å¨ä»»ä½æ¶åé½åå³äº props, é£ä¹å¯ä»¥ä½¿ç¨ getDerivedStateFromProps\*\*

\3. render()

\4. componentDidMount() =>ä¸è¬å¨è¿ä¸ªé©å­ä¸­åä¸äºåå§åçäºï¼ä¾å¦ï¼å¼å¯å®æ¶å¨ãåéç½ç»è¯·æ±ãè®¢éæ¶æ¯

\5.

**2.\*\***æ´æ°é¶æ®µ:\*\* ç±ç»ä»¶åé¨ this.setSate()æç¶ç»ä»¶éæ° render è§¦å

**1.\*\***getDerivedStateFromProps\*\*

\2. shouldComponentUpdate()

\3. render()

**4.\*\***getSnapshotBeforeUpdate //\***\*å¨æ´æ°ä¹åè·åå¿«ç§ï¼å¨åçæ´æ¹åè·å DOM ä¿¡æ¯**

\5. componentDidUpdate()

**3.\*\***å¸è½½ç»ä»¶:\*\* ç± ReactDOM.unmountComponentAtNode()è§¦å

\1. componentWillUnmount() =====> å¸¸ç¨

ä¸è¬å¨è¿ä¸ªé©å­ä¸­åä¸äºæ¶å°¾çäºï¼ä¾å¦ï¼å³é­å®æ¶å¨ãåæ¶è®¢éæ¶æ¯

### 2.6.5. éè¦çå¾å­

\1. renderï¼åå§åæ¸²æææ´æ°æ¸²æè°ç¨

\2. componentDidMountï¼å¼å¯çå¬, åé ajax è¯·æ±

\3. componentWillUnmountï¼åä¸äºæ¶å°¾å·¥ä½, å¦: æ¸çå®æ¶å¨

### 2.6.6. å³å°åºå¼çå¾å­

\1. componentWillMount

\2. componentWillReceiveProps

\3. componentWillUpdate

ç°å¨ä½¿ç¨ä¼åºç°è­¦åï¼ä¸ä¸ä¸ªå¤§çæ¬éè¦å ä¸ UNSAFE\_åç¼æè½ä½¿ç¨ï¼ä»¥åå¯è½ä¼è¢«å½»åºåºå¼ï¼ä¸å»ºè®®ä½¿ç¨ã

## 2.7. èæ DOM ä¸ DOM Diffing ç®æ³

### 2.7.1. ææ

\*éæ±ï¼éªè¯èæ\***\*DOM Diffing\*\***ç®æ³çå­å¨\*

### 2.7.2. åºæ¬åçå¾

# ç¬¬ 3 ç« ï¼React åºç¨(åºäº React èææ¶)

## 3.1. ä½¿ç¨ create-react-app åå»º react åºç¨

### 3.1.1. react èææ¶

\1. xxx èææ¶: ç¨æ¥å¸®å©ç¨åºåå¿«éåå»ºä¸ä¸ªåºäº xxx åºçæ¨¡æ¿é¡¹ç®

\1. åå«äºææéè¦çéç½®ï¼è¯­æ³æ£æ¥ãjsx ç¼è¯ãdevServerâ¦ï¼

\2. ä¸è½½å¥½äºææç¸å³çä¾èµ

\3. å¯ä»¥ç´æ¥è¿è¡ä¸ä¸ªç®åææ

\2. react æä¾äºä¸ä¸ªç¨äºåå»º react é¡¹ç®çèææ¶åº: create-react-app

\3. é¡¹ç®çæ´ä½ææ¯æ¶æä¸º: react + webpack + es6 + eslint

\4. ä½¿ç¨èææ¶å¼åçé¡¹ç®çç¹ç¹: æ¨¡åå, ç»ä»¶å, å·¥ç¨å

### 3.1.2. åå»ºé¡¹ç®å¹¶å¯å¨

**ç¬¬ä¸æ­¥**ï¼å¨å±å®è£ï¼npm i -g create-react-app

**ç¬¬äºæ­¥**ï¼åæ¢å°æ³åé¡¹ç®çç®å½ï¼ä½¿ç¨å½ä»¤ï¼create-react-app hello-react

**ç¬¬ä¸æ­¥**ï¼è¿å¥é¡¹ç®æä»¶å¤¹ï¼cd hello-react

**ç¬¬åæ­¥**ï¼å¯å¨é¡¹ç®ï¼npm start

### 3.1.3. react èææ¶é¡¹ç®ç»æ

public ---- éæèµæºæä»¶å¤¹

favicon.icon ------ ç½ç«é¡µç­¾å¾æ 

**index.html --------\*\***ä¸»é¡µé¢, åªæä¸ä¸ª html æä»¶\*\*

logo192.png ------- logo å¾

logo512.png ------- logo å¾

manifest.json ----- åºç¨å å£³çéç½®æä»¶

robots.txt -------- ç¬è«åè®®æä»¶

src ---- æºç æä»¶å¤¹

App.css -------- App ç»ä»¶çæ ·å¼

**App.js --------- App\*\***ç»ä»¶ï¼ææåºç¨çå¤å£³ç»ä»¶\*\*

App.test.js ---- ç¨äºç» App åæµè¯

index.css ------ æ ·å¼ï¼ç»ä»¶å¼å¥ï¼æ¸²æ index.html ä¸­å®ä¹çå®¹å¨

ä½¿ç¨<React. StrictMode></ React. StrictMode>æ£æ¥

**index.js -------\*\***å¥å£æä»¶\*\*

logo.svg ------- logo å¾

reportWebVitals.js

--- é¡µé¢æ§è½åææä»¶(éè¦ web-vitals åºçæ¯æ)è®°å½é¡µé¢ä¸çæ§è½ï¼web-vital åºè¿è¡æ§è½åæ

setupTests.js

---- ç»ä»¶ååæµè¯çæä»¶(éè¦ jest-dom åºçæ¯æ)

%PIBLIC_URL%ä»£è¡¨ public æä»¶å¤¹çè·¯å¾

### Rcc: ç±»å¼ç»ä»¶

Rfcï¼å½æ°å¼ç»ä»¶

### 3.1.4. åè½çé¢çç»ä»¶åç¼ç æµç¨ï¼éç¨ï¼

\1. æåç»ä»¶: æåçé¢, æ½åç»ä»¶

\2. å®ç°éæç»ä»¶: ä½¿ç¨ç»ä»¶å®ç°éæé¡µé¢ææ

\3. å®ç°å¨æç»ä»¶

3.1 å¨ææ¾ç¤ºåå§åæ°æ®

ç¶ææ¾å¨åªéï¼

3.1.1 æ°æ®ç±»å

3.1.2 æ°æ®åç§°

3.1.2 ä¿å­å¨åªä¸ªç»ä»¶?

3.2 äº¤äº(ä»ç»å®äºä»¶çå¬å¼å§)

## 3.2. ç»ä»¶çç»åä½¿ç¨-TodoList

_åè½**:**ç»ä»¶åå®ç°æ­¤åè½_

\*1.**æ¾ç¤ºææ\*\***todo\*_\*\*åè¡¨_

_2.**è¾å¥ææ¬**, **ç¹å»æé®æ¾ç¤ºå°åè¡¨çé¦ä½**, \*\*å¹¶æ¸é¤è¾å¥çææ¬_

reactDOM.render ä¹æ§è¡ä¸æ¬¡

index.html=>index.js(App.js é¡µé¢å±ç°å¨é¡µé¢)=>App.js

å­ç»ç¶ä¼ éä¿¡æ¯ï¼å¤«ç»å­ä¼ éä¸ä¸ªå½æ° ç¨ props ä¼ é

å®è£ nanoid

npm i nanoid

nanoid æ¯ä¸ä¸ªå½æ°ï¼æ¯ä¸æ¬¡çæçæ¶åé½ä¼çæä¸ä¸ªå­ç¬¦ä¸²ï¼å¹¶ä¸å¯ä»¥ä¿è¯æ¯å¯ä¸ç

# ç¬¬ 4 ç« ï¼React ajax

## React ajax çè§£

### 4.1.1. åç½®è¯´æ

\1. React æ¬èº«åªå³æ³¨äºçé¢, å¹¶ä¸åå«åé ajax è¯·æ±çä»£ç 

\2. åç«¯åºç¨éè¦éè¿ ajax è¯·æ±ä¸åå°è¿è¡äº¤äº(json æ°æ®)

\3. react åºç¨ä¸­éè¦éæç¬¬ä¸æ¹ ajax åº(æèªå·±å°è£)

### 4.1.2. å¸¸ç¨ç ajax è¯·æ±åº

\1. jQuery: æ¯è¾é, å¦æéè¦å¦å¤å¼å¥ä¸å»ºè®®ä½¿ç¨

\2. axios: è½»éçº§, å»ºè®®ä½¿ç¨

\1) å°è£ XmlHttpRequest å¯¹è±¡ç ajax

\2) promise é£æ ¼

\3) å¯ä»¥ç¨å¨æµè§å¨ç«¯å node æå¡å¨ç«¯

## 4.2. axios

### 4.2.1. ææ¡£

https://github.com/axios/axios

### 4.2.2. ç¸å³ API

\1) GET è¯·æ±

```
axios.get('/user?ID=12345') .then(function (response) {   console.log(response.data); }) .catch(function (error) { console.log(error); }); axios.get('/user', { params: { ID: 12345 } }) .then(function (response) { console.log(response); }) .catch(function (error) { console.log(error); });
```

\2) POST è¯·æ±

```
axios.post('/user', { firstName: 'Fred', lastName: 'Flintstone' }) .then(function (response) { console.log(response); }) .catch(function (error) { console.log(error); });
```

## 4.3. æ¡ä¾âgithub ç¨æ·æç´¢

### 4.3.1. ææ

è¯·æ±å°å: https://api.github.com/search/users?q=xxxxxx

## 4.4. æ¶æ¯è®¢é-åå¸æºå¶

\1. å·¥å·åº: PubSubJS

\2. ä¸è½½: npm install pubsub-js --save

\3. ä½¿ç¨:

\1) import PubSub from 'pubsub-js' //å¼å¥

\2) PubSub.subscribe('delete', function(data){ }); //è®¢é

\3) PubSub.publish('delete', data) //åå¸æ¶æ¯

## 4.5. æ©å±ï¼Fetch

### 4.5.1. ææ¡£

\1. https://github.github.io/fetch/

\2. https://segmentfault.com/a/1190000003810652

### 4.5.2. ç¹ç¹

\1. fetch: åçå½æ°ï¼ä¸åä½¿ç¨ XmlHttpRequest å¯¹è±¡æäº¤ ajax è¯·æ±

\2. èçæ¬æµè§å¨å¯è½ä¸æ¯æ

### 4.5.3. ç¸å³ API

\1) GET è¯·æ±

fetch(url).then(function(response) { return response.json() }).then(function(data) { console.log(data) }).catch(function(e) { console.log(e) }); 

\2) POST è¯·æ±

fetch(url, { method: "POST", body: JSON.stringify(data), }).then(function(data) { console.log(data) }).catch(function(e) { console.log(e) })

# ç¬¬ 5 ç« ï¼React è·¯ç±

# ç¬¬ 6 ç« ï¼React UI ç»ä»¶åº

## 6.1. æµè¡çå¼æº React UI ç»ä»¶åº

### 6.1.1. material-ui(å½å¤)

\1. å®ç½: http://www.material-ui.com/#/

\2. github: https://github.com/callemall/material-ui

### 6.1.2. ant-design(å½åèèéæ)

\1. å®ç½: https://ant.design/index-cn

\2. Github: https://github.com/ant-design/ant-design/

# ç¬¬ 7 ç« ï¼redux

## 7.1. redux çè§£

### 7.1.1. å­¦ä¹ ææ¡£

\1. è±æææ¡£: https://redux.js.org/

\2. ä¸­æææ¡£: http://www.redux.org.cn/

\3. Github: https://github.com/reactjs/redux

### 7.1.2. redux æ¯ä»ä¹

\1. redux æ¯ä¸ä¸ªä¸é¨ç¨äºå**ç¶æç®¡ç**ç JS åº(ä¸æ¯ react æä»¶åº)ã

\2. å®å¯ä»¥ç¨å¨ react, angular, vue ç­é¡¹ç®ä¸­, ä½åºæ¬ä¸ react éåä½¿ç¨ã

\3. ä½ç¨: éä¸­å¼ç®¡ç react åºç¨ä¸­å¤ä¸ªç»ä»¶**å±äº«**çç¶æã

### 7.1.3. ä»ä¹æåµä¸éè¦ä½¿ç¨ redux

\1. æä¸ªç»ä»¶çç¶æï¼éè¦è®©å¶ä»ç»ä»¶å¯ä»¥éæ¶æ¿å°ï¼å±äº«ï¼ã

\2. ä¸ä¸ªç»ä»¶éè¦æ¹åå¦ä¸ä¸ªç»ä»¶çç¶æï¼éä¿¡ï¼ã

\3. æ»ä½ååï¼è½ä¸ç¨å°±ä¸ç¨, å¦æä¸ç¨æ¯è¾ååæèèä½¿ç¨ã

### 7.1.4. redux å·¥ä½æµç¨

## 7.2. redux çä¸ä¸ªæ ¸å¿æ¦å¿µ

### 7.2.1. action

\1. å¨ä½çå¯¹è±¡

\2. åå« 2 ä¸ªå±æ§

l typeï¼æ è¯å±æ§, å¼ä¸ºå­ç¬¦ä¸², å¯ä¸, å¿è¦å±æ§

l dataï¼æ°æ®å±æ§, å¼ç±»åä»»æ, å¯éå±æ§

\3. ä¾å­ï¼{ type: 'ADD_STUDENT', data:{name: 'tom', age:18} }

### 7.2.2. reducer

\1. ç¨äºåå§åç¶æãå å·¥ç¶æã

\2. å å·¥æ¶ï¼æ ¹æ®æ§ç state å actionï¼ äº§çæ°ç state ç**çº¯å½æ°\*\***ã\*\*

### 7.2.3. store

\1. å° stateãactionãreducer èç³»å¨ä¸èµ·çå¯¹è±¡

\2. å¦ä½å¾å°æ­¤å¯¹è±¡?

\1) import {createStore} from 'redux'

\2) import reducer from './reducers'

\3) const store = createStore(reducer)

\3. æ­¤å¯¹è±¡çåè½?

\1) getState(): å¾å° state

\2) dispatch(action): åå action, è§¦å reducer è°ç¨, äº§çæ°ç state

\3) subscribe(listener): æ³¨åçå¬, å½äº§çäºæ°ç state æ¶, èªå¨è°ç¨

## 7.3. redux çæ ¸å¿ API

### 7.3.1. createstore()

ä½ç¨ï¼åå»ºåå«æå® reducer ç store å¯¹è±¡

### 7.3.2. store å¯¹è±¡

\1. ä½ç¨: redux åºææ ¸å¿çç®¡çå¯¹è±¡

\2. å®åé¨ç»´æ¤ç:

\1) state

\2) reducer

\3. æ ¸å¿æ¹æ³:

\1) getState()

\2) dispatch(action)

\3) subscribe(listener)

\4. å·ä½ç¼ç :

\1) store.getState()

\2) store.dispatch({type:'INCREMENT', number})

\3) store.subscribe(render)

### 7.3.3. applyMiddleware()

ä½ç¨ï¼åºç¨ä¸åºäº redux çä¸­é´ä»¶(æä»¶åº)

### 7.3.4. combineReducers()

ä½ç¨ï¼åå¹¶å¤ä¸ª reducer å½æ°

## 7.4. ä½¿ç¨ redux ç¼ååºç¨

**ææ**

## 7.5. redux å¼æ­¥ç¼ç¨

### 7.5.1 çè§£ï¼

\1. redux é»è®¤æ¯ä¸è½è¿è¡å¼æ­¥å¤çç, 

\2. æäºæ¶ååºç¨ä¸­éè¦å¨**redux\*\***ä¸­æ§è¡å¼æ­¥ä»»å¡\*\*(ajax, å®æ¶å¨)

### 7.5.2. ä½¿ç¨å¼æ­¥ä¸­é´ä»¶

npm install --save redux-thunk

## 7.6. react-redux

### 7.6.1. çè§£

\1. ä¸ä¸ª react æä»¶åº

\2. ä¸é¨ç¨æ¥ç®å react åºç¨ä¸­ä½¿ç¨ redux

### 7.6.2. react-Redux å°ææç»ä»¶åæä¸¤å¤§ç±»

\1. UI ç»ä»¶

\1) åªè´è´£ UI çåç°ï¼ä¸å¸¦æä»»ä½ä¸å¡é»è¾

\2) éè¿ props æ¥æ¶æ°æ®(ä¸è¬æ°æ®åå½æ°)

\3) ä¸ä½¿ç¨ä»»ä½ Redux ç API

\4) ä¸è¬ä¿å­å¨ components æä»¶å¤¹ä¸

\2. å®¹å¨ç»ä»¶

\1) è´è´£ç®¡çæ°æ®åä¸å¡é»è¾ï¼ä¸è´è´£ UI çåç°

\2) ä½¿ç¨ Redux ç API

\3) ä¸è¬ä¿å­å¨ containers æä»¶å¤¹ä¸

### 7.6.3. ç¸å³ API

\1. Providerï¼è®©ææç»ä»¶é½å¯ä»¥å¾å° state æ°æ®

**<**Provider **store** ={store}> **<**App **/></**Provider>

\2. connectï¼ç¨äºåè£ UI ç»ä»¶çæå®¹å¨ç»ä»¶

**import{connect}from'react-redux'connect**( **mapStateToprops**, **mapDispatchToProps)(**Counter)

\3. mapStateTopropsï¼å°å¤é¨çæ°æ®ï¼å³ state å¯¹è±¡ï¼è½¬æ¢ä¸º UI ç»ä»¶çæ ç­¾å±æ§

**constmapStateToprops=function(**state) { **return{value:state}}**

\4. mapDispatchToPropsï¼å°åå action çå½æ°è½¬æ¢ä¸º UI ç»ä»¶çæ ç­¾å±æ§

## 7.7. ä½¿ç¨ä¸ redux è°è¯å·¥å·

### 7.7.1. å®è£ chrome æµè§å¨æä»¶

### 7.7.2. ä¸è½½å·¥å·ä¾èµå

npm install --save-dev redux-devtools-extension

## 7.8. çº¯å½æ°åé«é¶å½æ°

### 7.8.1. çº¯å½æ°

\1. ä¸ç±»ç¹å«çå½æ°: åªè¦æ¯åæ ·çè¾å¥(å®å)ï¼å¿å®å¾å°åæ ·çè¾åº(è¿å)

\2. å¿é¡»éµå®ä»¥ä¸ä¸äºçº¦æ

\1) ä¸å¾æ¹ååæ°æ°æ®

\2) ä¸ä¼äº§çä»»ä½å¯ä½ç¨ï¼ä¾å¦ç½ç»è¯·æ±ï¼è¾å¥åè¾åºè®¾å¤

\3) ä¸è½è°ç¨ Date.now()æè Math.random()ç­ä¸çº¯çæ¹æ³

\3. redux ç reducer å½æ°å¿é¡»æ¯ä¸ä¸ªçº¯å½æ°

### 7.8.2. é«é¶å½æ°

\1. çè§£: ä¸ç±»ç¹å«çå½æ°

\1) æåµ 1: åæ°æ¯å½æ°

\2) æåµ 2: è¿åæ¯å½æ°

\2. å¸¸è§çé«é¶å½æ°:

\1) å®æ¶å¨è®¾ç½®å½æ°

\2) æ°ç»ç forEach()/map()/filter()/reduce()/find()/bind()

\3) promise

\4) react-redux ä¸­ç connect å½æ°

\3. ä½ç¨: è½å®ç°æ´å å¨æ, æ´å å¯æ©å±çåè½ babelâ è¿ç®ç¬¦{...}. åªè½éç¨äºæ ç­¾å±æ§ä¼ é

æé å¨æ¯å¦æ¥æ¶ propsï¼æ¯å¦ä¼ éç» superï¼åå³äºï¼æ¯å¦å¸æå¨æé å¨ä¸­éè¿ this è®¿é® props

å¿é¡»è¦å°ä¸ä¸ªå½æ°ä½ä¸ºäºä»¶çåè°

render å¨æ¯æ¬¡æè½½çæ¶åè°ç¨ ï¼è°ç¨ 1+n æ¬¡ï¼

ç»å¸é¢è¯é¢:

1). react/vue ä¸­ç key æä»ä¹ä½ç¨ï¼ï¼key çåé¨åçæ¯ä»ä¹ï¼ï¼

2). ä¸ºä»ä¹éååè¡¨æ¶ï¼key æå¥½ä¸è¦ç¨ index?

\1. èæ DOM ä¸­ key çä½ç¨ï¼ææ²¡ææ¸²æï¼æ¸²æè¿å°±ç´æ¥ä½¿ç¨

1). ç®åçè¯´: key æ¯èæ DOM å¯¹è±¡çæ è¯, å¨æ´æ°æ¾ç¤ºæ¶ key èµ·çæå¶éè¦çä½ç¨ã

2). è¯¦ç»çè¯´: å½ç¶æä¸­çæ°æ®åçååæ¶ï¼react ä¼æ ¹æ®ãæ°æ°æ®ãçæãæ°çèæ DOMã, 

éå React è¿è¡ãæ°èæ DOMãä¸ãæ§èæ DOMãç diff æ¯è¾ï¼æ¯è¾è§åå¦ä¸ï¼

a. æ§èæ DOM ä¸­æ¾å°äºä¸æ°èæ DOM ç¸åç keyï¼

(1). è¥èæ DOM ä¸­åå®¹æ²¡å, ç´æ¥ä½¿ç¨ä¹åççå® DOM

(2). è¥èæ DOM ä¸­åå®¹åäº, åçææ°ççå® DOMï¼éåæ¿æ¢æé¡µé¢ä¸­ä¹åççå® DOM

b. æ§èæ DOM ä¸­æªæ¾å°ä¸æ°èæ DOM ç¸åç key

æ ¹æ®æ°æ®åå»ºæ°ççå® DOMï¼éåæ¸²æå°å°é¡µé¢

\2. ç¨ index ä½ä¸º key å¯è½ä¼å¼åçé®é¢ï¼

\1. è¥å¯¹æ°æ®è¿è¡ï¼éåºæ·»å ãéåºå é¤ç­ç ´åé¡ºåºæä½:

ä¼äº§çæ²¡æå¿è¦ççå® DOM æ´æ° ==> çé¢æææ²¡é®é¢, ä½æçä½ã

\2. å¦æç»æä¸­è¿åå«è¾å¥ç±»ç DOMï¼

ä¼äº§çéè¯¯ DOM æ´æ° ==> çé¢æé®é¢ã

\3. æ³¨æï¼å¦æä¸å­å¨å¯¹æ°æ®çéåºæ·»å ãéåºå é¤ç­ç ´åé¡ºåºæä½ï¼

ä»ç¨äºæ¸²æåè¡¨ç¨äºå±ç¤ºï¼ä½¿ç¨ index ä½ä¸º key æ¯æ²¡æé®é¢çã

\3. å¼åä¸­å¦ä½éæ© key?:

1. æå¥½ä½¿ç¨æ¯æ¡æ°æ®çå¯ä¸æ è¯ä½ä¸º key, æ¯å¦ idãææºå·ãèº«ä»½è¯å·ãå­¦å·ç­å¯ä¸å¼ã

2. å¦æç¡®å®åªæ¯ç®åçå±ç¤ºæ°æ®ï¼ç¨ index ä¹æ¯å¯ä»¥çã

\*/

/\*

æ¢å¨ä½åæ¾----ä½¿ç¨ index ç´¢å¼å¼ä½ä¸º key

åå§æ°æ®ï¼

{id:1, name:'å°å¼ ', age:18}, 

{id:2, name:'å°æ', age:19}, 

åå§çèæ DOMï¼

<li key=0>å°å¼ ---18<input type="text"/></li>

<li key=1>å°æ---19<input type="text"/></li>

æ´æ°åçæ°æ®ï¼

{id:3, name:'å°ç', age:20}, 

{id:1, name:'å°å¼ ', age:18}, 

{id:2, name:'å°æ', age:19}, 

æ´æ°æ°æ®åçèæ DOMï¼

<li key=0>å°ç---20<input type="text"/></li>

<li key=1>å°å¼ ---18<input type="text"/></li>

<li key=2>å°æ---19<input type="text"/></li>

\-----------------------------------------------------------------

æ¢å¨ä½åæ¾----ä½¿ç¨ id å¯ä¸æ è¯ä½ä¸º key

åå§æ°æ®ï¼

{id:1, name:'å°å¼ ', age:18}, 

{id:2, name:'å°æ', age:19}, 

åå§çèæ DOMï¼

<li key=1>å°å¼ ---18<input type="text"/></li>

<li key=2>å°æ---19<input type="text"/></li>

æ´æ°åçæ°æ®ï¼

{id:3, name:'å°ç', age:20}, 

{id:1, name:'å°å¼ ', age:18}, 

{id:2, name:'å°æ', age:19}, 

æ´æ°æ°æ®åçèæ DOMï¼

<li key=3>å°ç---20<input type="text"/></li>

<li key=1>å°å¼ ---18<input type="text"/></li>

<li key=2>å°æ---19<input type="text"/></li>

# ç¬¬å«ç« .hoooks

## React Hooks æ¯ä»ä¹ï¼

Hooks é¡¾åæä¹ï¼å­é¢æä¹ä¸æ¥è¯´å°±æ¯ React é©å­çæ¦å¿µãéè¿ä¸ä¸ª case æä»¬å¯¹ React Hooks åæä¸ä¸ªç¬¬ä¸å°è±¡ã

åè®¾ç°å¨è¦å®ç°ä¸ä¸ªè®¡æ°å¨çç»ä»¶ãå¦æä½¿ç¨ç»ä»¶åçæ¹å¼ï¼æä»¬éè¦åçäºæç¸å¯¹æ´å¤ä¸äºï¼æ¯å¦è¯´å£°æ stateï¼ç¼åè®¡æ°å¨çæ¹æ³ç­ï¼èä¸éè¦çè§£çæ¦å¿µå¯è½æ´å¤ä¸äºï¼æ¯å¦ Javascript çç±»çæ¦å¿µï¼this ä¸ä¸æçæåç­ã

<!-- more -->

[ç¤ºä¾](https://codepen.io/x-cold/pen/JqjZKR)

```jsx
import React, { Component } from "react"
import ReactDOM from "react-dom"

class Counter extends React.Component {
  state = {
    count: 0,
  }

  countUp = () => {
    const { count } = this.state
    this.setState({ count: count + 1 })
  }

  countDown = () => {
    const { count } = this.state
    this.setState({ count: count - 1 })
  }

  render() {
    const { count } = this.state
    return (
      <div>
        <button onClick={this.countUp}>+</button>
        <h1>{count}</h1>
        <button onClick={this.countDown}>-</button>
      </div>
    )
  }
}

ReactDOM.render(<Counter />, document.getElementById("root"))
```

ä½¿ç¨ React Hooksï¼æä»¬å¯ä»¥è¿ä¹åã

[ç¤ºä¾](https://codepen.io/x-cold/pen/ZNEReY)

```jsx
import React, { useState } from "react"
import ReactDOM from "react-dom"

function Counter() {
  const [count, setCount] = useState(0)
  return (
    <div>
      <button onClick={() => setCount(count + 1)}>+</button>
      <h1>{count}</h1>
      <button onClick={() => setCount(count - 1)}>-</button>
    </div>
  )
}

ReactDOM.render(<Counter />, document.getElementById("root"))
```

éè¿ä¸é¢çä¾å­ï¼æ¾èæè§çæ¯ React Hooks æä¾äºä¸ç§ç®æ´çãå½æ°å¼ï¼FPï¼çç¨åºé£æ ¼ï¼éè¿çº¯å½æ°ç»ä»¶åå¯æ§çæ°æ®æµæ¥å®ç°ç¶æå° UI çäº¤äºï¼MVVMï¼ã

### Hooks API

* [Basic Hooks](https://reactjs.org/docs/hooks-reference.html#basic-hooks)

* - `useState`
  + `useEffect`

* - `useContext`

* [Additional Hooks](https://reactjs.org/docs/hooks-reference.html#additional-hooks)

* - `useReducer`
  + `useCallback`

* - `useMemo`
  + `useRef`

* - `useImperativeHandle`
  + `useLayoutEffect`

* - `useDebugValue`

### useState

useState æ¯æåºæ¬ç APIï¼å®ä¼ å¥ä¸ä¸ªåå§å¼ï¼æ¯æ¬¡å½æ°æ§è¡é½è½æ¿å°æ°å¼ã

```jsx
import React, { useState } from "react"
import ReactDOM from "react-dom"

function Counter() {
  const [count, setCount] = useState(0)
  return (
    <div>
      <button onClick={() => setCount(count + 1)}>+</button>
      <h1>{count}</h1>
      <button onClick={() => setCount(count - 1)}>-</button>
    </div>
  )
}

ReactDOM.render(<Counter />, document.getElementById("root"))
```

éè¦æ³¨æçæ¯ï¼éè¿ useState å¾å°çç¶æ countï¼å¨ Counter ç»ä»¶ä¸­çè¡¨ç°ä¸ºä¸ä¸ªå¸¸éï¼æ¯ä¸æ¬¡éè¿ setCount è¿è¡ä¿®æ¹åï¼åéæ°éè¿ useState è·åå°ä¸ä¸ªæ°çå¸¸éã

### useReducer

useReducer å useState å ä¹æ¯ä¸æ ·çï¼éè¦å¤ç½®å¤ç½® reducer (å¨å±)ï¼éè¿è¿ç§æ¹å¼å¯ä»¥å¯¹å¤ä¸ªç¶æåæ¶è¿è¡æ§å¶ãä»ç»ç«¯è¯¦èµ·æ¥ï¼å¶å®è· redux ä¸­çæ°æ®æµçæ¦å¿µéå¸¸æ¥è¿ã

```jsx
import { useState, useReducer } from "react"
import ReactDOM from "react-dom"

function reducer(state, action) {
  switch (action.type) {
    case "up":
      return { count: state.count + 1 }
    case "down":
      return { count: state.count - 1 }
  }
}

function Counter() {
  const [state, dispatch] = useReducer(reducer, { count: 1 })
  return (
    <div>
      {state.count}
      <button onClick={() => dispatch({ type: "up" })}>+</button>
      <button onClick={() => dispatch({ type: "down" })}>+</button>
    </div>
  )
}

ReactDOM.render(<Counter />, document.getElementById("root"))
```

### useEffect

ä¸ä¸ªè³å³éè¦ç Hooks APIï¼é¡¾åæä¹ï¼useEffect æ¯ç¨äºå¤çåç§ç¶æååé æçå¯ä½ç¨ï¼ä¹å°±æ¯è¯´åªæå¨ç¹å®çæ¶å»ï¼æä¼æ§è¡çé»è¾ãç¸å½äº componentDidMountï¼ï¼å componentDidUpdateï¼ï¼

å½ä½ è°ç¨ useEffect æ¶ï¼å°±æ¯å¨åè¯ React å¨å®æå¯¹ DOM çæ´æ¹åè¿è¡ä½ çâå¯ä½ç¨âå½æ°ãç±äºå¯ä½ç¨å½æ°æ¯å¨ç»ä»¶åå£°æçï¼æä»¥å®ä»¬å¯ä»¥è®¿é®å°ç»ä»¶ç props å stateãé»è®¤æåµä¸ï¼React ä¼å¨æ¯æ¬¡æ¸²æåè°ç¨å¯ä½ç¨å½æ° ââ **åæ¬**ç¬¬ä¸æ¬¡æ¸²æçæ¶åãï¼æä»¬ä¼å¨[ä½¿ç¨ Effect Hook](https://react.docschina.org/docs/hooks-effect.html) ä¸­è· class ç»ä»¶ççå½å¨ææ¹æ³åæ´è¯¦ç»çå¯¹æ¯ãï¼

å¯ä½ç¨å½æ°è¿å¯ä»¥éè¿è¿åä¸ä¸ªå½æ°æ¥æå®å¦ä½âæ¸é¤âå¯ä½ç¨ã

```jsx
import { useState, useEffect } from "react"
import ReactDOM from "react-dom"

function Example() {
  const [count, setCount] = useState(0)

  // => componentDidMount/componentDidUpdate
  useEffect(() => {
    // update
    document.title = `You clicked ${count} times`
    // => componentWillUnMount
    return function cleanup() {
      document.title = "app"
    }
  }, [count])

  return (
    <div>
      <p>You clicked {count} times</p>
      <button onClick={() => setCount(count + 1)}>Click me</button>
    </div>
  )
}

ReactDOM.render(<Example />, document.getElementById("root"))
```

### useMemo

useMemo ä¸»è¦ç¨äºæ¸²æè¿ç¨ä¼åï¼ä¸¤ä¸ªåæ°ä¾æ¬¡æ¯è®¡ç®å½æ°ï¼éå¸¸æ¯ç»ä»¶å½æ°ï¼åä¾èµç¶æåè¡¨ï¼å½ä¾èµçç¶æåçæ¹åæ¶ï¼æä¼è§¦åè®¡ç®å½æ°çæ§è¡ãå¦ææ²¡ææå®ä¾èµï¼åæ¯ä¸æ¬¡æ¸²æè¿ç¨é½ä¼æ§è¡è¯¥è®¡ç®å½æ°ã

```jsx
const memoizedValue = useMemo(() => computeExpensiveValue(a, b), [a, b])
```

```jsx
import { useState, useMemo } from "react"
import ReactDOM from "react-dom"

function Time() {
  return <p>{Date.now()}</p>
}

function Counter() {
  const [count, setCount] = useState(0)

  const memoizedChildComponent = useMemo(
    (count) => {
      return <Time />
    },
    [count]
  )

  return (
    <div>
      <h1>{count}</h1>
      <button onClick={() => setCount(count + 1)}>+</button>
      <div>{memoizedChildComponent}</div>
    </div>
  )
}

ReactDOM.render(<Counter />, document.getElementById("root"))
```

### useContext

context æ¯å¨å¤é¨ create ï¼åé¨ use ç stateï¼å®åå¨å±åéçåºå«å¨äºï¼å¦æå¤ä¸ªç»ä»¶åæ¶ useContextï¼é£ä¹è¿äºç»ä»¶é½ä¼ rerenderï¼å¦æå¤ä¸ªç»ä»¶åæ¶ useState åä¸ä¸ªå¨å±åéï¼ååªæè§¦å setState çå½åç»ä»¶ rerenderã

[ç¤ºä¾-æªä½¿ç¨ useContext](https://codepen.io/x-cold/pen/OYJGKQ)

```jsx
import { useState, useContext, createContext } from "react"
import ReactDOM from "react-dom"

// 1. ä½¿ç¨ createContext åå»ºä¸ä¸æ
const UserContext = createContext()

// 2. åå»º Provider
const UserProvider = (props) => {
  let [username, handleChangeUsername] = useState("")
  return (
    <UserContext.Provider value={{ username, handleChangeUsername }}>
      {props.children}
    </UserContext.Provider>
  )
}

// 3. åå»º Consumer
const UserConsumer = UserContext.Consumer

// 4. ä½¿ç¨ Consumer åè£¹ç»ä»¶
const Pannel = () => (
  <UserConsumer>
    {({ username, handleChangeUsername }) => (
      <div>
        <div>user: {username}</div>
        <input onChange={(e) => handleChangeUsername(e.target.value)} />
      </div>
    )}
  </UserConsumer>
)

const Form = () => <Pannel />

const App = () => (
  <div>
    <UserProvider>
      <Form />
    </UserProvider>
  </div>
)

ReactDOM.render(<App />, document.getElementById("root"))
```

[ç¤ºä¾ - ä½¿ç¨ useContext](https://codepen.io/x-cold/pen/GaRLqZ?editors=0010)

```jsx
import { useState, useContext, createContext } from "react"
import ReactDOM from "react-dom"

// 1. ä½¿ç¨ createContext åå»ºä¸ä¸æ
const UserContext = createContext()

// 2. åå»º Provider
const UserProvider = (props) => {
  let [username, handleChangeUsername] = useState("")
  return (
    <UserContext.Provider value={{ username, handleChangeUsername }}>
      {props.children}
    </UserContext.Provider>
  )
}

const Pannel = () => {
  const { username, handleChangeUsername } = useContext(UserContext) // 3. ä½¿ç¨ Context
  return (
    <div>
      <div>user: {username}</div>
      <input onChange={(e) => handleChangeUsername(e.target.value)} />
    </div>
  )
}

const Form = () => <Pannel />

const App = () => (
  <div>
    <UserProvider>
      <Form />
    </UserProvider>
  </div>
)

ReactDOM.render(<App />, document.getElementById("root"))
```

### useRef

useRef è¿åä¸ä¸ªå¯åç ref å¯¹è±¡ï¼å¶ .current å±æ§åå§åä¸ºä¼ éçåæ°ï¼initialValueï¼ãè¿åçå¯¹è±¡å°æç»­æ´ä¸ªç»ä»¶ççå½å¨æãäºå®ä¸ useRef æ¯ä¸ä¸ªéå¸¸æç¨ç APIï¼è®¸å¤æåµä¸ï¼æä»¬éè¦ä¿å­ä¸äºæ¹åçä¸è¥¿ï¼å®ä¼æ´¾ä¸å¤§ç¨åºçã

[ç¤ºä¾](https://codepen.io/x-cold/pen/EzxMPw)

```jsx
function TextInputWithFocusButton() {
  const inputEl = useRef(null)
  const onButtonClick = () => {
    // `current` points to the mounted text input element
    inputEl.current.focus()
  }
  return (
    <>
      <input ref={inputEl} type="text" />
      <button onClick={onButtonClick}>Focus the input</button>
    </>
  )
}
```

## React ç¶æå±äº«æ¹æ¡

è¯´å°ç¶æå±äº«ï¼æç®ååç´æ¥çæ¹å¼å°±æ¯éè¿ props éçº§è¿è¡ç¶æçä¼ éï¼è¿ç§æ¹å¼è¦åäºç»ä»¶çç¶å­å³ç³»ï¼ä¸æ¦ç»ä»¶åµå¥ç»æåçååï¼å°±éè¦éæ°ç¼åä»£ç ï¼ç»´æ¤ææ¬éå¸¸æè´µãéçæ¶é´çæ¨ç§»ï¼å®æ¹æ¨åºäºåç§æ¹æ¡æ¥è§£å³ç¶æå±äº«åä»£ç å¤ç¨çé®é¢ã

### Mixins

![img](https://cdn.nlark.com/yuque/0/2019/png/103147/1557132050699-0f447719-f393-477a-9aa3-8d792ca5cd5f.png)

React ä¸­ï¼åªæéè¿ createClass åå»ºçç»ä»¶æè½ä½¿ç¨ mixinsãè¿ç§é«è¦åï¼ä¾èµé¾ä»¥æ§å¶ï¼å¤æåº¦é«çæ¹å¼éç ES6 çæµªæ½®éæ¸æ·¡åºäºåå²èå°ã

### HOC

é«é¶ç»ä»¶æºäºå½æ°å¼ç¼ç¨ï¼ç±äº React ä¸­çç»ä»¶ä¹å¯ä»¥è§ä¸ºå½æ°ï¼ç±»ï¼ï¼å æ­¤å¤©çå°±å¯ä»¥éè¿ HOC çæ¹å¼æ¥å®ç°ä»£ç å¤ç¨ãå¯ä»¥éè¿å±æ§ä»£çåååç»§æ¿æ¥å®ç°ï¼HOC å¯ä»¥å¾æ¹ä¾¿çææ§æ¸²æçç»æï¼ä¹å¯ä»¥å¯¹ç»ä»¶ç props / state è¿è¡æä½ï¼ä»èå¯ä»¥å¾æ¹ä¾¿çè¿è¡å¤æçä»£ç é»è¾å¤ç¨ã

```jsx
import React from "react"
import PropTypes from "prop-types"

// å±æ§ä»£ç
class Show extends React.Component {
  static propTypes = {
    children: PropTypes.element,
    visible: PropTypes.bool,
  }

  render() {
    const { visible, children } = this.props
    return visible ? children : null
  }
}

// ååç»§æ¿
function Show2(WrappedComponent) {
  return class extends WrappedComponent {
    render() {
      if (this.props.visible === false) {
        return null
      } else {
        return super.render()
      }
    }
  }
}

function App() {
  return <Show visible={Math.random() > 0.5}>hello</Show>
}
```

Redux ä¸­çç¶æå¤ç¨æ¯ä¸ç§å¸åç HOC çå®ç°ï¼æä»¬å¯ä»¥éè¿ compose æ¥å°æ°æ®ç»è£å°ç®æ ç»ä»¶ä¸­ï¼å½ç¶ä½ ä¹å¯ä»¥éè¿è£é¥°å¨çæ¹å¼è¿è¡å¤çã

```jsx
import React from "react"
import { connect } from "react-redux"

// use decorator
@connect((state) => ({ name: state.user.name }))
class App extends React.Component {
  render() {
    return <div>hello, {this.props.name}</div>
  }
}

// use compose
connect((state) => ({ name: state.user.name }))(App)
```

### Render Props

æ¾èæè§ï¼renderProps å°±æ¯ä¸ç§å° render æ¹æ³ä½ä¸º props ä¼ éå°å­ç»ä»¶çæ¹æ¡ï¼ç¸æ¯ HOC çæ¹æ¡ï¼renderProps å¯ä»¥ä¿æ¤åæçç»ä»¶å±æ¬¡ç»æã

```jsx
import React from "react"
import ReactDOM from "react-dom"
import PropTypes from "prop-types"

// ä¸ HOC ä¸åï¼æä»¬å¯ä»¥ä½¿ç¨å·æ render prop çæ®éç»ä»¶æ¥å±äº«ä»£ç 
class Mouse extends React.Component {
  static propTypes = {
    render: PropTypes.func.isRequired,
  }

  state = { x: 0, y: 0 }

  handleMouseMove = (event) => {
    this.setState({
      x: event.clientX,
      y: event.clientY,
    })
  }

  render() {
    return (
      <div style={{ height: "100%" }} onMouseMove={this.handleMouseMove}>
        {this.props.render(this.state)}
      </div>
    )
  }
}

function App() {
  return (
    <div style={{ height: "100%" }}>
      <Mouse
        render={({ x, y }) => (
          // render prop ç»äºæä»¬æéè¦ç state æ¥æ¸²ææä»¬æ³è¦ç
          <h1>
            The mouse position is ({x}, {y})
          </h1>
        )}
      />
    </div>
  )
}

ReactDOM.render(<App />, document.getElementById("root"))
```

### Hooks

éè¿ç»å Hooks API å React åç½®ç Contextï¼ä»åé¢çç¤ºä¾å¯ä»¥çå°éè¿ Hook è®©ç»ä»¶ä¹é´çç¶æå±äº«æ´æ¸æ°åç®åã

## React Hooks è®¾è®¡çå¿µ

### åºæ¬åç

![img](https://cdn.nlark.com/yuque/0/2019/png/103147/1557141237856-51f92576-f6f5-4dc3-a38f-9ef3fc841590.png)

```jsx
function FunctionalComponent() {
  const [state1, setState1] = useState(1)
  const [state2, setState2] = useState(2)
  const [state3, setState3] = useState(3)
}
```

![img](https://cdn.nlark.com/yuque/0/2019/png/103147/1557141338783-bb968286-9762-4a3a-8bc0-4d52b717ae6b.png)

```javascript
{
    memoizedState: 'foo',
    next: {
        memoizedState: 'bar',
        next: {
            memoizedState: 'bar',
            next: null
        }
    }
}
```

### å½æ°å¼è´¯å½»å°åº

#### capture props

å½æ°ç»ä»¶å¤©çå°±æ¯æ¯æ props çï¼åºæ¬ç¨æ³ä¸å class ç»ä»¶æ²¡æå¤ªå¤§çå·®å«ãéè¦æ³¨æçä¸¤ä¸ªåºå«æ¯ï¼

* class ç»ä»¶ props æè½½å¨ this ä¸ä¸æä¸­ï¼èå½æ°å¼ç»ä»¶éè¿å½¢åä¼ å¥ï¼
* ç±äºæè½½ä½ç½®çå·®å¼ï¼class ç»ä»¶ä¸­å¦æ this åçäºååï¼é£ä¹ this.props ä¹ä¼éä¹æ¹åï¼èå¨å½æ°ç»ä»¶é props å§ç»æ¯ä¸å¯åçï¼å æ­¤éµå® capture value ååï¼å³è·åçå¼å§ç»æ¯æä¸æ¶å»çï¼ï¼Hooks ä¹éµå¾ªè¿ä¸ªååã

éè¿ä¸ä¸ª[ç¤ºä¾](https://codesandbox.io/s/pjqnl16lm7)æ¥çè§£ä¸ä¸ capture valueï¼æä»¬å¯ä»¥éè¿ useRef æ¥è§é¿ capture valueï¼å ä¸º useRef æ¯å¯åçã

#### state

|          | class ç»ä»¶                                       | å½æ°ç»ä»¶                                                                                           |
| -------- | ------------------------------------------------ | -------------------------------------------------------------------------------------------------- |
| åå»ºç¶æ | this.state = {}                                  | useState, useReducer                                                                               |
| ä¿®æ¹ç¶æ | this.setState()                                  | set function                                                                                       |
| æ´æ°æºå¶ | å¼æ­¥æ´æ°ï¼å¤æ¬¡ä¿®æ¹åå¹¶å°ä¸ä¸ä¸ªç¶æï¼äº§çä¸ä¸ªå¯æ¬ | åæ­¥æ´æ°ï¼ç´æ¥ä¿®æ¹ä¸ºç®æ ç¶æ                                                                       |
| ç¶æç®¡ç | ä¸ä¸ª state éä¸­å¼ç®¡çå¤ä¸ªç¶æ                    | å¤ä¸ª stateï¼å¯ä»¥éè¿ useReducer è¿è¡ç¶æåå¹¶ï¼æå¨ï¼                                               |
| æ§è½     | é«                                               | å¦æ useState åå§åç¶æéè¦éè¿éå¸¸å¤æçè®¡ç®å¾å°ï¼è¯·ä½¿ç¨å½æ°çå£°ææ¹å¼ï¼å¦åæ¯æ¬¡æ¸²æé½ä¼éå¤æ§è¡ |
|          |                                                  |                                                                                                    |

#### çå½å¨æ

* componentDidMount / componentDidUpdate / componentWillUnMount

useEffect å¨æ¯ä¸æ¬¡æ¸²æé½ä¼è¢«è°ç¨ï¼ç¨å¾®åè£ä¸ä¸å°±å¯ä»¥ä½ä¸ºè¿äºçå½å¨æä½¿ç¨ï¼

* shouldComponentUpdate

éå¸¸æä»¬ä¼åç»ä»¶æ§è½æ¶ï¼ä¼ä¼åéç¨çº¯ç»ä»¶çæ¹å¼æ¥åå°åä¸ªç»ä»¶çæ¸²ææ¬¡æ°ã

```jsx
class Button extends React.PureComponent {}
```

React Hooks ä¸­å¯ä»¥éç¨ useMemo ä»£æ¿ï¼å¯ä»¥å®ç°ä»å¨æäºæ°æ®ååæ¶éæ°æ¸²æç»ä»¶ï¼ç­åäºèªå¸¦äº shallowEqual ç shouldComponentUpdateã

#### å¼ºå¶æ¸²æ forceUpdate

ç±äºé»è®¤æåµä¸ï¼æ¯ä¸æ¬¡ä¿®æ¹ç¶æé½ä¼é æéæ°æ¸²æï¼å¯ä»¥éè¿ä¸ä¸ªä¸ä½¿ç¨ç set å½æ°æ¥å½æ forceUpdateã

```javascript
const forceUpdate = () => useState(0)[1]
```

### å®ç°åç

## åºäº Hooksï¼å¢å¼º Hooks

### æ¥ä¸å¥ç»åæ³å§ï¼

ç±äºæ¯ä¸ä¸ª Hooks API é½æ¯çº¯å½æ°çæ¦å¿µï¼ä½¿ç¨æ¶æ´å³æ³¨è¾å¥ (input) åè¾åº (output)ï¼å æ­¤å¯ä»¥æ´å¥½çéè¿ç»è£å½æ°çæ¹å¼ï¼å¯¹ä¸åç¹æ§çåºç¡ Hooks API è¿è¡ç»åï¼åé æ¥ææ°ç¹æ§ç Hooksã

* useState ç»´æ¤ç»ä»¶ç¶æ
* useEffect å¤çå¯ä½ç¨

* useContext çå¬ provider æ´æ°åå

### useDidMount

```jsx
import { useEffect } from "react"

const useDidMount = (fn) => useEffect(() => fn && fn(), [])

export default useDidMount
```

###

### useDidUpdate

```jsx
import { useEffect, useRef } from "react"

const useDidUpdate = (fn, conditions) => {
  const didMoutRef = useRef(false)
  useEffect(() => {
    if (!didMoutRef.current) {
      didMoutRef.current = true
      return
    }
    // Cleanup effects when fn returns a function
    return fn && fn()
  }, conditions)
}

export default useDidUpdate
```

### useWillUnmount

å¨è®²å° useEffect æ¶å·²ç»æåè¿ï¼å¶åè®¸è¿åä¸ä¸ª cleanup å½æ°ï¼ç»ä»¶å¨åæ¶æè½½æ¶å°ä¼æ§è¡è¯¥ cleanup å½æ°ï¼å æ­¤ useWillUnmount ä¹è½è½»æ¾å®ç°~

```javascript
import {
    useEffect
} from "react"

const useWillUnmount = (fn) => useEffect(() => () => fn && fn(), [])

export default useWillUnmount
```

### useHover

[ç¤ºä¾](https://codepen.io/x-cold/pen/joOXxK)

```jsx
// lib/onHover.js
import { useState } from "react"

const useHover = () => {
  const [hovered, set] = useState(false)
  return {
    hovered,
    bind: {
      onMouseEnter: () => set(true),
      onMouseLeave: () => set(false),
    },
  }
}

export default useHover
```

```jsx
import { useHover } from "./lib/onHover.js"

function Hover() {
  const { hovered, bind } = useHover()
  return (
    <div>
      <div {...bind}>
        hovered:
        {String(hovered)}
      </div>
    </div>
  )
}
```

### useField

[ç¤ºä¾](https://codepen.io/x-cold/pen/rgNPNB)

```jsx
// lib/useField.js

import { useState } from "react"

const useField = (initial) => {
  const [value, set] = useState(initial)

  return {
    value,
    set,
    reset: () => set(initial),
    bind: {
      value,
      onChange: (e) => set(e.target.value),
    },
  }
}

export default useField
```

```jsx
import { useField } from 'lib/useField';

function Input {
  const { value, bind } = useField('Type Here...');

  return (
    <div>
      input text:
      {value}
      <input type="text" {...bind} />
    </div>
  );
}

function Select() {
  const { value, bind } = useField('apple')
  return (
    <div>
      selected:
      {value}
      <select {...bind}>
        <option value="apple">apple</option>
        <option value="orange">orange</option>
      </select>
    </div>
  );
}
```

## æ³¨æäºé¡¹

Hook å°±æ¯ JavaScript å½æ°ï¼ä½¿ç¨è§åï¼

* Hook çä½¿ç¨èå´ï¼å½æ°å¼ç React ç»ä»¶ä¸­ãèªå®ä¹ç Hook å½æ°éï¼
* Hook å¿é¡»åå¨å½æ°çæå¤å±ï¼æ¯ä¸æ¬¡ useState é½ä¼æ¹åå¶ä¸æ  (cursor)ï¼React æ ¹æ®å¶é¡ºåºæ¥æ´æ°ç¶æï¼

* å°½ç®¡æ¯ä¸æ¬¡æ¸²æé½ä¼æ§è¡ Hook APIï¼ä½æ¯äº§ççç¶æ (state) å§ç»æ¯ä¸ä¸ªå¸¸éï¼ä½ç¨åå¨å½æ°åé¨ï¼ï¼

* åªè½å¨**å½æ°æå¤å±**è°ç¨ Hookãä¸è¦å¨å¾ªç¯ãæ¡ä»¶å¤æ­æèå­å½æ°ä¸­è°ç¨ã
* åªè½å¨ **React çå½æ°ç»ä»¶**ä¸­è°ç¨ Hookãä¸è¦å¨å¶ä» JavaScript å½æ°ä¸­è°ç¨ãï¼è¿æä¸ä¸ªå°æ¹å¯ä»¥è°ç¨ Hook ââ å°±æ¯èªå®ä¹ç Hook ä¸­ãï¼

## ç»è¯­

React Hooks æä¾ä¸ºç¶æç®¡çæä¾äºæ°çå¯è½æ§ï¼å°½ç®¡æä»¬å¯è½éè¦é¢å¤å»ç»´æ¤ä¸äºåé¨çç¶æï¼ä½æ¯å¯ä»¥é¿åéè¿ renderProps / HOC ç­å¤æçæ¹å¼æ¥å¤çç¶æç®¡ççé®é¢ãHooks å¸¦æ¥çå¥½å¤å¦ä¸ï¼

* æ´ç»ç²åº¦çä»£ç å¤ç¨ï¼å¹¶ä¸ä¸ä¼äº§çè¿å¤çå¯ä½ç¨
* å½æ°å¼ç¼ç¨é£æ ¼ï¼ä»£ç æ´ç®æ´ï¼åæ¶éä½äºä½¿ç¨åçè§£é¨æ§

* åå°ç»ä»¶åµå¥å±æ°
* ç»ä»¶æ°æ®æµåæ´æ¸æ°

äºå®ä¸ï¼éè¿å®å¶åç§åºæ¯ä¸çèªå®ä¹ Hooksï¼è½è®©æä»¬çåºç¨ç¨åºæ´æ¹ä¾¿åç®æ´ï¼ç»ä»¶çå±æ¬¡ç»æä¹è½ä¿è¯å®å¥½ï¼è¿æå¦æ­¤ä»¤äººææ¦çå½æ°å¼ç¼ç¨é£æ ¼ï¼Hooks å¨ React 16.8.0 çæ¬å·²ç»æ­£å¼åå¸ç¨³å®çæ¬ï¼ç°å¨å¼å§ç¨èµ·æ¥å§ï¼ï¼ï¼
