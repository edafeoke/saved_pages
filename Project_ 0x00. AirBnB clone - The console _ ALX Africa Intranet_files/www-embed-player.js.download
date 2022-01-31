(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
'use strict';var m;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ca(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var da=ca(this);function q(a,b){if(b)a:{var c=da;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
q("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.h=f;ba(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d="jscomp_symbol_"+(1E9*Math.random()>>>0)+"_",e=0;return b});
q("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=da[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return fa(aa(this))}})}return a});
function fa(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function t(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];return b?b.call(a):{next:aa(a)}}
function ha(a){if(!(a instanceof Array)){a=t(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
var ia="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},ja=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if("undefined"!=typeof Reflect&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){void 0===e&&(e=c);
e=ia(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),ka;
if("function"==typeof Object.setPrototypeOf)ka=Object.setPrototypeOf;else{var la;a:{var ma={a:!0},na={};try{na.__proto__=ma;la=na.a;break a}catch(a){}la=!1}ka=la?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var oa=ka;
function v(a,b){a.prototype=ia(b.prototype);a.prototype.constructor=a;if(oa)oa(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.U=b.prototype}
function qa(){this.F=!1;this.l=null;this.i=void 0;this.h=1;this.A=this.m=0;this.C=this.j=null}
function ra(a){if(a.F)throw new TypeError("Generator is already running");a.F=!0}
qa.prototype.u=function(a){this.i=a};
function sa(a,b){a.j={kb:b,pb:!0};a.h=a.m||a.A}
qa.prototype.return=function(a){this.j={return:a};this.h=this.A};
function w(a,b,c){a.h=c;return{value:b}}
qa.prototype.o=function(a){this.h=a};
function ta(a,b,c){a.m=b;void 0!=c&&(a.A=c)}
function ua(a,b){a.h=b;a.m=0}
function va(a){a.m=0;var b=a.j.kb;a.j=null;return b}
function wa(a){a.C=[a.j];a.m=0;a.A=0}
function xa(a){var b=a.C.splice(0)[0];(b=a.j=a.j||b)?b.pb?a.h=a.m||a.A:void 0!=b.o&&a.A<b.o?(a.h=b.o,a.j=null):a.h=a.A:a.h=0}
function ya(a){this.h=new qa;this.i=a}
function za(a,b){ra(a.h);var c=a.h.l;if(c)return Aa(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return Ba(a)}
function Aa(a,b,c,d){try{var e=b.call(a.h.l,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.F=!1,e;var f=e.value}catch(g){return a.h.l=null,sa(a.h,g),Ba(a)}a.h.l=null;d.call(a.h,f);return Ba(a)}
function Ba(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.F=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,sa(a.h,c)}a.h.F=!1;if(a.h.j){b=a.h.j;a.h.j=null;if(b.pb)throw b.kb;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Ca(a){this.next=function(b){ra(a.h);a.h.l?b=Aa(a,a.h.l.next,b,a.h.u):(a.h.u(b),b=Ba(a));return b};
this.throw=function(b){ra(a.h);a.h.l?b=Aa(a,a.h.l["throw"],b,a.h.u):(sa(a.h,b),b=Ba(a));return b};
this.return=function(b){return za(a,b)};
this[Symbol.iterator]=function(){return this}}
function Da(a){function b(d){return a.next(d)}
function c(d){return a.throw(d)}
return new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}
f(a.next())})}
function x(a){return Da(new Ca(new ya(a)))}
function Ea(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b}
q("Reflect",function(a){return a?a:{}});
q("Reflect.construct",function(){return ja});
q("Reflect.setPrototypeOf",function(a){return a?a:oa?function(b,c){try{return oa(b,c),!0}catch(d){return!1}}:null});
q("Promise",function(a){function b(g){this.h=0;this.j=void 0;this.i=[];this.F=!1;var h=this.l();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(null==this.h){this.h=[];var h=this;this.j(function(){h.A()})}this.h.push(g)};
var e=da.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.A=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.l(l)}}}this.h=null};
c.prototype.l=function(g){this.j(function(){throw g;})};
b.prototype.l=function(){function g(l){return function(n){k||(k=!0,l.call(h,n))}}
var h=this,k=!1;return{resolve:g(this.P),reject:g(this.A)}};
b.prototype.P=function(g){if(g===this)this.A(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.aa(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.K(g):this.m(g)}};
b.prototype.K=function(g){var h=void 0;try{h=g.then}catch(k){this.A(k);return}"function"==typeof h?this.na(h,g):this.m(g)};
b.prototype.A=function(g){this.u(2,g)};
b.prototype.m=function(g){this.u(1,g)};
b.prototype.u=function(g,h){if(0!=this.h)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.h);this.h=g;this.j=h;2===this.h&&this.T();this.C()};
b.prototype.T=function(){var g=this;e(function(){if(g.J()){var h=da.console;"undefined"!==typeof h&&h.error(g.j)}},1)};
b.prototype.J=function(){if(this.F)return!1;var g=da.CustomEvent,h=da.Event,k=da.dispatchEvent;if("undefined"===typeof k)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=da.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.j;return k(g)};
b.prototype.C=function(){if(null!=this.i){for(var g=0;g<this.i.length;++g)f.i(this.i[g]);this.i=null}};
var f=new c;b.prototype.aa=function(g){var h=this.l();g.Ba(h.resolve,h.reject)};
b.prototype.na=function(g,h){var k=this.l();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(u,r){return"function"==typeof u?function(z){try{l(u(z))}catch(A){n(A)}}:r}
var l,n,p=new b(function(u,r){l=u;n=r});
this.Ba(k(g,l),k(h,n));return p};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.Ba=function(g,h){function k(){switch(l.h){case 1:g(l.j);break;case 2:h(l.j);break;default:throw Error("Unexpected state: "+l.h);}}
var l=this;null==this.i?f.i(k):this.i.push(k);this.F=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=t(g),n=l.next();!n.done;n=l.next())d(n.value).Ba(h,k)})};
b.all=function(g){var h=t(g),k=h.next();return k.done?d([]):new b(function(l,n){function p(z){return function(A){u[z]=A;r--;0==r&&l(u)}}
var u=[],r=0;do u.push(void 0),r++,d(k.value).Ba(p(u.length-1),n),k=h.next();while(!k.done)})};
return b});
function Fa(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
q("WeakMap",function(a){function b(k){this.h=(h+=Math.random()+1).toString();if(k){k=t(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return"object"===l&&null!==k||"function"===l}
function e(k){if(!Fa(k,g)){var l=new c;ba(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(n){if(n instanceof c)return n;Object.isExtensible(n)&&e(n);return l(n)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),n=new a([[k,2],[l,3]]);if(2!=n.get(k)||3!=n.get(l))return!1;n.delete(k);n.set(l,4);return!n.has(k)&&4==n.get(l)}catch(p){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!Fa(k,g))throw Error("WeakMap key fail: "+k);k[g][this.h]=l;return this};
b.prototype.get=function(k){return d(k)&&Fa(k,g)?k[g][this.h]:void 0};
b.prototype.has=function(k){return d(k)&&Fa(k,g)&&Fa(k[g],this.h)};
b.prototype.delete=function(k){return d(k)&&Fa(k,g)&&Fa(k[g],this.h)?delete k[g][this.h]:!1};
return b});
q("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h.h;return fa(function(){if(l){for(;l.head!=h.h;)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;"object"==l||"function"==l?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var n=h.data_[l];if(n&&Fa(h.data_,l))for(h=0;h<n.length;h++){var p=n[h];if(k!==k&&p.key!==p.key||k===p.key)return{id:l,list:n,index:h,entry:p}}return{id:l,list:n,index:-1,entry:void 0}}
function e(h){this.data_={};this.h=b();this.size=0;if(h){h=t(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(t([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var l=k.entries(),n=l.next();if(n.done||n.value[0]!=h||"s"!=n.value[1])return!1;n=l.next();return n.done||4!=n.value[0].x||"t"!=n.value[1]||!l.next().done?!1:!0}catch(p){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=0===h?0:h;var l=d(this,h);l.list||(l.list=this.data_[l.id]=[]);l.entry?l.entry.value=k:(l.entry={next:this.h,previous:this.h.previous,head:this.h,key:h,value:k},l.list.push(l.entry),this.h.previous.next=l.entry,this.h.previous=l.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this.data_[h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this.data_={};this.h=this.h.previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var l=this.entries(),n;!(n=l.next()).done;)n=n.value,h.call(k,n[1],n[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
function Ga(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
q("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ga(this,b,"endsWith");b+="";void 0===c&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;0<e&&0<c;)if(d[--c]!=b[--e])return!1;return 0>=e}});
q("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
q("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ga(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
function Ha(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
q("Array.prototype.entries",function(a){return a?a:function(){return Ha(this,function(b,c){return[b,c]})}});
q("Object.setPrototypeOf",function(a){return a||oa});
var Ja="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)Fa(d,e)&&(a[e]=d[e])}return a};
q("Object.assign",function(a){return a||Ja});
q("Set",function(a){function b(c){this.h=new Map;if(c){c=t(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(t([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
q("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)Fa(b,d)&&c.push([d,b[d]]);return c}});
q("Array.prototype.keys",function(a){return a?a:function(){return Ha(this,function(b){return b})}});
q("Array.prototype.values",function(a){return a?a:function(){return Ha(this,function(b,c){return c})}});
q("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
q("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
q("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==Ga(this,b,"includes").indexOf(b,c||0)}});
q("Array.from",function(a){return a?a:function(b,c,d){c=null!=c?c:function(h){return h};
var e=[],f="undefined"!=typeof Symbol&&Symbol.iterator&&b[Symbol.iterator];if("function"==typeof f){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
q("Number.isNaN",function(a){return a?a:function(b){return"number"===typeof b&&isNaN(b)}});
q("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
q("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)Fa(b,d)&&c.push(b[d]);return c}});
var y=this||self;function B(a,b,c){a=a.split(".");c=c||y;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function C(a,b){a=a.split(".");b=b||y;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b}
function Ka(){}
function La(a){a.ka=void 0;a.getInstance=function(){return a.ka?a.ka:a.ka=new a}}
function Ma(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function Na(a){var b=Ma(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function Oa(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Pa(a){return Object.prototype.hasOwnProperty.call(a,Qa)&&a[Qa]||(a[Qa]=++Ra)}
var Qa="closure_uid_"+(1E9*Math.random()>>>0),Ra=0;function Sa(a,b,c){return a.call.apply(a.bind,arguments)}
function Ua(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Va(a,b,c){Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?Va=Sa:Va=Ua;return Va.apply(null,arguments)}
function Wa(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function Xa(a,b){B(a,b,void 0)}
function D(a,b){function c(){}
c.prototype=b.prototype;a.U=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.kn=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function Ya(a){return a}
;function Za(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,Za);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));void 0!==b&&(this.Eb=b)}
D(Za,Error);Za.prototype.name="CustomError";function $a(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.j=!b&&/[?&]ae=1(&|$)/.test(a);this.l=!b&&/[?&]ae=2(&|$)/.test(a);if((this.h=/[?&]adurl=([^&]*)/.exec(a))&&this.h[1]){try{var c=decodeURIComponent(this.h[1])}catch(d){c=null}this.i=c}}
;function ab(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var bb=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},E=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},cb=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f="string"===typeof a?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},db=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e="string"===typeof a?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},eb=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
E(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function fb(a,b){a:{for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return 0>b?null:"string"===typeof a?a.charAt(b):a[b]}
function gb(a,b){b=bb(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c}
function hb(a){var b=a.length;if(0<b){for(var c=Array(b),d=0;d<b;d++)c[d]=a[d];return c}return[]}
function ib(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Na(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function jb(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function kb(a){var b=lb,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function mb(a){for(var b in a)return!1;return!0}
function nb(a,b){if(null!==a&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function ob(){var a=F("PLAYER_VARS",{});return null!==a&&"privembed"in a?a.privembed:!1}
function pb(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function qb(a){var b={},c;for(c in a)b[c]=a[c];return b}
function rb(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();if("undefined"!==typeof Map&&a instanceof Map)return new Map(a);if("undefined"!==typeof Set&&a instanceof Set)return new Set(a);var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=rb(a[c]);return b}
var sb="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function tb(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<sb.length;f++)c=sb[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var ub;function vb(){if(void 0===ub){var a=null,b=y.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:Ya,createScript:Ya,createScriptURL:Ya})}catch(c){y.console&&y.console.error(c.message)}ub=a}else ub=a}return ub}
;function wb(a,b){this.h=a===xb&&b||""}
wb.prototype.ea=!0;wb.prototype.da=function(){return this.h};
function yb(a){return new wb(xb,a)}
var xb={};yb("");var zb={};function Ab(a){this.h=zb===zb?a:"";this.ea=!0}
Ab.prototype.da=function(){return this.h.toString()};
Ab.prototype.toString=function(){return this.h.toString()};function Bb(a,b){this.h=b===Cb?a:""}
m=Bb.prototype;m.ea=!0;m.da=function(){return this.h.toString()};
m.Ra=!0;m.Na=function(){return 1};
m.toString=function(){return this.h+""};
function Db(a){if(a instanceof Bb&&a.constructor===Bb)return a.h;Ma(a);return"type_error:TrustedResourceUrl"}
var Cb={};function Eb(a){var b=vb();a=b?b.createScriptURL(a):a;return new Bb(a,Cb)}
;var Fb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]},Gb=/&/g,Hb=/</g,Ib=/>/g,Jb=/"/g,Kb=/'/g,Lb=/\x00/g,Mb=/[\x00&<>"']/;function Nb(a,b){this.h=b===Ob?a:""}
m=Nb.prototype;m.ea=!0;m.da=function(){return this.h.toString()};
m.Ra=!0;m.Na=function(){return 1};
m.toString=function(){return this.h.toString()};
function Pb(a){if(a instanceof Nb&&a.constructor===Nb)return a.h;Ma(a);return"type_error:SafeUrl"}
var Qb=RegExp('^(?:audio/(?:3gpp2|3gpp|aac|L16|midi|mp3|mp4|mpeg|oga|ogg|opus|x-m4a|x-matroska|x-wav|wav|webm)|font/\\w+|image/(?:bmp|gif|jpeg|jpg|png|tiff|webp|x-icon)|video/(?:mpeg|mp4|ogg|webm|quicktime|x-matroska))(?:;\\w+=(?:\\w+|"[\\w;,= ]+"))*$',"i"),Rb=/^data:(.*);base64,[a-z0-9+\/]+=*$/i,Sb=/^(?:(?:https?|mailto|ftp):|[^:/?#]*(?:[/?#]|$))/i,Ob={},Tb=new Nb("about:invalid#zClosurez",Ob);function Ub(){var a=y.navigator;return a&&(a=a.userAgent)?a:""}
function G(a){return-1!=Ub().indexOf(a)}
;function Vb(){return(G("Chrome")||G("CriOS"))&&!G("Edge")||G("Silk")}
;var Wb={};function Xb(a,b,c){this.h=c===Wb?a:"";this.i=b;this.ea=this.Ra=!0}
Xb.prototype.Na=function(){return this.i};
Xb.prototype.da=function(){return this.h.toString()};
Xb.prototype.toString=function(){return this.h.toString()};
function Yb(a,b){var c=vb();a=c?c.createHTML(a):a;return new Xb(a,b,Wb)}
;function Zb(a,b){b instanceof Nb||b instanceof Nb||(b="object"==typeof b&&b.ea?b.da():String(b),Sb.test(b)||(b="about:invalid#zClosurez"),b=new Nb(b,Ob));a.href=Pb(b)}
function $b(a,b){a.rel="stylesheet";a.href=Db(b).toString();(b=ac('style[nonce],link[rel="stylesheet"][nonce]',a.ownerDocument&&a.ownerDocument.defaultView))&&a.setAttribute("nonce",b)}
function bc(){return ac("script[nonce]",void 0)}
var cc=/^[\w+/_-]+[=]{0,2}$/;function ac(a,b){b=(b||y).document;return b.querySelector?(a=b.querySelector(a))&&(a=a.nonce||a.getAttribute("nonce"))&&cc.test(a)?a:"":""}
;function dc(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var ec=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function fc(a){return a?decodeURI(a):a}
function gc(a){return fc(a.match(ec)[3]||null)}
function hc(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)hc(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function ic(a){var b=[],c;for(c in a)hc(c,a[c],b);return b.join("&")}
function jc(a,b){b=ic(b);if(b){var c=a.indexOf("#");0>c&&(c=a.length);var d=a.indexOf("?");if(0>d||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.substr(0,d),e,a.substr(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;b=a[0]+(a[1]?"?"+a[1]:"")+a[2]}else b=a;return b}
var kc=/#|$/;function lc(){return G("iPhone")&&!G("iPod")&&!G("iPad")}
;function mc(a){mc[" "](a);return a}
mc[" "]=Ka;var nc=G("Opera"),oc=G("Trident")||G("MSIE"),pc=G("Edge"),qc=G("Gecko")&&!(-1!=Ub().toLowerCase().indexOf("webkit")&&!G("Edge"))&&!(G("Trident")||G("MSIE"))&&!G("Edge"),rc=-1!=Ub().toLowerCase().indexOf("webkit")&&!G("Edge"),sc=G("Android");function tc(){var a=y.document;return a?a.documentMode:void 0}
var uc;a:{var vc="",wc=function(){var a=Ub();if(qc)return/rv:([^\);]+)(\)|;)/.exec(a);if(pc)return/Edge\/([\d\.]+)/.exec(a);if(oc)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(rc)return/WebKit\/(\S+)/.exec(a);if(nc)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
wc&&(vc=wc?wc[1]:"");if(oc){var xc=tc();if(null!=xc&&xc>parseFloat(vc)){uc=String(xc);break a}}uc=vc}var yc=uc,zc;if(y.document&&oc){var Ac=tc();zc=Ac?Ac:parseInt(yc,10)||void 0}else zc=void 0;var Bc=zc;var Cc=lc()||G("iPod"),Dc=G("iPad");!G("Android")||Vb();Vb();var Ec=G("Safari")&&!(Vb()||G("Coast")||G("Opera")||G("Edge")||G("Edg/")||G("OPR")||G("Firefox")||G("FxiOS")||G("Silk")||G("Android"))&&!(lc()||G("iPad")||G("iPod"));var Fc={},Gc=null;
function Hc(a,b){Na(a);void 0===b&&(b=0);if(!Gc){Gc={};for(var c="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),d=["+/=","+/","-_=","-_.","-_"],e=0;5>e;e++){var f=c.concat(d[e].split(""));Fc[e]=f;for(var g=0;g<f.length;g++){var h=f[g];void 0===Gc[h]&&(Gc[h]=g)}}}b=Fc[b];c=Array(Math.floor(a.length/3));d=b[64]||"";for(e=f=0;f<a.length-2;f+=3){var k=a[f],l=a[f+1];h=a[f+2];g=b[k>>2];k=b[(k&3)<<4|l>>4];l=b[(l&15)<<2|h>>6];h=b[h&63];c[e++]=""+g+k+l+h}g=0;h=d;switch(a.length-
f){case 2:g=a[f+1],h=b[(g&15)<<2]||d;case 1:a=a[f],c[e]=""+b[a>>2]+b[(a&3)<<4|g>>4]+h+d}return c.join("")}
;var Ic="function"===typeof Uint8Array;var Jc="function"===typeof Symbol&&"symbol"===typeof Symbol()?Symbol(void 0):void 0;function Kc(a){Object.isFrozen(a)||(Jc?a[Jc]|=1:void 0!==a.h?a.h|=1:Object.defineProperties(a,{h:{value:1,configurable:!0,writable:!0,enumerable:!1}}));return a}
;function Lc(a){return null!==a&&"object"===typeof a&&a.constructor===Object}
var Mc;function Nc(a){switch(typeof a){case "number":return isFinite(a)?a:String(a);case "object":if(Ic&&null!=a&&a instanceof Uint8Array)return Hc(a)}return a}
;function Oc(a,b){if(null!=a)return Array.isArray(a)||Lc(a)?Qc(a,b):b(a)}
function Qc(a,b){if(Array.isArray(a)){for(var c=Array(a.length),d=0;d<a.length;d++)c[d]=Oc(a[d],b);if(Array.isArray(a)){var e;Jc?e=a[Jc]:e=a.h;a=!!((null==e?0:e)&1)}else a=!1;a&&Kc(c);return c}e={};for(c in a)e[c]=Oc(a[c],b);return e}
function Rc(a){a=Nc(a);return Array.isArray(a)?Qc(a,Rc):a}
function Sc(a){return Ic&&null!=a&&a instanceof Uint8Array?new Uint8Array(a):a}
;var Tc;function H(a,b,c){var d=Tc;Tc=null;a||(a=d);d=this.constructor.qn;a||(a=d?[d]:[]);this.j=(d?0:-1)-(this.constructor.pn||0);this.h=null;this.O=a;a:{d=this.O.length;a=d-1;if(d&&(d=this.O[a],Lc(d))){this.l=a-this.j;this.i=d;break a}void 0!==b&&-1<b?(this.l=Math.max(b,a+1-this.j),this.i=null):this.l=Number.MAX_VALUE}if(c)for(b=0;b<c.length;b++)a=c[b],a<this.l?(a+=this.j,(d=this.O[a])?Array.isArray(d)&&Kc(d):this.O[a]=Uc):(Vc(this),(d=this.i[a])?Array.isArray(d)&&Kc(d):this.i[a]=Uc)}
var Uc=Object.freeze(Kc([]));function Vc(a){var b=a.l+a.j;a.O[b]||(a.i=a.O[b]={})}
function Wc(a,b,c){return-1===b?null:b>=a.l?a.i?a.i[b]:void 0:(void 0===c?0:c)&&a.i&&a.i[b]?a.i[b]:a.O[b+a.j]}
function Xc(a,b,c){c=void 0===c?!1:c;var d=Wc(a,b,c);null==d&&(d=Uc);d===Uc&&(d=Kc(d.slice()),I(a,b,d,c));return d}
function I(a,b,c,d){(void 0===d?0:d)||b>=a.l?(Vc(a),a.i[b]=c):a.O[b+a.j]=c;return a}
function Yc(a,b){for(var c=0,d=0;d<b.length;d++){var e=b[d];null!=Wc(a,e)&&(0!==c&&I(a,c,void 0,!1),c=e)}return c}
function Zc(a,b,c,d,e){if(-1===c)return null;a.h||(a.h={});var f=a.h[c];if(f)return f;e=Wc(a,c,void 0===e?!1:e);if(null==e&&!d)return f;b=new b(e);return a.h[c]=b}
function $c(a,b,c,d){a.h||(a.h={});var e=a.h[c];if(!e){d=Xc(a,c,void 0===d?!1:d);e=[];for(var f=0;f<d.length;f++)e[f]=new b(d[f]);a.h[c]=e}return e}
function ad(a,b,c){var d;a.h||(a.h={});var e=c?c.O:c;a.h[b]=c;return I(a,b,e,void 0===d?!1:d)}
function bd(a,b,c,d){var e=$c(a,d,b);c=c?c:new d;a=Xc(a,b);e.push(c);a.push(c.O)}
H.prototype.toJSON=function(){var a=this.O;return Mc?a:Qc(a,Rc)};
function cd(a,b){return Nc(b)}
H.prototype.toString=function(){return this.O.toString()};
H.prototype.clone=function(){var a=this.constructor,b=Qc(this.O,Sc);Tc=b;a=new a(b);Tc=null;dd(a,this);return a};
function dd(a,b){b.A&&(a.A=b.A.slice());var c=b.h;if(c){b=b.i;for(var d in c){var e=c[d];if(e){var f=!(!b||!b[d]),g=+d;if(Array.isArray(e)){if(e.length)for(f=$c(a,e[0].constructor,g,f),g=0;g<Math.min(f.length,e.length);g++)dd(f[g],e[g])}else(f=Zc(a,e.constructor,g,void 0,f))&&dd(f,e)}}}}
;function ed(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function fd(a){this.i=!1;var b=a.program;a=a.globalName;var c=new ed;this.j=c.promise;this.l=t((0,y[a].a)(b,function(d,e){Promise.resolve().then(function(){c.resolve({Db:d,hc:e})})},!0)).next().value;
this.fc=c.promise.then(function(){})}
fd.prototype.snapshot=function(a){if(this.i)throw Error("Already disposed");return this.j.then(function(b){var c=b.Db;return new Promise(function(d){c(function(e){d(e)},[a.gb,
a.ic])})})};
fd.prototype.yb=function(a){if(this.i)throw Error("Already disposed");return this.l([a.gb,a.ic])};
fd.prototype.dispose=function(){this.i=!0;this.j.then(function(a){(a=a.hc)&&a()})};
fd.prototype.h=function(){return this.i};var gd=window;yb("csi.gstatic.com");yb("googleads.g.doubleclick.net");yb("pagead2.googlesyndication.com");yb("partner.googleadservices.com");yb("pubads.g.doubleclick.net");yb("securepubads.g.doubleclick.net");yb("tpc.googlesyndication.com");/*

 SPDX-License-Identifier: Apache-2.0
*/
var hd={};function id(){}
function jd(a){this.h=a}
v(jd,id);jd.prototype.toString=function(){return this.h};
var kd=new jd("about:invalid#zTSz",hd);function ld(a){this.isValid=a}
function md(a){return new ld(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var nd=[md("data"),md("http"),md("https"),md("mailto"),md("ftp"),new ld(function(a){return/^[^:]*([/?#]|$)/.test(a)})];function od(a){if(a instanceof id)if(a instanceof jd)a=a.h;else throw Error("");else a=Pb(a);return a}
;function pd(a,b){a.src=Db(b);var c;b=(a.ownerDocument&&a.ownerDocument.defaultView||window).document;var d=null===(c=b.querySelector)||void 0===c?void 0:c.call(b,"script[nonce]");(c=d?d.nonce||d.getAttribute("nonce")||"":"")&&a.setAttribute("nonce",c)}
;function qd(a,b){this.x=void 0!==a?a:0;this.y=void 0!==b?b:0}
m=qd.prototype;m.clone=function(){return new qd(this.x,this.y)};
m.equals=function(a){return a instanceof qd&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
m.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
m.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
m.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
m.scale=function(a,b){this.x*=a;this.y*="number"===typeof b?b:a;return this};function rd(a,b){this.width=a;this.height=b}
m=rd.prototype;m.clone=function(){return new rd(this.width,this.height)};
m.aspectRatio=function(){return this.width/this.height};
m.isEmpty=function(){return!(this.width*this.height)};
m.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
m.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
m.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
m.scale=function(a,b){this.width*=a;this.height*="number"===typeof b?b:a;return this};function sd(a){var b=document;return"string"===typeof a?b.getElementById(a):a}
function td(a,b){jb(b,function(c,d){c&&"object"==typeof c&&c.ea&&(c=c.da());"style"==d?a.style.cssText=c:"class"==d?a.className=c:"for"==d?a.htmlFor=c:ud.hasOwnProperty(d)?a.setAttribute(ud[d],c):0==d.lastIndexOf("aria-",0)||0==d.lastIndexOf("data-",0)?a.setAttribute(d,c):a[d]=c})}
var ud={cellpadding:"cellPadding",cellspacing:"cellSpacing",colspan:"colSpan",frameborder:"frameBorder",height:"height",maxlength:"maxLength",nonce:"nonce",role:"role",rowspan:"rowSpan",type:"type",usemap:"useMap",valign:"vAlign",width:"width"};function vd(a,b,c){var d=arguments,e=document,f=d[1],g=wd(e,String(d[0]));f&&("string"===typeof f?g.className=f:Array.isArray(f)?g.className=f.join(" "):td(g,f));2<d.length&&xd(e,g,d);return g}
function xd(a,b,c){function d(h){h&&b.appendChild("string"===typeof h?a.createTextNode(h):h)}
for(var e=2;e<c.length;e++){var f=c[e];if(!Na(f)||Oa(f)&&0<f.nodeType)d(f);else{a:{if(f&&"number"==typeof f.length){if(Oa(f)){var g="function"==typeof f.item||"string"==typeof f.item;break a}if("function"===typeof f){g="function"==typeof f.item;break a}}g=!1}E(g?hb(f):f,d)}}}
function wd(a,b){b=String(b);"application/xhtml+xml"===a.contentType&&(b=b.toLowerCase());return a.createElement(b)}
function yd(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;function zd(a){var b=Ad;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a.call(void 0,b[c],c,b)}
function Bd(){var a=[];zd(function(b){a.push(b)});
return a}
var Ad={yc:"allow-forms",zc:"allow-modals",Ac:"allow-orientation-lock",Bc:"allow-pointer-lock",Cc:"allow-popups",Dc:"allow-popups-to-escape-sandbox",Ec:"allow-presentation",Fc:"allow-same-origin",Gc:"allow-scripts",Hc:"allow-top-navigation",Ic:"allow-top-navigation-by-user-activation"},Cd=ab(function(){return Bd()});
function Dd(){var a=Ed(),b={};E(Cd(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function Ed(){var a=void 0===a?document:a;return a.createElement("iframe")}
;function Fd(a){"number"==typeof a&&(a=Math.round(a)+"px");return a}
;var Gd=(new Date).getTime();var Hd=new function(a,b){this.flag=a;this.defaultValue=void 0===b?!1:b}(1959);function Id(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if("http"!==c&&"https"!==c&&"chrome-extension"!==c&&"moz-extension"!==c&&"file"!==c&&"android-app"!==
c&&"chrome-search"!==c&&"chrome-untrusted"!==c&&"chrome"!==c&&"app"!==c&&"devtools"!==c)throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===c&&"80"!==e||"https"===c&&"443"!==e)a=":"+e}return c+"://"+b+a}
;function Jd(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;n=l=0}
function b(p){for(var u=g,r=0;64>r;r+=4)u[r/4]=p[r]<<24|p[r+1]<<16|p[r+2]<<8|p[r+3];for(r=16;80>r;r++)p=u[r-3]^u[r-8]^u[r-14]^u[r-16],u[r]=(p<<1|p>>>31)&4294967295;p=e[0];var z=e[1],A=e[2],J=e[3],R=e[4];for(r=0;80>r;r++){if(40>r)if(20>r){var S=J^z&(A^J);var U=1518500249}else S=z^A^J,U=1859775393;else 60>r?(S=z&A|J&(z|A),U=2400959708):(S=z^A^J,U=3395469782);S=((p<<5|p>>>27)&4294967295)+S+R+U+u[r]&4294967295;R=J;J=A;A=(z<<30|z>>>2)&4294967295;z=p;p=S}e[0]=e[0]+p&4294967295;e[1]=e[1]+z&4294967295;e[2]=
e[2]+A&4294967295;e[3]=e[3]+J&4294967295;e[4]=e[4]+R&4294967295}
function c(p,u){if("string"===typeof p){p=unescape(encodeURIComponent(p));for(var r=[],z=0,A=p.length;z<A;++z)r.push(p.charCodeAt(z));p=r}u||(u=p.length);r=0;if(0==l)for(;r+64<u;)b(p.slice(r,r+64)),r+=64,n+=64;for(;r<u;)if(f[l++]=p[r++],n++,64==l)for(l=0,b(f);r+64<u;)b(p.slice(r,r+64)),r+=64,n+=64}
function d(){var p=[],u=8*n;56>l?c(h,56-l):c(h,64-(l-56));for(var r=63;56<=r;r--)f[r]=u&255,u>>>=8;b(f);for(r=u=0;5>r;r++)for(var z=24;0<=z;z-=8)p[u++]=e[r]>>z&255;return p}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var l,n;a();return{reset:a,update:c,digest:d,Gb:function(){for(var p=d(),u="",r=0;r<p.length;r++)u+="0123456789ABCDEF".charAt(Math.floor(p[r]/16))+"0123456789ABCDEF".charAt(p[r]%16);return u}}}
;function Kd(a,b,c){var d=String(y.location.href);return d&&a&&b?[b,Ld(Id(d),a,c||null)].join(" "):null}
function Ld(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],E(d,function(h){e.push(h)}),Md(e.join(" "));
var f=[],g=[];E(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];E(d,function(h){e.push(h)});
a=Md(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function Md(a){var b=Jd();b.update(a);return b.Gb().toLowerCase()}
;var Nd={};function Od(a){this.h=a||{cookie:""}}
m=Od.prototype;m.isEnabled=function(){if(!y.navigator.cookieEnabled)return!1;if(!this.isEmpty())return!0;this.set("TESTCOOKIESENABLED","1",{Ua:60});if("1"!==this.get("TESTCOOKIESENABLED"))return!1;this.remove("TESTCOOKIESENABLED");return!0};
m.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.vn;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.Ua}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString();this.h.cookie=a+"="+b+c+g+h+d+(null!=e?";samesite="+
e:"")};
m.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=Fb(d[e]);if(0==f.lastIndexOf(c,0))return f.substr(c.length);if(f==a)return""}return b};
m.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{Ua:0,path:b,domain:c});return d};
m.isEmpty=function(){return!this.h.cookie};
m.clear=function(){for(var a=(this.h.cookie||"").split(";"),b=[],c=[],d,e,f=0;f<a.length;f++)e=Fb(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));for(a=b.length-1;0<=a;a--)this.remove(b[a])};
var Pd=new Od("undefined"==typeof document?null:document);function Qd(a){return!!Nd.FPA_SAMESITE_PHASE2_MOD||!(void 0===a||!a)}
function Rd(a){a=void 0===a?!1:a;var b=y.__SAPISID||y.__APISID||y.__3PSAPISID||y.__OVERRIDE_SID;Qd(a)&&(b=b||y.__1PSAPISID);if(b)return!0;var c=new Od(document);b=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID")||c.get("SID");Qd(a)&&(b=b||c.get("__Secure-1PAPISID"));return!!b}
function Sd(a,b,c,d){(a=y[a])||(a=(new Od(document)).get(b));return a?Kd(a,c,d):null}
function Td(a){var b=void 0===b?!1:b;var c=Id(String(y.location.href)),d=[];if(Rd(b)){c=0==c.indexOf("https:")||0==c.indexOf("chrome-extension:")||0==c.indexOf("moz-extension:");var e=c?y.__SAPISID:y.__APISID;e||(e=new Od(document),e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID"));(e=e?Kd(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e);c&&Qd(b)&&((b=Sd("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=Sd("__3PSAPISID","__Secure-3PAPISID","SAPISID3PHASH",a))&&d.push(a))}return 0==
d.length?null:d.join(" ")}
;function Ud(a){a&&"function"==typeof a.dispose&&a.dispose()}
;function Vd(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Na(d)?Vd.apply(null,d):Ud(d)}}
;function K(){this.F=this.F;this.A=this.A}
K.prototype.F=!1;K.prototype.h=function(){return this.F};
K.prototype.dispose=function(){this.F||(this.F=!0,this.G())};
function Wd(a,b){a.F?b():(a.A||(a.A=[]),a.A.push(b))}
K.prototype.G=function(){if(this.A)for(;this.A.length;)this.A.shift()()};function Xd(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
Xd.prototype.stopPropagation=function(){this.j=!0};
Xd.prototype.preventDefault=function(){this.defaultPrevented=!0};function Yd(a){var b=C("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||y.$googDebugFname||b}catch(g){e="Not available",c=!0}b=Zd(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,$d[c])c=$d[c];else{c=String(c);if(!$d[c]){var f=/function\s+([^\(]+)/m.exec(c);$d[c]=f?f[1]:"[Anonymous]"}c=$d[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return{message:a.message,name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:a.stack}}
function Zd(a,b){b||(b={});b[ae(a)]=!0;var c=a.stack||"";(a=a.Eb)&&!b[ae(a)]&&(c+="\nCaused by: ",a.stack&&0==a.stack.indexOf(a.toString())||(c+="string"===typeof a?a:a.message+"\n"),c+=Zd(a,b));return c}
function ae(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var $d={};var be=function(){if(!y.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{y.addEventListener("test",Ka,b),y.removeEventListener("test",Ka,b)}catch(c){}return a}();function ce(a,b){Xd.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
D(ce,Xd);var de={2:"touch",3:"pen",4:"mouse"};
ce.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;if(b=a.relatedTarget){if(qc){a:{try{mc(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:de[a.pointerType]||"";this.state=a.state;
this.i=a;a.defaultPrevented&&ce.U.preventDefault.call(this)};
ce.prototype.stopPropagation=function(){ce.U.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
ce.prototype.preventDefault=function(){ce.U.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var ee="closure_listenable_"+(1E6*Math.random()|0);var fe=0;function ge(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.Ea=e;this.key=++fe;this.va=this.Aa=!1}
function he(a){a.va=!0;a.listener=null;a.proxy=null;a.src=null;a.Ea=null}
;function ie(a){this.src=a;this.listeners={};this.h=0}
ie.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=je(a,b,d,e);-1<g?(b=a[g],c||(b.Aa=!1)):(b=new ge(b,this.src,f,!!d,e),b.Aa=c,a.push(b));return b};
ie.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=je(e,b,c,d);return-1<b?(he(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.h--),!0):!1};
function ke(a,b){var c=b.type;c in a.listeners&&gb(a.listeners[c],b)&&(he(b),0==a.listeners[c].length&&(delete a.listeners[c],a.h--))}
function je(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.va&&f.listener==b&&f.capture==!!c&&f.Ea==d)return e}return-1}
;var le="closure_lm_"+(1E6*Math.random()|0),me={},ne=0;function oe(a,b,c,d,e){if(d&&d.once)pe(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)oe(a,b[f],c,d,e);else c=qe(c),a&&a[ee]?a.V(b,c,Oa(d)?!!d.capture:!!d,e):re(a,b,c,!1,d,e)}
function re(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Oa(e)?!!e.capture:!!e,h=se(a);h||(a[le]=h=new ie(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=te();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)be||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(ue(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");ne++}}
function te(){function a(c){return b.call(a.src,a.listener,c)}
var b=ve;return a}
function pe(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)pe(a,b[f],c,d,e);else c=qe(c),a&&a[ee]?a.i.add(String(b),c,!0,Oa(d)?!!d.capture:!!d,e):re(a,b,c,!0,d,e)}
function we(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)we(a,b[f],c,d,e);else(d=Oa(d)?!!d.capture:!!d,c=qe(c),a&&a[ee])?a.i.remove(String(b),c,d,e):a&&(a=se(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=je(b,c,d,e)),(c=-1<a?b[a]:null)&&xe(c))}
function xe(a){if("number"!==typeof a&&a&&!a.va){var b=a.src;if(b&&b[ee])ke(b.i,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(ue(c),d):b.addListener&&b.removeListener&&b.removeListener(d);ne--;(c=se(b))?(ke(c,a),0==c.h&&(c.src=null,b[le]=null)):he(a)}}}
function ue(a){return a in me?me[a]:me[a]="on"+a}
function ve(a,b){if(a.va)a=!0;else{b=new ce(b,this);var c=a.listener,d=a.Ea||a.src;a.Aa&&xe(a);a=c.call(d,b)}return a}
function se(a){a=a[le];return a instanceof ie?a:null}
var ye="__closure_events_fn_"+(1E9*Math.random()>>>0);function qe(a){if("function"===typeof a)return a;a[ye]||(a[ye]=function(b){return a.handleEvent(b)});
return a[ye]}
;function ze(){K.call(this);this.i=new ie(this);this.T=this;this.J=null}
D(ze,K);ze.prototype[ee]=!0;ze.prototype.addEventListener=function(a,b,c,d){oe(this,a,b,c,d)};
ze.prototype.removeEventListener=function(a,b,c,d){we(this,a,b,c,d)};
function Ae(a,b){var c=a.J;if(c){var d=[];for(var e=1;c;c=c.J)d.push(c),++e}a=a.T;c=b.type||b;"string"===typeof b?b=new Xd(b,a):b instanceof Xd?b.target=b.target||a:(e=b,b=new Xd(c,a),tb(b,e));e=!0;if(d)for(var f=d.length-1;!b.j&&0<=f;f--){var g=b.h=d[f];e=Be(g,c,!0,b)&&e}b.j||(g=b.h=a,e=Be(g,c,!0,b)&&e,b.j||(e=Be(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=Be(g,c,!1,b)&&e}
ze.prototype.G=function(){ze.U.G.call(this);if(this.i){var a=this.i,b=0,c;for(c in a.listeners){for(var d=a.listeners[c],e=0;e<d.length;e++)++b,he(d[e]);delete a.listeners[c];a.h--}}this.J=null};
ze.prototype.V=function(a,b,c,d){return this.i.add(String(a),b,!1,c,d)};
function Be(a,b,c,d){b=a.i.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.va&&g.capture==c){var h=g.listener,k=g.Ea||g.src;g.Aa&&ke(a.i,g);e=!1!==h.call(k,d)&&e}}return e&&!d.defaultPrevented}
;function Ce(a){var b,c;ze.call(this);var d=this;this.C=this.l=0;this.S=null!==a&&void 0!==a?a:{M:function(e,f){return setTimeout(e,f)},
ca:clearTimeout};this.j=null!==(c=null===(b=window.navigator)||void 0===b?void 0:b.onLine)&&void 0!==c?c:!0;this.m=function(){return x(function(e){return w(e,De(d),0)})};
window.addEventListener("offline",this.m);window.addEventListener("online",this.m);this.C||Ee(this)}
v(Ce,ze);Ce.prototype.dispose=function(){window.removeEventListener("offline",this.m);window.removeEventListener("online",this.m);this.S.ca(this.C);delete Ce.h};
Ce.prototype.H=function(){return this.j};
function Ee(a){a.C=a.S.M(function(){var b;return x(function(c){if(1==c.h)return a.j?(null===(b=window.navigator)||void 0===b?0:b.onLine)?c.o(3):w(c,De(a),3):w(c,De(a),3);Ee(a);c.h=0})},3E4)}
function De(a,b){return a.u?a.u:a.u=new Promise(function(c){var d,e,f;return x(function(g){switch(g.h){case 1:return d=window.AbortController?new window.AbortController:void 0,e=null===d||void 0===d?void 0:d.signal,f=!1,ta(g,2,3),d&&(a.l=a.S.M(function(){d.abort()},b||2E4)),w(g,fetch("/generate_204",{method:"HEAD",
signal:e}),5);case 5:f=!0;case 3:wa(g);a.u=void 0;a.l&&(a.S.ca(a.l),a.l=0);f!==a.j&&(a.j=f,a.j?Ae(a,"networkstatus-online"):Ae(a,"networkstatus-offline"));c(f);xa(g);break;case 2:va(g),f=!1,g.o(3)}})})}
;var Fe={Tm:"WEB_DISPLAY_MODE_UNKNOWN",Pm:"WEB_DISPLAY_MODE_BROWSER",Rm:"WEB_DISPLAY_MODE_MINIMAL_UI",Sm:"WEB_DISPLAY_MODE_STANDALONE",Qm:"WEB_DISPLAY_MODE_FULLSCREEN"};function Ge(){this.data_=[];this.h=-1}
Ge.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&0===a%1&&this.data_[a]!=b&&(this.data_[a]=b,this.h=-1)};
Ge.prototype.get=function(a){return!!this.data_[a]};
function He(a){-1==a.h&&(a.h=eb(a.data_,function(b,c,d){return c?b+Math.pow(2,d):b},0));
return a.h}
;function Ie(){var a={};this.D=function(b,c){return null!=a[b]?a[b]:c}}
;function Je(a,b){this.j=a;this.l=b;this.i=0;this.h=null}
Je.prototype.get=function(){if(0<this.i){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function Ke(a,b){a.l(b);100>a.i&&(a.i++,b.next=a.h,a.h=b)}
;var Le;
function Me(){var a=y.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!G("Presto")&&(a=function(){var e=wd(document,"IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=Va(function(k){if(("*"==h||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!G("Trident")&&!G("MSIE")){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.fb;c.fb=null;e()}};
return function(e){d.next={fb:e};d=d.next;b.port2.postMessage(0)}}return function(e){y.setTimeout(e,0)}}
;function Ne(a){y.setTimeout(function(){throw a;},0)}
;function Oe(){this.i=this.h=null}
Oe.prototype.add=function(a,b){var c=Pe.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
Oe.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var Pe=new Je(function(){return new Qe},function(a){return a.reset()});
function Qe(){this.next=this.scope=this.h=null}
Qe.prototype.set=function(a,b){this.h=a;this.scope=b;this.next=null};
Qe.prototype.reset=function(){this.next=this.scope=this.h=null};function Re(a,b){Se||Te();Ue||(Se(),Ue=!0);Ve.add(a,b)}
var Se;function Te(){if(y.Promise&&y.Promise.resolve){var a=y.Promise.resolve(void 0);Se=function(){a.then(We)}}else Se=function(){var b=We;
"function"!==typeof y.setImmediate||y.Window&&y.Window.prototype&&!G("Edge")&&y.Window.prototype.setImmediate==y.setImmediate?(Le||(Le=Me()),Le(b)):y.setImmediate(b)}}
var Ue=!1,Ve=new Oe;function We(){for(var a;a=Ve.remove();){try{a.h.call(a.scope)}catch(b){Ne(b)}Ke(Pe,a)}Ue=!1}
;function Xe(a,b){this.h=a[y.Symbol.iterator]();this.i=b;this.j=0}
Xe.prototype[Symbol.iterator]=function(){return this};
Xe.prototype.next=function(){var a=this.h.next();return{value:a.done?void 0:this.i.call(void 0,a.value,this.j++),done:a.done}};
function Ye(a,b){return new Xe(a,b)}
;function Ze(){this.blockSize=-1}
;function $e(){this.blockSize=-1;this.blockSize=64;this.h=[];this.A=[];this.m=[];this.j=[];this.j[0]=128;for(var a=1;a<this.blockSize;++a)this.j[a]=0;this.l=this.i=0;this.reset()}
D($e,Ze);$e.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.l=this.i=0};
function af(a,b,c){c||(c=0);var d=a.m;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.h[0];c=a.h[1];var g=a.h[2],h=a.h[3],k=a.h[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var l=1518500249}else f=c^g^h,l=1859775393;else 60>e?(f=c&g|h&(c|g),l=2400959708):
(f=c^g^h,l=3395469782);f=(b<<5|b>>>27)+f+k+l+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+g&4294967295;a.h[3]=a.h[3]+h&4294967295;a.h[4]=a.h[4]+k&4294967295}
$e.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.A,f=this.i;d<b;){if(0==f)for(;d<=c;)af(this,a,d),d+=this.blockSize;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){af(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){af(this,e);f=0;break}}this.i=f;this.l+=b}};
$e.prototype.digest=function(){var a=[],b=8*this.l;56>this.i?this.update(this.j,56-this.i):this.update(this.j,this.blockSize-(this.i-56));for(var c=this.blockSize-1;56<=c;c--)this.A[c]=b&255,b/=256;af(this,this.A);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function bf(a){return"string"==typeof a.className?a.className:a.getAttribute&&a.getAttribute("class")||""}
function cf(a,b){"string"==typeof a.className?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function df(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:bf(a).match(/\S+/g)||[],b=0<=bb(a,b));return b}
function ef(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):df(a,"inverted-hdpi")&&cf(a,Array.prototype.filter.call(a.classList?a.classList:bf(a).match(/\S+/g)||[],function(b){return"inverted-hdpi"!=b}).join(" "))}
;var ff="StopIteration"in y?y.StopIteration:{message:"StopIteration",stack:""};function gf(){}
gf.prototype.W=function(){throw ff;};
gf.prototype.next=function(){return hf};
var hf={done:!0,value:void 0};function jf(a){return{value:a,done:!1}}
function kf(a){if(a.done)throw ff;return a.value}
gf.prototype.R=function(){return this};function lf(a){if(a instanceof mf||a instanceof nf||a instanceof of)return a;if("function"==typeof a.W)return new mf(function(){return pf(a)});
if("function"==typeof a[Symbol.iterator])return new mf(function(){return a[Symbol.iterator]()});
if("function"==typeof a.R)return new mf(function(){return pf(a.R())});
throw Error("Not an iterator or iterable.");}
function pf(a){if(!(a instanceof gf))return a;var b=!1;return{next:function(){for(var c;!b;)try{c=a.W();break}catch(d){if(d!==ff)throw d;b=!0}return{value:c,done:b}}}}
function mf(a){this.h=a}
mf.prototype.R=function(){return new nf(this.h())};
mf.prototype[Symbol.iterator]=function(){return new of(this.h())};
mf.prototype.i=function(){return new of(this.h())};
function nf(a){this.h=a}
v(nf,gf);nf.prototype.W=function(){var a=this.h.next();if(a.done)throw ff;return a.value};
nf.prototype.next=function(){return this.h.next()};
nf.prototype[Symbol.iterator]=function(){return new of(this.h)};
nf.prototype.i=function(){return new of(this.h)};
function of(a){mf.call(this,function(){return a});
this.j=a}
v(of,mf);of.prototype.next=function(){return this.j.next()};function qf(a,b){this.i={};this.h=[];this.ia=this.size=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof qf)for(c=rf(a),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
function rf(a){sf(a);return a.h.concat()}
m=qf.prototype;m.has=function(a){return tf(this.i,a)};
m.equals=function(a,b){if(this===a)return!0;if(this.size!=a.size)return!1;b=b||uf;sf(this);for(var c,d=0;c=this.h[d];d++)if(!b(this.get(c),a.get(c)))return!1;return!0};
function uf(a,b){return a===b}
m.isEmpty=function(){return 0==this.size};
m.clear=function(){this.i={};this.ia=this.size=this.h.length=0};
m.remove=function(a){return this.delete(a)};
m.delete=function(a){return tf(this.i,a)?(delete this.i[a],--this.size,this.ia++,this.h.length>2*this.size&&sf(this),!0):!1};
function sf(a){if(a.size!=a.h.length){for(var b=0,c=0;b<a.h.length;){var d=a.h[b];tf(a.i,d)&&(a.h[c++]=d);b++}a.h.length=c}if(a.size!=a.h.length){var e={};for(c=b=0;b<a.h.length;)d=a.h[b],tf(e,d)||(a.h[c++]=d,e[d]=1),b++;a.h.length=c}}
m.get=function(a,b){return tf(this.i,a)?this.i[a]:b};
m.set=function(a,b){tf(this.i,a)||(this.size+=1,this.h.push(a),this.ia++);this.i[a]=b};
m.forEach=function(a,b){for(var c=rf(this),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
m.clone=function(){return new qf(this)};
m.keys=function(){return lf(this.R(!0)).i()};
m.values=function(){return lf(this.R(!1)).i()};
m.entries=function(){var a=this;return Ye(this.keys(),function(b){return[b,a.get(b)]})};
m.R=function(a){sf(this);var b=0,c=this.ia,d=this,e=new gf;e.next=function(){if(c!=d.ia)throw Error("The map has changed since the iterator was created");if(b>=d.h.length)return hf;var g=d.h[b++];return jf(a?g:d.i[g])};
var f=e.next;e.W=function(){return kf(f.call(e))};
return e};
function tf(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
;function vf(a){wf();return Eb(a)}
var wf=Ka;function xf(a){var b=[];yf(new zf,a,b);return b.join("")}
function zf(){}
function yf(a,b,c){if(null==b)c.push("null");else{if("object"==typeof b){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),yf(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],"function"!=typeof f&&(c.push(e),Af(d,c),c.push(":"),yf(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":Af(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var Bf={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\x0B":"\\u000b"},Cf=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function Af(a,b){b.push('"',a.replace(Cf,function(c){var d=Bf[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).substr(1),Bf[c]=d);return d}),'"')}
;function Df(a){if(!a)return!1;try{return!!a.$goog_Thenable}catch(b){return!1}}
;function Ef(a){this.h=0;this.F=void 0;this.l=this.i=this.j=null;this.A=this.m=!1;if(a!=Ka)try{var b=this;a.call(void 0,function(c){Ff(b,2,c)},function(c){Ff(b,3,c)})}catch(c){Ff(this,3,c)}}
function Gf(){this.next=this.context=this.onRejected=this.i=this.h=null;this.j=!1}
Gf.prototype.reset=function(){this.context=this.onRejected=this.i=this.h=null;this.j=!1};
var Hf=new Je(function(){return new Gf},function(a){a.reset()});
function If(a,b,c){var d=Hf.get();d.i=a;d.onRejected=b;d.context=c;return d}
function Jf(a){return new Ef(function(b,c){c(a)})}
Ef.prototype.then=function(a,b,c){return Kf(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
Ef.prototype.$goog_Thenable=!0;function Lf(a,b){return Kf(a,null,b,void 0)}
Ef.prototype.cancel=function(a){if(0==this.h){var b=new Mf(a);Re(function(){Nf(this,b)},this)}};
function Nf(a,b){if(0==a.h)if(a.j){var c=a.j;if(c.i){for(var d=0,e=null,f=null,g=c.i;g&&(g.j||(d++,g.h==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.h&&1==d?Nf(c,b):(f?(d=f,d.next==c.l&&(c.l=d),d.next=d.next.next):Of(c),Pf(c,e,3,b)))}a.j=null}else Ff(a,3,b)}
function Qf(a,b){a.i||2!=a.h&&3!=a.h||Rf(a);a.l?a.l.next=b:a.i=b;a.l=b}
function Kf(a,b,c,d){var e=If(null,null,null);e.h=new Ef(function(f,g){e.i=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.onRejected=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof Mf?g(h):f(k)}catch(l){g(l)}}:g});
e.h.j=a;Qf(a,e);return e.h}
Ef.prototype.C=function(a){this.h=0;Ff(this,2,a)};
Ef.prototype.J=function(a){this.h=0;Ff(this,3,a)};
function Ff(a,b,c){if(0==a.h){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.h=1;a:{var d=c,e=a.C,f=a.J;if(d instanceof Ef){Qf(d,If(e||Ka,f||null,a));var g=!0}else if(Df(d))d.then(e,f,a),g=!0;else{if(Oa(d))try{var h=d.then;if("function"===typeof h){Sf(d,h,e,f,a);g=!0;break a}}catch(k){f.call(a,k);g=!0;break a}g=!1}}g||(a.F=c,a.h=b,a.j=null,Rf(a),3!=b||c instanceof Mf||Tf(a,c))}}
function Sf(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function Rf(a){a.m||(a.m=!0,Re(a.u,a))}
function Of(a){var b=null;a.i&&(b=a.i,a.i=b.next,b.next=null);a.i||(a.l=null);return b}
Ef.prototype.u=function(){for(var a;a=Of(this);)Pf(this,a,this.h,this.F);this.m=!1};
function Pf(a,b,c,d){if(3==c&&b.onRejected&&!b.j)for(;a&&a.A;a=a.j)a.A=!1;if(b.h)b.h.j=null,Uf(b,c,d);else try{b.j?b.i.call(b.context):Uf(b,c,d)}catch(e){Vf.call(null,e)}Ke(Hf,b)}
function Uf(a,b,c){2==b?a.i.call(a.context,c):a.onRejected&&a.onRejected.call(a.context,c)}
function Tf(a,b){a.A=!0;Re(function(){a.A&&Vf.call(null,b)})}
var Vf=Ne;function Mf(a){Za.call(this,a)}
D(Mf,Za);Mf.prototype.name="cancel";function L(a){K.call(this);this.u=1;this.l=[];this.m=0;this.i=[];this.j={};this.C=!!a}
D(L,K);m=L.prototype;m.subscribe=function(a,b,c){var d=this.j[a];d||(d=this.j[a]=[]);var e=this.u;this.i[e]=a;this.i[e+1]=b;this.i[e+2]=c;this.u=e+3;d.push(e);return e};
function Wf(a,b,c,d){if(b=a.j[b]){var e=a.i;(b=b.find(function(f){return e[f+1]==c&&e[f+2]==d}))&&a.ra(b)}}
m.ra=function(a){var b=this.i[a];if(b){var c=this.j[b];0!=this.m?(this.l.push(a),this.i[a+1]=Ka):(c&&gb(c,a),delete this.i[a],delete this.i[a+1],delete this.i[a+2])}return!!b};
m.ja=function(a,b){var c=this.j[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.C)for(e=0;e<c.length;e++){var g=c[e];Xf(this.i[g+1],this.i[g+2],d)}else{this.m++;try{for(e=0,f=c.length;e<f&&!this.h();e++)g=c[e],this.i[g+1].apply(this.i[g+2],d)}finally{if(this.m--,0<this.l.length&&0==this.m)for(;c=this.l.pop();)this.ra(c)}}return 0!=e}return!1};
function Xf(a,b,c){Re(function(){a.apply(b,c)})}
m.clear=function(a){if(a){var b=this.j[a];b&&(b.forEach(this.ra,this),delete this.j[a])}else this.i.length=0,this.j={}};
m.G=function(){L.U.G.call(this);this.clear();this.l.length=0};function Yf(a){this.h=a}
Yf.prototype.set=function(a,b){void 0===b?this.h.remove(a):this.h.set(a,xf(b))};
Yf.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
Yf.prototype.remove=function(a){this.h.remove(a)};function Zf(a){this.h=a}
D(Zf,Yf);function $f(a){this.data=a}
function bg(a){return void 0===a||a instanceof $f?a:new $f(a)}
Zf.prototype.set=function(a,b){Zf.U.set.call(this,a,bg(b))};
Zf.prototype.i=function(a){a=Zf.U.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
Zf.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function cg(a){this.h=a}
D(cg,Zf);cg.prototype.set=function(a,b,c){if(b=bg(b)){if(c){if(c<Date.now()){cg.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Date.now()}cg.U.set.call(this,a,b)};
cg.prototype.i=function(a){var b=cg.U.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Date.now()||c&&c>Date.now())cg.prototype.remove.call(this,a);else return b}};function dg(){}
;function eg(){}
D(eg,dg);eg.prototype[Symbol.iterator]=function(){return lf(this.R(!0)).i()};
eg.prototype.clear=function(){var a=Array.from(this);a=t(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function fg(a){this.h=a}
D(fg,eg);m=fg.prototype;m.isAvailable=function(){if(!this.h)return!1;try{return this.h.setItem("__sak","1"),this.h.removeItem("__sak"),!0}catch(a){return!1}};
m.set=function(a,b){try{this.h.setItem(a,b)}catch(c){if(0==this.h.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
m.get=function(a){a=this.h.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
m.remove=function(a){this.h.removeItem(a)};
m.R=function(a){var b=0,c=this.h,d=new gf;d.next=function(){if(b>=c.length)return hf;var f=c.key(b++);if(a)return jf(f);f=c.getItem(f);if("string"!==typeof f)throw"Storage mechanism: Invalid value was encountered";return jf(f)};
var e=d.next;d.W=function(){return kf(e.call(d))};
return d};
m.clear=function(){this.h.clear()};
m.key=function(a){return this.h.key(a)};function gg(){var a=null;try{a=window.localStorage||null}catch(b){}this.h=a}
D(gg,fg);function hg(a,b){this.i=a;this.h=null;var c;if(c=oc)c=!(9<=Number(Bc));if(c){ig||(ig=new qf);this.h=ig.get(a);this.h||(b?this.h=document.getElementById(b):(this.h=document.createElement("userdata"),this.h.addBehavior("#default#userData"),document.body.appendChild(this.h)),ig.set(a,this.h));try{this.h.load(this.i)}catch(d){this.h=null}}}
D(hg,eg);var jg={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},ig=null;function kg(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return jg[b]})}
m=hg.prototype;m.isAvailable=function(){return!!this.h};
m.set=function(a,b){this.h.setAttribute(kg(a),b);lg(this)};
m.get=function(a){a=this.h.getAttribute(kg(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
m.remove=function(a){this.h.removeAttribute(kg(a));lg(this)};
m.R=function(a){var b=0,c=this.h.XMLDocument.documentElement.attributes,d=new gf;d.next=function(){if(b>=c.length)return hf;var f=c[b++];if(a)return jf(decodeURIComponent(f.nodeName.replace(/\./g,"%")).substr(1));f=f.nodeValue;if("string"!==typeof f)throw"Storage mechanism: Invalid value was encountered";return jf(f)};
var e=d.next;d.W=function(){return kf(e.call(d))};
return d};
m.clear=function(){for(var a=this.h.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);lg(this)};
function lg(a){try{a.h.save(a.i)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function mg(a,b){this.i=a;this.h=b+"::"}
D(mg,eg);mg.prototype.set=function(a,b){this.i.set(this.h+a,b)};
mg.prototype.get=function(a){return this.i.get(this.h+a)};
mg.prototype.remove=function(a){this.i.remove(this.h+a)};
mg.prototype.R=function(a){var b=this.i.R(!0),c=this,d=new gf;d.next=function(){try{var f=b.W()}catch(g){if(g===ff)return hf;throw g;}for(;f.substr(0,c.h.length)!=c.h;)try{f=b.W()}catch(g){if(g===ff)return hf;throw g;}return jf(a?f.substr(c.h.length):c.i.get(f))};
var e=d.next;d.W=function(){return kf(e.call(d))};
return d};function ng(a){H.call(this,a)}
v(ng,H);ng.prototype.getKey=function(){return Wc(this,1)};
ng.prototype.getValue=function(){return Wc(this,2===Yc(this,og)?2:-1)};
ng.prototype.setValue=function(a){var b=Yc(this,og);b&&2!==b&&null!=a&&(this.h&&b in this.h&&(this.h[b]=void 0),I(this,b,void 0));return I(this,2,a)};
var og=[2,3,4,5,6];function pg(a){H.call(this,a)}
v(pg,H);function qg(a){H.call(this,a)}
v(qg,H);function rg(a){H.call(this,a)}
v(rg,H);function sg(a){H.call(this,a,-1,tg)}
v(sg,H);sg.prototype.getPlayerType=function(){return Wc(this,36)};
sg.prototype.setHomeGroupInfo=function(a){return ad(this,81,a)};
var tg=[9,66,24,32,86,100,101];function ug(a){H.call(this,a,-1,vg)}
v(ug,H);var vg=[15,26,28];function wg(a){H.call(this,a)}
v(wg,H);wg.prototype.setToken=function(a){return I(this,2,a)};function xg(a){H.call(this,a,-1,yg)}
v(xg,H);xg.prototype.setSafetyMode=function(a){return I(this,5,a)};
var yg=[12];function zg(a){H.call(this,a,-1,Ag)}
v(zg,H);var Ag=[12];function Bg(a){H.call(this,a)}
v(Bg,H);function Cg(a){H.call(this,a)}
v(Cg,H);var Dg=[1,2];function Eg(a){H.call(this,a,-1,Fg)}
v(Eg,H);var Fg=[3];function Gg(a,b){1<b.length?a[b[0]]=b[1]:1===b.length&&Object.assign(a,b[0])}
;function Hg(a){H.call(this,a,1)}
v(Hg,H);var Ig,Jg,Kg,Lg=y.window,Mg=(null===(Ig=null===Lg||void 0===Lg?void 0:Lg.yt)||void 0===Ig?void 0:Ig.config_)||(null===(Jg=null===Lg||void 0===Lg?void 0:Lg.ytcfg)||void 0===Jg?void 0:Jg.data_)||{},Ng=(null===(Kg=null===Lg||void 0===Lg?void 0:Lg.ytcfg)||void 0===Kg?void 0:Kg.obfuscatedData_)||[];function Og(){Hg.apply(this,arguments)}
v(Og,Hg);new Og(Ng);B("yt.config_",Mg,void 0);B("yt.configJspb_",Ng,void 0);function M(){Gg(Mg,arguments)}
function F(a,b){return a in Mg?Mg[a]:b}
;var Pg=[];function Qg(a){Pg.forEach(function(b){return b(a)})}
function Rg(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){Sg(b)}}:a}
function Sg(a,b,c,d){var e=C("yt.logging.errors.log");e?e(a,"ERROR",b,c,d):(e=F("ERRORS",[]),e.push([a,"ERROR",b,c,d]),M("ERRORS",e));Qg(a)}
function Tg(a,b,c,d){var e=C("yt.logging.errors.log");e?e(a,"WARNING",b,c,d):(e=F("ERRORS",[]),e.push([a,"WARNING",b,c,d]),M("ERRORS",e))}
;var Ug=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};B("yt.msgs_",Ug,void 0);function Vg(a){Gg(Ug,arguments)}
;function N(a){a=Wg(a);return"string"===typeof a&&"false"===a?!1:!!a}
function Xg(a,b){a=Wg(a);return void 0===a&&void 0!==b?b:Number(a||0)}
function Wg(a){var b=F("EXPERIMENTS_FORCED_FLAGS",{});return void 0!==b[a]?b[a]:F("EXPERIMENT_FLAGS",{})[a]}
function Yg(){var a=[],b=F("EXPERIMENTS_FORCED_FLAGS",{});for(c in b)a.push({key:c,value:String(b[c])});var c=F("EXPERIMENT_FLAGS",{});for(var d in c)d.startsWith("force_")&&void 0===b[d]&&a.push({key:d,value:String(c[d])});return a}
;var Zg={appSettingsCaptured:!0,visualElementAttached:!0,visualElementGestured:!0,visualElementHidden:!0,visualElementShown:!0,flowEvent:!0,visualElementStateChanged:!0,playbackAssociated:!0,youThere:!0,accountStateChangeSignedIn:!0,accountStateChangeSignedOut:!0},$g={latencyActionBaselined:!0,latencyActionInfo:!0,latencyActionTicked:!0,bedrockRepetitiveActionTimed:!0,adsClientStateChange:!0,streamzIncremented:!0,mdxDialAdditionalDataUpdateEvent:!0,tvhtml5WatchKeyEvent:!0,tvhtml5VideoSeek:!0,tokenRefreshEvent:!0,
adNotify:!0,adNotifyFilled:!0,tvhtml5LaunchUrlComponentChanged:!0,bedrockResourceConsumptionSnapshot:!0,deviceStartupMetrics:!0,mdxSignIn:!0,tvhtml5KeyboardLogging:!0,tvhtml5StartupSoundEvent:!0,tvhtml5LiveChatStatus:!0,tvhtml5DeviceStorageStatus:!0,tvhtml5LocalStorage:!0,directSignInEvent:!0,finalPayload:!0,tvhtml5SearchCompleted:!0,tvhtml5KeyboardPerformance:!0,adNotifyFailure:!0,latencyActionSpan:!0,tvhtml5AccountDialogOpened:!0,tvhtml5ApiTest:!0};var ah=0,bh=rc?"webkit":qc?"moz":oc?"ms":nc?"o":"";B("ytDomDomGetNextId",C("ytDomDomGetNextId")||function(){return++ah},void 0);var ch={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function dh(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in ch||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.h=a.pageX;this.i=a.pageY}}catch(e){}}
function eh(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.h=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.i=a.clientY+b}}
dh.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
dh.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
dh.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var lb=y.ytEventsEventsListeners||{};B("ytEventsEventsListeners",lb,void 0);var fh=y.ytEventsEventsCounter||{count:0};B("ytEventsEventsCounter",fh,void 0);
function gh(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return kb(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=Oa(e[4])&&Oa(d)&&pb(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
var hh=ab(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function ih(a,b,c,d){d=void 0===d?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=gh(a,b,c,d);if(e)return e;e=++fh.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new dh(h);if(!yd(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new dh(h);
h.currentTarget=a;return c.call(a,h)};
g=Rg(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),hh()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);lb[e]=[a,b,c,g,d];return e}
function jh(a){a&&("string"==typeof a&&(a=[a]),E(a,function(b){if(b in lb){var c=lb[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?hh()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete lb[b]}}))}
;var kh=window.ytcsi&&window.ytcsi.now?window.ytcsi.now:window.performance&&window.performance.timing&&window.performance.now&&window.performance.timing.navigationStart?function(){return window.performance.timing.navigationStart+window.performance.now()}:function(){return(new Date).getTime()};function lh(a,b){"function"===typeof a&&(a=Rg(a));return window.setTimeout(a,b)}
function mh(a){window.clearTimeout(a)}
;function nh(a){this.J=a;this.i=null;this.m=0;this.C=null;this.u=0;this.j=[];for(a=0;4>a;a++)this.j.push(0);this.l=0;this.P=ih(window,"mousemove",Va(this.T,this));a=Va(this.K,this);"function"===typeof a&&(a=Rg(a));this.aa=window.setInterval(a,25)}
D(nh,K);nh.prototype.T=function(a){void 0===a.h&&eh(a);var b=a.h;void 0===a.i&&eh(a);this.i=new qd(b,a.i)};
nh.prototype.K=function(){if(this.i){var a=kh();if(0!=this.m){var b=this.C,c=this.i,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.m);this.j[this.l]=.5<Math.abs((d-this.u)/this.u)?1:0;for(c=b=0;4>c;c++)b+=this.j[c]||0;3<=b&&this.J();this.u=d}this.m=a;this.C=this.i;this.l=(this.l+1)%4}};
nh.prototype.G=function(){window.clearInterval(this.aa);jh(this.P)};function oh(){}
function ph(a,b){return qh(a,0,b)}
oh.prototype.M=function(a,b){return qh(a,1,b)};
function rh(a,b){qh(a,2,b)}
;function sh(){oh.apply(this,arguments)}
v(sh,oh);function th(){sh.h||(sh.h=new sh);return sh.h}
function qh(a,b,c){void 0!==c&&Number.isNaN(Number(c))&&(c=void 0);var d=C("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):lh(a,c||0)}
sh.prototype.ca=function(a){if(void 0===a||!Number.isNaN(Number(a))){var b=C("yt.scheduler.instance.cancelJob");b?b(a):mh(a)}};
sh.prototype.start=function(){var a=C("yt.scheduler.instance.start");a&&a()};
sh.prototype.pause=function(){var a=C("yt.scheduler.instance.pause");a&&a()};var uh=th();var vh={};
function wh(a){var b=void 0===a?{}:a;a=void 0===b.Tb?!1:b.Tb;b=void 0===b.Ib?!0:b.Ib;if(null==C("_lact",window)){var c=parseInt(F("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;B("_lact",c,window);B("_fact",c,window);-1==c&&xh();ih(document,"keydown",xh);ih(document,"keyup",xh);ih(document,"mousedown",xh);ih(document,"mouseup",xh);a?ih(window,"touchmove",function(){yh("touchmove",200)},{passive:!0}):(ih(window,"resize",function(){yh("resize",200)}),b&&ih(window,"scroll",function(){yh("scroll",200)}));
new nh(function(){yh("mouse",100)});
ih(document,"touchstart",xh,{passive:!0});ih(document,"touchend",xh,{passive:!0})}}
function yh(a,b){vh[a]||(vh[a]=!0,uh.M(function(){xh();vh[a]=!1},b))}
function xh(){null==C("_lact",window)&&wh();var a=Date.now();B("_lact",a,window);-1==C("_fact",window)&&B("_fact",a,window);(a=C("ytglobal.ytUtilActivityCallback_"))&&a()}
function zh(){var a=C("_lact",window);return null==a?-1:Math.max(Date.now()-a,0)}
;function Ah(){var a=Bh;C("yt.ads.biscotti.getId_")||B("yt.ads.biscotti.getId_",a,void 0)}
function Ch(a){B("yt.ads.biscotti.lastId_",a,void 0)}
;var Dh=/^[\w.]*$/,Eh={q:!0,search_query:!0};function Fh(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=Gh(f[0]||""),h=Gh(f[1]||"");g in c?Array.isArray(c[g])?ib(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(p){var k=p,l=f[0],n=String(Fh);k.args=[{key:l,value:f[1],query:a,method:Hh==n?"unchanged":n}];Eh.hasOwnProperty(l)||Tg(k)}}return c}
var Hh=String(Fh);function Ih(a){var b=[];jb(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];E(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function Jh(a){"?"==a.charAt(0)&&(a=a.substr(1));return Fh(a,"&")}
function Kh(){var a=window.location.href;return-1!=a.indexOf("?")?(a=(a||"").split("#")[0],a=a.split("?",2),Jh(1<a.length?a[1]:a[0])):{}}
function Lh(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=Jh(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);return jc(a,e)+d}
function Mh(a){if(!b)var b=window.location.href;var c=a.match(ec)[1]||null,d=gc(a);c&&d?(a=a.match(ec),b=b.match(ec),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?gc(b)==d&&(Number(b.match(ec)[4]||null)||null)==(Number(a.match(ec)[4]||null)||null):!0;return a}
function Gh(a){return a&&a.match(Dh)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function Nh(a){var b=Oh;a=void 0===a?C("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=Gd;e.flash="0";a:{try{var f=b.h.top.location.href}catch(Ta){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=void 0===g?gd:g;try{var h=g.history.length}catch(Ta){h=0}e.u_his=h;var k;e.u_h=null==(k=gd.screen)?void 0:k.height;var l;e.u_w=null==(l=gd.screen)?void 0:l.width;var n;e.u_ah=null==(n=gd.screen)?void 0:n.availHeight;var p;e.u_aw=
null==(p=gd.screen)?void 0:p.availWidth;var u;e.u_cd=null==(u=gd.screen)?void 0:u.colorDepth}catch(Ta){}h=b.h;try{var r=h.screenX;var z=h.screenY}catch(Ta){}try{var A=h.outerWidth;var J=h.outerHeight}catch(Ta){}try{var R=h.innerWidth;var S=h.innerHeight}catch(Ta){}try{var U=h.screenLeft;var Pc=h.screenTop}catch(Ta){}try{R=h.innerWidth,S=h.innerHeight}catch(Ta){}try{var ag=h.screen.availWidth;var co=h.screen.availTop}catch(Ta){}r=[U,Pc,r,z,ag,co,A,J,R,S];z=b.h.top;try{var pa=(z||window).document,ea=
"CSS1Compat"==pa.compatMode?pa.documentElement:pa.body;var Ia=(new rd(ea.clientWidth,ea.clientHeight)).round()}catch(Ta){Ia=new rd(-12245933,-12245933)}pa=Ia;Ia={};ea=new Ge;y.SVGElement&&y.document.createElementNS&&ea.set(0);z=Dd();z["allow-top-navigation-by-user-activation"]&&ea.set(1);z["allow-popups-to-escape-sandbox"]&&ea.set(2);y.crypto&&y.crypto.subtle&&ea.set(3);y.TextDecoder&&y.TextEncoder&&ea.set(4);ea=He(ea);Ia.bc=ea;Ia.bih=pa.height;Ia.biw=pa.width;Ia.brdim=r.join();b=b.i;pa="ka";Ie.ka&&
Ie.hasOwnProperty(pa)?pa=Ie.ka:(ea=new Ie,Ie.ka=ea,Ie.hasOwnProperty(pa),pa=ea);b=(Ia.vis=pa.D(Hd.flag,Hd.defaultValue)&&b.prerendering?3:{visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,Ia.wgl=!!gd.WebGLRenderingContext,Ia);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var Oh=new function(){var a=window.document;this.h=window;this.i=a};
B("yt.ads_.signals_.getAdSignalsString",function(a){return Ih(Nh(a))},void 0);Date.now();var Ph="XMLHttpRequest"in y?function(){return new XMLHttpRequest}:null;
function Qh(){if(!Ph)return null;var a=Ph();return"open"in a?a:null}
function Rh(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;var Sh={Authorization:"AUTHORIZATION","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL","X-YouTube-Page-Label":"PAGE_BUILD_LABEL",
"X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM"},Th="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(ha("client_dev_mss_url client_dev_regex_map client_dev_root_url expflag jsfeat jsmode client_rollout_override".split(" "))),Uh=!1;
function Vh(a,b){b=void 0===b?{}:b;var c=Mh(a),d=N("web_ajax_ignore_global_headers_if_set"),e;for(e in Sh){var f=F(Sh[e]);!f||!c&&gc(a)||d&&void 0!==b[e]||(b[e]=f)}if(c||!gc(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!gc(a)){try{var g=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(h){}g&&(b["X-YouTube-Time-Zone"]=g)}if(c||!gc(a))b["X-YouTube-Ad-Signals"]=Ih(Nh(void 0));return b}
function Wh(a){var b=window.location.search,c=gc(a);N("debug_handle_relative_url_for_query_forward_killswitch")||c||!Mh(a)||(c=document.location.hostname);var d=fc(a.match(ec)[5]||null);d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=Jh(b),f={};E(Th,function(g){e[g]&&(f[g]=e[g])});
return Lh(a,f||{},!1)}
function Xh(a,b){var c=b.format||"JSON";a=Yh(a,b);var d=Zh(a,b),e=!1,f=$h(a,function(k){if(!e){e=!0;h&&mh(h);var l=Rh(k),n=null,p=400<=k.status&&500>k.status,u=500<=k.status&&600>k.status;if(l||p||u)n=ai(a,c,k,b.convertToSafeHtml);if(l)a:if(k&&204==k.status)l=!0;else{switch(c){case "XML":l=0==parseInt(n&&n.return_code,10);break a;case "RAW":l=!0;break a}l=!!n}n=n||{};p=b.context||y;l?b.onSuccess&&b.onSuccess.call(p,k,n):b.onError&&b.onError.call(p,k,n);b.onFinish&&b.onFinish.call(p,k,n)}},b.method,
d,b.headers,b.responseType,b.withCredentials);
if(b.onTimeout&&0<b.timeout){var g=b.onTimeout;var h=lh(function(){e||(e=!0,f.abort(),mh(h),g.call(b.context||y,f))},b.timeout)}return f}
function Yh(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=F("XSRF_FIELD_NAME",void 0);if(b=b.urlParams)b[c]&&delete b[c],a=Lh(a,b||{},!0);return a}
function Zh(a,b){var c=F("XSRF_FIELD_NAME",void 0),d=F("XSRF_TOKEN",void 0),e=b.postBody||"",f=b.postParams,g=F("XSRF_FIELD_NAME",void 0),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||gc(a)&&!b.withCredentials&&gc(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);f&&"string"===typeof e&&(e=Jh(e),tb(e,f),e=b.postBodyFormat&&"JSON"==b.postBodyFormat?JSON.stringify(e):ic(e));f=e||f&&!mb(f);!Uh&&f&&
"POST"!=b.method&&(Uh=!0,Sg(Error("AJAX request with postData should use POST")));return e}
function ai(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,Tg(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?bi(a):null)e={},E(a.getElementsByTagName("*"),function(g){e[g.tagName]=ci(g)})}d&&di(e);
return e}
function di(a){if(Oa(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;yb("HTML that is escaped and sanitized server-side and passed through yt.net.ajax");var d=Yb(a[b],null);a[c]=d}else di(a[b])}}
function bi(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function ci(a){var b="";E(a.childNodes,function(c){b+=c.nodeValue});
return b}
function $h(a,b,c,d,e,f,g){function h(){4==(k&&"readyState"in k?k.readyState:0)&&b&&Rg(b)(k)}
c=void 0===c?"GET":c;d=void 0===d?"":d;var k=Qh();if(!k)return null;"onloadend"in k?k.addEventListener("loadend",h,!1):k.onreadystatechange=h;N("debug_forward_web_query_parameters")&&(a=Wh(a));k.open(c,a,!0);f&&(k.responseType=f);g&&(k.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=Vh(a,e))for(var l in e)k.setRequestHeader(l,e[l]),"content-type"==l.toLowerCase()&&(c=!1);c&&k.setRequestHeader("Content-Type","application/x-www-form-urlencoded");k.send(d);
return k}
;var ei=Cc||Dc;function fi(a){var b=Ub();return b?0<=b.toLowerCase().indexOf(a):!1}
;var gi={},hi=0;
function ii(a,b,c,d,e){e=void 0===e?"":e;if(a)if(c&&!fi("cobalt")){if(a){a instanceof Nb||(a="object"==typeof a&&a.ea?a.da():String(a),Sb.test(a)?a=new Nb(a,Ob):(a=String(a),a=a.replace(/(%0A|%0D)/g,""),a=(b=a.match(Rb))&&Qb.test(b[1])?new Nb(a,Ob):null));b=Pb(a||Tb);if("about:invalid#zClosurez"===b||b.startsWith("data"))a="";else{if(b instanceof Xb)a=b;else{var f="object"==typeof b;a=null;f&&b.Ra&&(a=b.Na());b=f&&b.ea?b.da():String(b);Mb.test(b)&&(-1!=b.indexOf("&")&&(b=b.replace(Gb,"&amp;")),-1!=
b.indexOf("<")&&(b=b.replace(Hb,"&lt;")),-1!=b.indexOf(">")&&(b=b.replace(Ib,"&gt;")),-1!=b.indexOf('"')&&(b=b.replace(Jb,"&quot;")),-1!=b.indexOf("'")&&(b=b.replace(Kb,"&#39;")),-1!=b.indexOf("\x00")&&(b=b.replace(Lb,"&#0;")));a=Yb(b,a)}a instanceof Xb&&a.constructor===Xb?a=a.h:(Ma(a),a="type_error:SafeHtml");a=encodeURIComponent(String(xf(a.toString())))}/^[\s\xa0]*$/.test(a)||(a=vd("IFRAME",{src:'javascript:"<body><img src=\\""+'+a+'+"\\"></body>"',style:"display:none"}),(9==a.nodeType?a:a.ownerDocument||
a.document).body.appendChild(a))}}else if(e)$h(a,b,"POST",e,d);else if(F("USE_NET_AJAX_FOR_PING_TRANSPORT",!1)||d)$h(a,b,"GET","",d);else{b:{try{var g=new $a({url:a});if(g.j&&g.i||g.l){var h=fc(a.match(ec)[5]||null),k;if(!(k=!h||!h.endsWith("/aclk"))){var l=a.search(kc);d:{for(c=0;0<=(c=a.indexOf("ri",c))&&c<l;){var n=a.charCodeAt(c-1);if(38==n||63==n){var p=a.charCodeAt(c+2);if(!p||61==p||38==p||35==p){var u=c;break d}}c+=3}u=-1}if(0>u)var r=null;else{var z=a.indexOf("&",u);if(0>z||z>l)z=l;u+=3;
r=decodeURIComponent(a.substr(u,z-u).replace(/\+/g," "))}k="1"!==r}f=!k;break b}}catch(A){}f=!1}f?ji(a)?(b&&b(),f=!0):f=!1:f=!1;f||ki(a,b)}}
function li(a){var b=void 0===b?"":b;ji(a,b)||ii(a,void 0,void 0,void 0,b)}
function ji(a,b){try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,void 0===b?"":b))return!0}catch(c){}return!1}
function ki(a,b){var c=new Image,d=""+hi++;gi[d]=c;c.onload=c.onerror=function(){b&&gi[d]&&b();delete gi[d]};
c.src=a}
;var mi=y.ytPubsubPubsubInstance||new L,ni=y.ytPubsubPubsubSubscribedKeys||{},oi=y.ytPubsubPubsubTopicToKeys||{},pi=y.ytPubsubPubsubIsSynchronous||{};function qi(a,b){var c=ri();if(c&&b){var d=c.subscribe(a,function(){var e=arguments;var f=function(){ni[d]&&b.apply&&"function"==typeof b.apply&&b.apply(window,e)};
try{pi[a]?f():lh(f,0)}catch(g){Sg(g)}},void 0);
ni[d]=!0;oi[a]||(oi[a]=[]);oi[a].push(d);return d}return 0}
function si(a){var b=ri();b&&("number"===typeof a?a=[a]:"string"===typeof a&&(a=[parseInt(a,10)]),E(a,function(c){b.unsubscribeByKey(c);delete ni[c]}))}
function ti(a,b){var c=ri();c&&c.publish.apply(c,arguments)}
function ui(a){var b=ri();if(b)if(b.clear(a),a)vi(a);else for(var c in oi)vi(c)}
function ri(){return y.ytPubsubPubsubInstance}
function vi(a){oi[a]&&(a=oi[a],E(a,function(b){ni[b]&&delete ni[b]}),a.length=0)}
L.prototype.subscribe=L.prototype.subscribe;L.prototype.unsubscribeByKey=L.prototype.ra;L.prototype.publish=L.prototype.ja;L.prototype.clear=L.prototype.clear;B("ytPubsubPubsubInstance",mi,void 0);B("ytPubsubPubsubTopicToKeys",oi,void 0);B("ytPubsubPubsubIsSynchronous",pi,void 0);B("ytPubsubPubsubSubscribedKeys",ni,void 0);var wi=window,O=wi.ytcsi&&wi.ytcsi.now?wi.ytcsi.now:wi.performance&&wi.performance.timing&&wi.performance.now&&wi.performance.timing.navigationStart?function(){return wi.performance.timing.navigationStart+wi.performance.now()}:function(){return(new Date).getTime()};var xi=Xg("initial_gel_batch_timeout",2E3),yi=Math.pow(2,16)-1,zi=void 0;function Ai(){this.j=this.h=this.i=0}
var Bi=new Ai,Ci=new Ai,Di=!0,Ei=y.ytLoggingTransportGELQueue_||new Map;B("ytLoggingTransportGELQueue_",Ei,void 0);var Fi=y.ytLoggingTransportGELProtoQueue_||new Map;B("ytLoggingTransportGELProtoQueue_",Fi,void 0);var Gi=y.ytLoggingTransportTokensToCttTargetIds_||{};B("ytLoggingTransportTokensToCttTargetIds_",Gi,void 0);var Hi=y.ytLoggingTransportTokensToJspbCttTargetIds_||{};B("ytLoggingTransportTokensToJspbCttTargetIds_",Hi,void 0);
function Ii(a,b){if("log_event"===a.endpoint){var c=Ji(a),d=Ei.get(c)||[];Ei.set(c,d);d.push(a.payload);var e=void 0===e?!1:e;b&&(zi=new b);a=Xg("tvhtml5_logging_max_batch")||Xg("web_logging_max_batch")||100;b=O();var f=e?Ci.j:Bi.j;d.length>=a?Ki({writeThenSend:!0},N("flush_only_full_queue")?c:void 0,e):10<=b-f&&(Li(e),e?Ci.j=b:Bi.j=b)}}
function Mi(a,b){if("log_event"===a.endpoint){var c=Ji(a),d=new Map;d.set(c,[a.payload]);b&&(zi=new b);return new Ef(function(e){zi&&zi.isReady()?Ni(d,e,{bypassNetworkless:!0},!0):e()})}}
function Ji(a){var b="";if(a.Ma)b="visitorOnlyApprovedKey";else if(a.cttAuthInfo){b=a.cttAuthInfo;var c={};b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId);Gi[a.cttAuthInfo.token]=c;b=a.cttAuthInfo.token}return b}
function Ki(a,b,c){a=void 0===a?{}:a;c=void 0===c?!1:c;new Ef(function(d){c?(mh(Ci.i),mh(Ci.h),Ci.h=0):(mh(Bi.i),mh(Bi.h),Bi.h=0);if(zi&&zi.isReady())if(void 0!==b)if(c){var e=new Map,f=Fi.get(b)||[];e.set(b,f);Oi(e,d,a);Fi.delete(b)}else e=new Map,f=Ei.get(b)||[],e.set(b,f),Ni(e,d,a),Ei.delete(b);else c?(Oi(Fi,d,a),Fi.clear()):(Ni(Ei,d,a),Ei.clear());else Li(c),d()})}
function Li(a){a=void 0===a?!1:a;if(N("web_gel_timeout_cap")&&(!a&&!Bi.h||a&&!Ci.h)){var b=lh(function(){Ki({writeThenSend:!0},void 0,a)},6E4);
a?Ci.h=b:Bi.h=b}mh(a?Ci.i:Bi.i);b=F("LOGGING_BATCH_TIMEOUT",Xg("web_gel_debounce_ms",1E4));N("shorten_initial_gel_batch_timeout")&&Di&&(b=xi);b=lh(function(){Ki({writeThenSend:!0},void 0,a)},b);
a?Ci.i=b:Bi.i=b}
function Ni(a,b,c,d){var e=zi;c=void 0===c?{}:c;var f=Math.round(O()),g=a.size;a=t(a);for(var h=a.next();!h.done;h=a.next()){var k=t(h.value);h=k.next().value;var l=k=k.next().value;k=rb({context:Pi(e.config_||Qi())});k.events=l;(l=Gi[h])&&Ri(k,h,l);delete Gi[h];h="visitorOnlyApprovedKey"===h;Si(k,f,h);Ti(c);N("send_beacon_before_gel")&&window.navigator&&window.navigator.sendBeacon&&!c.writeThenSend&&li("/generate_204");Ui(e,"log_event",k,Vi(c,h,function(){g--;g||b()},function(){g--;
g||b()},d));
Di=!1}}
function Oi(a,b,c){var d=zi;c=void 0===c?{}:c;var e=Math.round(O()),f=a.size;a=t(a);for(var g=a.next();!g.done;g=a.next()){var h=t(g.value);g=h.next().value;var k=h=h.next().value;h=new Eg;var l=Wi(d.config_||Qi());ad(h,1,l);for(l=0;l<k.length;l++)bd(h,3,k[l],Bg);(k=Hi[g])&&Xi(h,g,k);delete Hi[g];g="visitorOnlyApprovedKey"===g;Yi(h,e,g);Ti(c);a:{Mc=!0;try{var n=JSON.stringify(h.toJSON(),cd);break a}finally{Mc=!1}n=void 0}h=n;g=Vi(c,g,function(){f--;f||b()},function(){f--;
f||b()},void 0);
g.headers={"Content-Type":"application/json+protobuf"};g.postBodyFormat="JSPB";g.postBody=h;Ui(d,"log_event","",g);Di=!1}}
function Ti(a){N("always_send_and_write")&&(a.writeThenSend=!1)}
function Vi(a,b,c,d,e){return{retry:!0,onSuccess:c,onError:d,rb:a,Ma:b,ln:!!e,headers:{},postBodyFormat:"",postBody:""}}
function Si(a,b,c){a.requestTimeMs=String(b);N("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=F("EVENT_ID",void 0))&&(c=Zi(),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function Yi(a,b,c){I(a,2,b);if(!c&&(b=F("EVENT_ID",void 0))){c=Zi();var d=new Cg;I(d,1,b);I(d,2,c);ad(a,5,d)}}
function Zi(){var a=F("BATCH_CLIENT_COUNTER",void 0)||0;a||(a=Math.floor(Math.random()*yi/2));a++;a>yi&&(a=1);M("BATCH_CLIENT_COUNTER",a);return a}
function Ri(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function Xi(a,b,c){if(Wc(c,1===Yc(c,Dg)?1:-1))var d=1;else if(c.getPlaylistId())d=2;else return;ad(a,4,c);a=Zc(a,zg,1)||new zg;c=Zc(a,xg,3)||new xg;var e=new wg;e.setToken(b);I(e,1,d);bd(c,12,e,wg);ad(a,3,c)}
;var $i=y.ytLoggingGelSequenceIdObj_||{};B("ytLoggingGelSequenceIdObj_",$i,void 0);
function aj(a,b,c,d){d=void 0===d?{}:d;if(N("lr_drop_other_and_business_payloads")){if($g[a]||Zg[a])return}else if(N("lr_drop_other_payloads")&&$g[a])return;var e={},f=Math.round(d.timestamp||O());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;a=zh();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};N("log_sequence_info_on_gel_web")&&d.ha&&(a=e.context,b=d.ha,$i[b]=b in $i?$i[b]+1:0,a.sequence={index:$i[b],groupKey:b},d.Jb&&delete $i[d.ha]);(d.wn?Mi:Ii)({endpoint:"log_event",payload:e,
cttAuthInfo:d.cttAuthInfo,Ma:d.Ma},c)}
;function bj(){if(!y.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return y.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":y.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":y.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":y.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
function cj(){var a=bj();a=Object.keys(Fe).indexOf(a);return-1===a?null:a}
;function dj(a,b,c,d,e){Pd.set(""+a,b,{Ua:c,path:"/",domain:void 0===d?"youtube.com":d,secure:void 0===e?!1:e})}
;var ej=C("ytglobal.prefsUserPrefsPrefs_")||{};B("ytglobal.prefsUserPrefsPrefs_",ej,void 0);function fj(){this.h=F("ALT_PREF_COOKIE_NAME","PREF");this.i=F("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=Pd.get(""+this.h,void 0);if(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(ej[d]=c.toString())}}}
fj.prototype.get=function(a,b){gj(a);hj(a);a=void 0!==ej[a]?ej[a].toString():null;return null!=a?a:b?b:""};
fj.prototype.set=function(a,b){gj(a);hj(a);if(null==b)throw Error("ExpectedNotNull");ej[a]=b.toString()};
fj.prototype.remove=function(a){gj(a);hj(a);delete ej[a]};
fj.prototype.clear=function(){for(var a in ej)delete ej[a]};
function hj(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function gj(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function ij(a){a=void 0!==ej[a]?ej[a].toString():null;return null!=a&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
La(fj);var jj={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},kj={CONN_DEFAULT:0,CONN_UNKNOWN:1,CONN_NONE:2,CONN_WIFI:3,CONN_CELLULAR_2G:4,CONN_CELLULAR_3G:5,CONN_CELLULAR_4G:6,CONN_CELLULAR_UNKNOWN:7,CONN_DISCO:8,CONN_CELLULAR_5G:9,CONN_WIFI_METERED:10,CONN_CELLULAR_5G_SA:11,
CONN_CELLULAR_5G_NSA:12,CONN_INVALID:31},lj={EFFECTIVE_CONNECTION_TYPE_UNKNOWN:0,EFFECTIVE_CONNECTION_TYPE_OFFLINE:1,EFFECTIVE_CONNECTION_TYPE_SLOW_2G:2,EFFECTIVE_CONNECTION_TYPE_2G:3,EFFECTIVE_CONNECTION_TYPE_3G:4,EFFECTIVE_CONNECTION_TYPE_4G:5},mj={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};function nj(){var a=y.navigator;return a?a.connection:void 0}
;function oj(){return"INNERTUBE_API_KEY"in Mg&&"INNERTUBE_API_VERSION"in Mg}
function Qi(){return{innertubeApiKey:F("INNERTUBE_API_KEY",void 0),innertubeApiVersion:F("INNERTUBE_API_VERSION",void 0),Sa:F("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),Ta:F("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),Lb:F("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:F("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0),nb:F("INNERTUBE_CONTEXT_HL",void 0),mb:F("INNERTUBE_CONTEXT_GL",void 0),Mb:F("INNERTUBE_HOST_OVERRIDE",void 0)||"",Ob:!!F("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),Nb:!!F("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:F("SERIALIZED_CLIENT_CONFIG_DATA",void 0)}}
function Pi(a){var b={client:{hl:a.nb,gl:a.mb,clientName:a.Ta,clientVersion:a.innertubeContextClientVersion,configInfo:a.Sa}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=y.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=F("EXPERIMENTS_TOKEN","");""!==c&&(b.client.experimentsToken=c);c=Yg();0<c.length&&(b.request={internalExperimentFlags:c});pj(a,void 0,b);qj(a,void 0,b);rj(void 0,b);sj(a,void 0,b);tj(void 0,b);F("DELEGATED_SESSION_ID")&&!N("pageid_as_header_web")&&
(b.user={onBehalfOfUser:F("DELEGATED_SESSION_ID")});a=Object;c=a.assign;for(var d=b.client,e={},f=t(Object.entries(Jh(F("DEVICE","")))),g=f.next();!g.done;g=f.next()){var h=t(g.value);g=h.next().value;h=h.next().value;"cbrand"===g?e.deviceMake=h:"cmodel"===g?e.deviceModel=h:"cbr"===g?e.browserName=h:"cbrver"===g?e.browserVersion=h:"cos"===g?e.osName=h:"cosver"===g?e.osVersion=h:"cplatform"===g&&(e.platform=h)}b.client=c.call(a,d,e);return b}
function Wi(a){var b=new zg,c=new sg;I(c,1,a.nb);I(c,2,a.mb);I(c,16,a.Lb);I(c,17,a.innertubeContextClientVersion);if(a.Sa){var d=a.Sa,e=new pg;d.coldConfigData&&I(e,1,d.coldConfigData);d.appInstallData&&I(e,6,d.appInstallData);d.coldHashData&&I(e,3,d.coldHashData);d.hotHashData&&I(e,5,d.hotHashData);ad(c,62,e)}(d=y.devicePixelRatio)&&1!=d&&I(c,65,d);d=F("EXPERIMENTS_TOKEN","");""!==d&&I(c,54,d);d=Yg();if(0<d.length){e=new ug;for(var f=0;f<d.length;f++){var g=new ng;I(g,1,d[f].key);g.setValue(d[f].value);
bd(e,15,g,ng)}ad(b,5,e)}pj(a,c);qj(a,c);rj(c);sj(a,c);tj(c);F("DELEGATED_SESSION_ID")&&!N("pageid_as_header_web")&&(a=new xg,I(a,3,F("DELEGATED_SESSION_ID")));a=t(Object.entries(Jh(F("DEVICE",""))));for(d=a.next();!d.done;d=a.next())e=t(d.value),d=e.next().value,e=e.next().value,"cbrand"===d?I(c,12,e):"cmodel"===d?I(c,13,e):"cbr"===d?I(c,87,e):"cbrver"===d?I(c,88,e):"cos"===d?I(c,18,e):"cosver"===d?I(c,19,e):"cplatform"===d&&I(c,42,e);ad(b,1,c);return b}
function pj(a,b,c){a=a.Ta;if("WEB"===a||"MWEB"===a||1===a||2===a)if(b){c=Zc(b,qg,96)||new qg;var d=cj();null!==d&&I(c,3,d);ad(b,96,c)}else c&&(c.client.mainAppWebInfo=null!=(d=c.client.mainAppWebInfo)?d:{},c.client.mainAppWebInfo.webDisplayMode=bj())}
function qj(a,b,c){a=a.Ta;if(("WEB_REMIX"===a||76===a)&&!N("music_web_display_mode_killswitch"))if(b){var d;c=null!=(d=Zc(b,rg,70))?d:new rg;d=cj();null!==d&&I(c,10,d);ad(b,70,c)}else if(c){var e;c.client.qb=null!=(e=c.client.qb)?e:{};c.client.qb.webDisplayMode=bj()}}
function rj(a,b){var c;if(N("web_log_memory_total_kbytes")&&(null==(c=y.navigator)?0:c.deviceMemory)){var d;c=null==(d=y.navigator)?void 0:d.deviceMemory;a?I(a,95,1E6*c):b&&(b.client.memoryTotalKbytes=""+1E6*c)}}
function sj(a,b,c){if(a.appInstallData)if(b){var d;c=null!=(d=Zc(b,pg,62))?d:new pg;I(c,6,a.appInstallData);ad(b,62,c)}else c&&(c.client.configInfo=c.client.configInfo||{},c.client.configInfo.appInstallData=a.appInstallData)}
function tj(a,b){a:{var c=nj();if(c){var d=jj[c.type||"unknown"]||"CONN_UNKNOWN";c=jj[c.effectiveType||"unknown"]||"CONN_UNKNOWN";"CONN_CELLULAR_UNKNOWN"===d&&"CONN_UNKNOWN"!==c&&(d=c);if("CONN_UNKNOWN"!==d)break a;if("CONN_UNKNOWN"!==c){d=c;break a}}d=void 0}d&&(a?I(a,61,kj[d]):b&&(b.client.connectionType=d));N("web_log_effective_connection_type")&&(d=nj(),d=null!==d&&void 0!==d&&d.effectiveType?mj.hasOwnProperty(d.effectiveType)?mj[d.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN":void 0,d&&
(a?I(a,94,lj[d]):b&&(b.client.effectiveConnectionType=d)))}
function uj(a,b,c){c=void 0===c?{}:c;var d={"X-Goog-Visitor-Id":c.visitorData||F("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;(b=c.jn||F("AUTHORIZATION"))||(a?b="Bearer "+C("gapi.auth.getToken")().hn:b=Td([]));b&&(d.Authorization=b,d["X-Goog-AuthUser"]=F("SESSION_INDEX",0),N("pageid_as_header_web")&&(d["X-Goog-PageId"]=F("DELEGATED_SESSION_ID")));return d}
;function vj(a){a=Object.assign({},a);delete a.Authorization;var b=Td();if(b){var c=new $e;c.update(F("INNERTUBE_API_KEY",void 0));c.update(b);a.hash=Hc(c.digest(),3)}return a}
;function wj(a){var b=new gg;(b=b.isAvailable()?a?new mg(b,a):b:null)||(a=new hg(a||"UserDataSharedStore"),b=a.isAvailable()?a:null);this.h=(a=b)?new cg(a):null;this.i=document.domain||window.location.hostname}
wj.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape(xf(b))}catch(f){return}else e=escape(b);dj(a,e,c,this.i)};
wj.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=Pd.get(""+a,void 0))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
wj.prototype.remove=function(a){this.h&&this.h.remove(a);var b=this.i;Pd.remove(""+a,"/",void 0===b?"youtube.com":b)};var xj;function yj(){xj||(xj=new wj("yt.innertube"));return xj}
function zj(a,b,c,d){if(d)return null;d=yj().get("nextId",!0)||1;var e=yj().get("requests",!0)||{};e[d]={method:a,request:b,authState:vj(c),requestTime:Math.round(O())};yj().set("nextId",d+1,86400,!0);yj().set("requests",e,86400,!0);return d}
function Aj(a){var b=yj().get("requests",!0)||{};delete b[a];yj().set("requests",b,86400,!0)}
function Bj(a){var b=yj().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(O())-d.requestTime)){var e=d.authState,f=vj(uj(!1));pb(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(O())),Ui(a,d.method,e,{}));delete b[c]}}yj().set("requests",b,86400,!0)}}
;var Cj=function(){var a;return function(){a||(a=new wj("ytidb"));return a}}();
function Dj(){var a;return null===(a=Cj())||void 0===a?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var Ej=[],Fj,Gj=!1;function Hj(a){Gj||(Fj?Fj.handleError(a):(Ej.push({type:"ERROR",payload:a}),10<Ej.length&&Ej.shift()))}
function Ij(a,b){Gj||(Fj?Fj.logEvent(a,b):(Ej.push({type:"EVENT",eventType:a,payload:b}),10<Ej.length&&Ej.shift()))}
;function Jj(a){var b=Ea.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(ha(b))}
v(Jj,Error);function Kj(){try{return Lj(),!0}catch(a){return!1}}
function Lj(){if(void 0!==F("DATASYNC_ID",void 0))return F("DATASYNC_ID",void 0);throw new Jj("Datasync ID not set","unknown");}
;function Mj(a){if(0<=a.indexOf(":"))throw Error("Database name cannot contain ':'");}
function Nj(a){return a.substr(0,a.indexOf(":"))||a}
;var Oj={},Pj=(Oj.AUTH_INVALID="No user identifier specified.",Oj.EXPLICIT_ABORT="Transaction was explicitly aborted.",Oj.IDB_NOT_SUPPORTED="IndexedDB is not supported.",Oj.MISSING_INDEX="Index not created.",Oj.MISSING_OBJECT_STORES="Object stores not created.",Oj.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",Oj.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",Oj.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",
Oj.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",Oj.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",Oj.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",Oj),Qj={},Rj=(Qj.AUTH_INVALID="ERROR",Qj.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",Qj.EXPLICIT_ABORT="IGNORED",Qj.IDB_NOT_SUPPORTED="ERROR",Qj.MISSING_INDEX="WARNING",Qj.MISSING_OBJECT_STORES="ERROR",Qj.DB_DELETED_BY_MISSING_OBJECT_STORES=
"WARNING",Qj.QUOTA_EXCEEDED="WARNING",Qj.QUOTA_MAYBE_EXCEEDED="WARNING",Qj.UNKNOWN_ABORT="WARNING",Qj.INCOMPATIBLE_DB_VERSION="WARNING",Qj),Sj={},Tj=(Sj.AUTH_INVALID=!1,Sj.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,Sj.EXPLICIT_ABORT=!1,Sj.IDB_NOT_SUPPORTED=!1,Sj.MISSING_INDEX=!1,Sj.MISSING_OBJECT_STORES=!1,Sj.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,Sj.QUOTA_EXCEEDED=!1,Sj.QUOTA_MAYBE_EXCEEDED=!0,Sj.UNKNOWN_ABORT=!0,Sj.INCOMPATIBLE_DB_VERSION=!1,Sj);
function P(a,b,c,d,e){b=void 0===b?{}:b;c=void 0===c?Pj[a]:c;d=void 0===d?Rj[a]:d;e=void 0===e?Tj[a]:e;Jj.call(this,c,Object.assign({name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,P.prototype)}
v(P,Jj);function Uj(a,b){P.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},Pj.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,Uj.prototype)}
v(Uj,P);function Vj(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,Vj.prototype)}
v(Vj,Error);var Wj=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function Xj(a,b,c,d){b=Nj(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof P)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if("QuotaExceededError"===e.name)return new P("QUOTA_EXCEEDED",a);if(Ec&&"UnknownError"===e.name)return new P("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof Vj)return new P("MISSING_INDEX",Object.assign(Object.assign({},a),{objectStore:e.objectStore,index:e.index}));if("InvalidStateError"===e.name&&Wj.some(function(f){return e.message.includes(f)}))return new P("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if("AbortError"===e.name)return new P("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign(Object.assign({},a),{name:"IdbError",sn:e.name})];e.level="WARNING";return e}
function Yj(a,b,c){var d=Dj();return new P("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:null===d||void 0===d?void 0:d.hasSucceededOnce}})}
;function Zj(a){if(!a)throw Error();throw a;}
function ak(a){return a}
function bk(a){this.h=a}
function Q(a){function b(e){if("PENDING"===d.state.status){d.state={status:"REJECTED",reason:e};e=t(d.onRejected);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if("PENDING"===d.state.status){d.state={status:"FULFILLED",value:e};e=t(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.h=[];this.onRejected=[];a=a.h;try{a(c,b)}catch(e){b(e)}}
Q.all=function(a){return new Q(new bk(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={ma:0};f.ma<a.length;f={ma:f.ma},++f.ma)ck(Q.resolve(a[f.ma]).then(function(g){return function(h){d[g.ma]=h;e--;0===e&&b(d)}}(f)),function(g){c(g)})}))};
Q.resolve=function(a){return new Q(new bk(function(b,c){a instanceof Q?a.then(b,c):b(a)}))};
Q.reject=function(a){return new Q(new bk(function(b,c){c(a)}))};
Q.prototype.then=function(a,b){var c=this,d=null!==a&&void 0!==a?a:ak,e=null!==b&&void 0!==b?b:Zj;return new Q(new bk(function(f,g){"PENDING"===c.state.status?(c.h.push(function(){dk(c,c,d,f,g)}),c.onRejected.push(function(){ek(c,c,e,f,g)})):"FULFILLED"===c.state.status?dk(c,c,d,f,g):"REJECTED"===c.state.status&&ek(c,c,e,f,g)}))};
function ck(a,b){a.then(void 0,b)}
function dk(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof Q?fk(a,b,f,d,e):d(f)}catch(g){e(g)}}
function ek(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof Q?fk(a,b,f,d,e):d(f)}catch(g){e(g)}}
function fk(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof Q?fk(a,b,f,d,e):d(f)},function(f){e(f)})}
;function gk(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function hk(a){return new Promise(function(b,c){gk(a,b,c)})}
function ik(a){return new Q(new bk(function(b,c){gk(a,b,c)}))}
;function jk(a,b){return new Q(new bk(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;function kk(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(O());this.i=!1}
m=kk.prototype;m.add=function(a,b,c){return lk(this,[a],{mode:"readwrite",N:!0},function(d){return d.objectStore(a).add(b,c)})};
m.clear=function(a){return lk(this,[a],{mode:"readwrite",N:!0},function(b){return b.objectStore(a).clear()})};
m.close=function(){var a;this.h.close();(null===(a=this.options)||void 0===a?0:a.closed)&&this.options.closed()};
m.count=function(a,b){return lk(this,[a],{mode:"readonly",N:!0},function(c){return c.objectStore(a).count(b)})};
function mk(a,b,c){a=a.h.createObjectStore(b,c);return new nk(a)}
m.delete=function(a,b){return lk(this,[a],{mode:"readwrite",N:!0},function(c){return c.objectStore(a).delete(b)})};
m.get=function(a,b){return lk(this,[a],{mode:"readonly",N:!0},function(c){return c.objectStore(a).get(b)})};
function ok(a,b){return lk(a,["LogsRequestsStore"],{mode:"readwrite",N:!0},function(c){c=c.objectStore("LogsRequestsStore");return ik(c.h.put(b,void 0))})}
m.objectStoreNames=function(){return Array.from(this.h.objectStoreNames)};
function lk(a,b,c,d){var e,f,g,h,k,l,n,p,u,r,z,A;return x(function(J){switch(J.h){case 1:var R={mode:"readonly",N:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};"string"===typeof c?R.mode=c:Object.assign(R,c);e=R;a.transactionCount++;f=e.N?3:1;g=0;case 2:if(h){J.o(3);break}g++;k=Math.round(O());ta(J,4);l=a.h.transaction(b,e.mode);R=new pk(l);R=qk(R,d);return w(J,R,6);case 6:return n=J.i,p=Math.round(O()),rk(a,k,p,g,void 0,b.join(),e),J.return(n);case 4:u=va(J);r=Math.round(O());z=Xj(u,a.h.name,b.join(),a.h.version);
if((A=z instanceof P&&!z.h)||g>=f)rk(a,k,r,g,z,b.join(),e),h=z;J.o(2);break;case 3:return J.return(Promise.reject(h))}})}
function rk(a,b,c,d,e,f,g){b=c-b;e?(e instanceof P&&("QUOTA_EXCEEDED"===e.type||"QUOTA_MAYBE_EXCEEDED"===e.type)&&Ij("QUOTA_EXCEEDED",{dbName:Nj(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof P&&"UNKNOWN_ABORT"===e.type&&(c-=a.j,0>c&&c>=Math.pow(2,31)&&(c=0),Ij("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.i=!0),sk(a,!1,d,f,b,g.tag),Hj(e)):sk(a,!0,d,f,b,g.tag)}
function sk(a,b,c,d,e,f){Ij("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c,tag:void 0===f?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
m.getName=function(){return this.h.name};
function nk(a){this.h=a}
m=nk.prototype;m.add=function(a,b){return ik(this.h.add(a,b))};
m.autoIncrement=function(){return this.h.autoIncrement};
m.clear=function(){return ik(this.h.clear()).then(function(){})};
m.count=function(a){return ik(this.h.count(a))};
function tk(a,b){return uk(a,{query:b},function(c){return c.delete().then(function(){return c.continue()})}).then(function(){})}
m.delete=function(a){return a instanceof IDBKeyRange?tk(this,a):ik(this.h.delete(a))};
m.get=function(a){return ik(this.h.get(a))};
m.index=function(a){try{return new vk(this.h.index(a))}catch(b){if(b instanceof Error&&"NotFoundError"===b.name)throw new Vj(a,this.h.name);throw b;}};
m.getName=function(){return this.h.name};
m.keyPath=function(){return this.h.keyPath};
function uk(a,b,c){a=a.h.openCursor(b.query,b.direction);return wk(a).then(function(d){return jk(d,c)})}
function pk(a){var b=this;this.h=a;this.j=new Map;this.i=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.i){e=P;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(null===k)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function qk(a,b){var c=new Promise(function(d,e){try{ck(b(a).then(function(f){d(f)}),e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return t(d).next().value})}
pk.prototype.abort=function(){this.h.abort();this.i=!0;throw new P("EXPLICIT_ABORT");};
pk.prototype.objectStore=function(a){a=this.h.objectStore(a);var b=this.j.get(a);b||(b=new nk(a),this.j.set(a,b));return b};
function vk(a){this.h=a}
m=vk.prototype;m.count=function(a){return ik(this.h.count(a))};
m.delete=function(a){return xk(this,{query:a},function(b){return b.delete().then(function(){return b.continue()})})};
m.get=function(a){return ik(this.h.get(a))};
m.getKey=function(a){return ik(this.h.getKey(a))};
m.keyPath=function(){return this.h.keyPath};
m.unique=function(){return this.h.unique};
function xk(a,b,c){a=a.h.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return wk(a).then(function(d){return jk(d,c)})}
function yk(a,b){this.request=a;this.cursor=b}
function wk(a){return ik(a).then(function(b){return b?new yk(a,b):null})}
m=yk.prototype;m.advance=function(a){this.cursor.advance(a);return wk(this.request)};
m.continue=function(a){this.cursor.continue(a);return wk(this.request)};
m.delete=function(){return ik(this.cursor.delete()).then(function(){})};
m.getKey=function(){return this.cursor.key};
m.getValue=function(){return this.cursor.value};
m.update=function(a){return ik(this.cursor.update(a))};function zk(a,b,c){return new Promise(function(d,e){function f(){u||(u=new kk(g.result,{closed:p}));return u}
var g=void 0!==b?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.blocked,k=c.blocking,l=c.jc,n=c.upgrade,p=c.closed,u;g.addEventListener("upgradeneeded",function(r){try{if(null===r.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(null===g.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");r.dataLoss&&"none"!==r.dataLoss&&Ij("IDB_DATA_CORRUPTED",{reason:r.dataLossMessage||"unknown reason",dbName:Nj(a)});var z=f(),A=new pk(g.transaction);
n&&n(z,function(J){return r.oldVersion<J&&r.newVersion>=J},A);
A.done.catch(function(J){e(J)})}catch(J){e(J)}});
g.addEventListener("success",function(){var r=g.result;k&&r.addEventListener("versionchange",function(){k(f())});
r.addEventListener("close",function(){Ij("IDB_UNEXPECTEDLY_CLOSED",{dbName:Nj(a),dbVersion:r.version});l&&l()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function Ak(a,b,c){c=void 0===c?{}:c;return zk(a,b,c)}
function Bk(a,b){b=void 0===b?{}:b;var c,d,e,f;return x(function(g){if(1==g.h)return ta(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.blocked)&&c.addEventListener("blocked",function(){e()}),w(g,hk(c),4);
if(2!=g.h)return ua(g,0);f=va(g);throw Xj(f,a,"",-1);})}
;function Ck(a){return new Promise(function(b){rh(function(){b()},a)})}
function Dk(a,b){this.name=a;this.options=b;this.l=!0;this.A=0;this.i=500}
Dk.prototype.j=function(a,b,c){c=void 0===c?{}:c;return Ak(a,b,c)};
Dk.prototype.delete=function(a){a=void 0===a?{}:a;return Bk(this.name,a)};
function Ek(a,b){return new P("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function Fk(a,b){if(!b)throw Yj("openWithToken",Nj(a.name));return a.open()}
Dk.prototype.open=function(){function a(){var f,g,h,k,l,n,p,u,r,z;return x(function(A){switch(A.h){case 1:return h=null!==(f=Error().stack)&&void 0!==f?f:"",ta(A,2),w(A,c.j(c.name,c.options.version,e),4);case 4:k=A.i;for(var J=c.options,R=[],S=t(Object.keys(J.ta)),U=S.next();!U.done;U=S.next()){U=U.value;var Pc=J.ta[U],ag=void 0===Pc.Vb?Number.MAX_VALUE:Pc.Vb;!(k.h.version>=Pc.La)||k.h.version>=ag||k.h.objectStoreNames.contains(U)||R.push(U)}l=R;if(0===l.length){A.o(5);break}n=Object.keys(c.options.ta);
p=k.objectStoreNames();if(!(c.A<Xg("ytidb_remake_db_retries",1))){A.o(6);break}c.A++;if(!N("ytidb_remake_db_enable_backoff_delay")){A.o(7);break}return w(A,Ck(c.i),8);case 8:c.i*=2;case 7:return w(A,c.delete(),9);case 9:return Hj(new P("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:n,foundObjectStores:p})),A.return(a());case 6:throw new Uj(p,n);case 5:return A.return(k);case 2:u=va(A);if(u instanceof DOMException?"VersionError"!==u.name:"DOMError"in self&&u instanceof DOMError?
"VersionError"!==u.name:!(u instanceof Object&&"message"in u)||"An attempt was made to open a database using a lower version than the existing version."!==u.message){A.o(10);break}return w(A,c.j(c.name,void 0,Object.assign(Object.assign({},e),{upgrade:void 0})),11);case 11:r=A.i;z=r.h.version;if(void 0!==c.options.version&&z>c.options.version+1)throw r.close(),c.l=!1,Ek(c,z);return A.return(r);case 10:throw b(),u instanceof Error&&!N("ytidb_async_stack_killswitch")&&(u.stack=u.stack+"\n"+h.substring(h.indexOf("\n")+
1)),Xj(u,c.name,"",null!==(g=c.options.version)&&void 0!==g?g:-1);}})}
function b(){c.h===d&&(c.h=void 0)}
var c=this;if(!this.l)throw Ek(this);if(this.h)return this.h;var d,e={blocking:function(f){f.close()},
closed:b,jc:b,upgrade:this.options.upgrade};return this.h=d=a()};var Gk=new Dk("YtIdbMeta",{ta:{databases:{La:1}},upgrade:function(a,b){b(1)&&mk(a,"databases",{keyPath:"actualName"})}});
function Hk(a,b){var c;return x(function(d){if(1==d.h)return w(d,Fk(Gk,b),2);c=d.i;return d.return(lk(c,["databases"],{N:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return ik(f.h.put(a,void 0)).then(function(){})})}))})}
function Ik(a,b){var c;return x(function(d){if(1==d.h)return a?w(d,Fk(Gk,b),2):d.return();c=d.i;return d.return(c.delete("databases",a))})}
function Jk(a,b){var c,d;return x(function(e){return 1==e.h?(c=[],w(e,Fk(Gk,b),2)):3!=e.h?(d=e.i,w(e,lk(d,["databases"],{N:!0,mode:"readonly"},function(f){c.length=0;return uk(f.objectStore("databases"),{},function(g){a(g.getValue())&&c.push(g.getValue());return g.continue()})}),3)):e.return(c)})}
function Kk(a){return Jk(function(b){return"LogsDatabaseV2"===b.publicName&&void 0!==b.userIdentifier},a)}
;var Lk,Mk=new function(){}(new function(){});
function Nk(){var a,b,c;return x(function(d){switch(d.h){case 1:a=Dj();if(null===a||void 0===a?0:a.hasSucceededOnce)return d.return(!0);var e;if(e=ei)e=/WebKit\/([0-9]+)/.exec(Ub()),e=!!(e&&600<=parseInt(e[1],10));e&&(e=/WebKit\/([0-9]+)/.exec(Ub()),e=!(e&&602<=parseInt(e[1],10)));if(e||pc)return d.return(!1);try{if(b=self,!(b.indexedDB&&b.IDBIndex&&b.IDBKeyRange&&b.IDBObjectStore))return d.return(!1)}catch(f){return d.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return d.return(!1);
ta(d,2);c={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return w(d,Hk(c,Mk),4);case 4:return w(d,Ik("yt-idb-test-do-not-use",Mk),5);case 5:return d.return(!0);case 2:return va(d),d.return(!1)}})}
function Ok(){if(void 0!==Lk)return Lk;Gj=!0;return Lk=Nk().then(function(a){Gj=!1;var b,c;null!==(b=Cj())&&void 0!==b&&b.h&&(b=Dj(),b={hasSucceededOnce:(null===b||void 0===b?void 0:b.hasSucceededOnce)||a},null===(c=Cj())||void 0===c?void 0:c.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0));return a})}
function Pk(){return C("ytglobal.idbToken_")||void 0}
function Qk(){var a=Pk();return a?Promise.resolve(a):Ok().then(function(b){(b=b?Mk:void 0)&&B("ytglobal.idbToken_",b,void 0);return b})}
;new ed;function Rk(a){if(!Kj())throw a=new P("AUTH_INVALID",{dbName:a}),Hj(a),a;var b=Lj();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function Sk(a,b,c,d){var e,f,g,h,k,l;return x(function(n){switch(n.h){case 1:return f=null!==(e=Error().stack)&&void 0!==e?e:"",w(n,Qk(),2);case 2:g=n.i;if(!g)throw h=Yj("openDbImpl",a,b),N("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),Hj(h),h;Mj(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:Rk(a);ta(n,3);return w(n,Hk(k,g),5);case 5:return w(n,Ak(k.actualName,b,d),6);case 6:return n.return(n.i);case 3:return l=va(n),ta(n,7),w(n,Ik(k.actualName,
g),9);case 9:ua(n,8);break;case 7:va(n);case 8:throw l;}})}
function Tk(a,b,c){c=void 0===c?{}:c;return Sk(a,b,!1,c)}
function Uk(a,b,c){c=void 0===c?{}:c;return Sk(a,b,!0,c)}
function Vk(a,b){b=void 0===b?{}:b;var c,d;return x(function(e){if(1==e.h)return w(e,Qk(),2);if(3!=e.h){c=e.i;if(!c)return e.return();Mj(a);d=Rk(a);return w(e,Bk(d.actualName,b),3)}return w(e,Ik(d.actualName,c),0)})}
function Wk(a,b,c){a=a.map(function(d){return x(function(e){return 1==e.h?w(e,Bk(d.actualName,b),2):w(e,Ik(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function Xk(){var a=void 0===a?{}:a;var b,c;return x(function(d){if(1==d.h)return w(d,Qk(),2);if(3!=d.h){b=d.i;if(!b)return d.return();Mj("LogsDatabaseV2");return w(d,Kk(b),3)}c=d.i;return w(d,Wk(c,a,b),0)})}
function Yk(a,b){b=void 0===b?{}:b;var c;return x(function(d){if(1==d.h)return w(d,Qk(),2);if(3!=d.h){c=d.i;if(!c)return d.return();Mj(a);return w(d,Bk(a,b),3)}return w(d,Ik(a,c),0)})}
;function Zk(a){var b,c,d,e,f,g,h,k;this.h=!1;this.potentialEsfErrorCounter=this.i=0;this.handleError=function(){};
this.qa=function(){};
this.now=Date.now;this.sa=!1;this.zb=null!==(b=a.zb)&&void 0!==b?b:100;this.wb=null!==(c=a.wb)&&void 0!==c?c:1;this.ub=null!==(d=a.ub)&&void 0!==d?d:2592E6;this.sb=null!==(e=a.sb)&&void 0!==e?e:12E4;this.vb=null!==(f=a.vb)&&void 0!==f?f:5E3;this.B=null!==(g=a.B)&&void 0!==g?g:void 0;this.Da=!!a.Da;this.Ca=null!==(h=a.Ca)&&void 0!==h?h:.1;this.Ha=null!==(k=a.Ha)&&void 0!==k?k:10;a.handleError&&(this.handleError=a.handleError);a.qa&&(this.qa=a.qa);a.sa&&(this.sa=a.sa);this.D=a.D;this.S=a.S;this.I=a.I;
this.L=a.L;this.Y=a.Y;this.Xa=a.Xa;this.Wa=a.Wa;this.B&&(!this.D||this.D("networkless_logging"))&&$k(this)}
function $k(a){return x(function(b){if(1==b.h)return!a.B||a.sa?b.return():a.Da&&Math.random()<=a.Ca?w(b,a.I.Fb(a.B),2):b.o(2);al(a);a.L.H()&&a.wa();a.L.V(a.Xa,a.wa.bind(a));a.L.V(a.Wa,a.eb.bind(a));a.h=!0;b.h=0})}
m=Zk.prototype;m.writeThenSend=function(a,b){var c=this;b=void 0===b?{}:b;if(this.B&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.I.set(d,this.B).then(function(e){d.id=e;c.L.H()&&bl(c,d)}).catch(function(e){bl(c,d);
cl(c,e)})}else this.Y(a,b)};
m.sendThenWrite=function(a,b,c){var d=this;b=void 0===b?{}:b;if(this.B&&this.h){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.D&&this.D("nwl_skip_retry")&&(e.skipRetry=c);if(this.L.H()||this.D&&this.D("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return x(function(k){if(1==k.h)return w(k,d.I.set(e,d.B).catch(function(l){cl(d,l)}),2);
f(g,h);k.h=0})}}this.Y(a,b,e.skipRetry)}else this.I.set(e,this.B).catch(function(g){d.Y(a,b,e.skipRetry);
cl(d,g)})}else this.Y(a,b,this.D&&this.D("nwl_skip_retry")&&c)};
m.sendAndWrite=function(a,b){var c=this;b=void 0===b?{}:b;if(this.B&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){void 0!==d.id?c.I.oa(d.id,c.B):e=!0;c.L.ga&&c.D&&c.D("vss_network_hint")&&c.L.ga(!0);f(g,h)};
this.Y(d.url,d.options);this.I.set(d,this.B).then(function(g){d.id=g;e&&c.I.oa(d.id,c.B)}).catch(function(g){cl(c,g)})}else this.Y(a,b)};
m.wa=function(){var a=this;if(!this.B)throw Yj("throttleSend");this.i||(this.i=this.S.M(function(){var b;return x(function(c){if(1==c.h)return w(c,a.I.lb("NEW",a.B),2);if(3!=c.h)return b=c.i,b?w(c,bl(a,b),3):(a.eb(),c.return());a.i&&(a.i=0,a.wa());c.h=0})},this.zb))};
m.eb=function(){this.S.ca(this.i);this.i=0};
function bl(a,b){var c,d;return x(function(e){switch(e.h){case 1:if(!a.B)throw c=Yj("immediateSend"),c;if(void 0===b.id){e.o(2);break}return w(e,a.I.Pb(b.id,a.B),3);case 3:(d=e.i)?b=d:a.qa(Error("The request cannot be found in the database."));case 2:if(dl(a,b,a.ub)){e.o(4);break}a.qa(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===b.id){e.o(5);break}return w(e,a.I.oa(b.id,a.B),5);case 5:return e.return();case 4:b.skipRetry||(b=el(a,b));if(!b){e.o(0);break}if(!b.skipRetry||
void 0===b.id){e.o(8);break}return w(e,a.I.oa(b.id,a.B),8);case 8:a.Y(b.url,b.options,!!b.skipRetry),e.h=0}})}
function el(a,b){if(!a.B)throw Yj("updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g;return x(function(h){switch(h.h){case 1:g=fl(f);if(!(a.D&&a.D("nwl_consider_error_code")&&g||a.D&&!a.D("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.Ha)){h.o(2);break}if(!a.L.Z){h.o(3);break}return w(h,a.L.Z(),3);case 3:if(a.L.H()){h.o(2);break}c(e,f);if(!a.D||!a.D("nwl_consider_error_code")||void 0===(null===b||void 0===b?void 0:b.id)){h.o(6);break}return w(h,a.I.Ya(b.id,a.B,!1),6);case 6:return h.return();case 2:if(a.D&&a.D("nwl_consider_error_code")&&
!g&&a.potentialEsfErrorCounter>a.Ha)return h.return();a.potentialEsfErrorCounter++;if(void 0===(null===b||void 0===b?void 0:b.id)){h.o(8);break}return b.sendCount<a.wb?w(h,a.I.Ya(b.id,a.B),12):w(h,a.I.oa(b.id,a.B),8);case 12:a.S.M(function(){a.L.H()&&a.wa()},a.vb);
case 8:c(e,f),h.h=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){return x(function(g){if(1==g.h)return void 0===(null===b||void 0===b?void 0:b.id)?g.o(2):w(g,a.I.oa(b.id,a.B),2);a.L.ga&&a.D&&a.D("vss_network_hint")&&a.L.ga(!0);d(e,f);g.h=0})};
return b}
function dl(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function al(a){if(!a.B)throw Yj("retryQueuedRequests");a.I.lb("QUEUED",a.B).then(function(b){b&&!dl(a,b,a.sb)?a.S.M(function(){return x(function(c){if(1==c.h)return void 0===b.id?c.o(2):w(c,a.I.Ya(b.id,a.B),2);al(a);c.h=0})}):a.L.H()&&a.wa()})}
function cl(a,b){a.Ab&&!a.L.H()?a.Ab(b):a.handleError(b)}
function fl(a){var b;return(a=null===(b=null===a||void 0===a?void 0:a.error)||void 0===b?void 0:b.code)&&400<=a&&599>=a?!1:!0}
;function gl(a,b){this.version=a;this.args=b}
;function hl(a,b){this.topic=a;this.h=b}
hl.prototype.toString=function(){return this.topic};var il=C("ytPubsub2Pubsub2Instance")||new L;L.prototype.subscribe=L.prototype.subscribe;L.prototype.unsubscribeByKey=L.prototype.ra;L.prototype.publish=L.prototype.ja;L.prototype.clear=L.prototype.clear;B("ytPubsub2Pubsub2Instance",il,void 0);var jl=C("ytPubsub2Pubsub2SubscribedKeys")||{};B("ytPubsub2Pubsub2SubscribedKeys",jl,void 0);var kl=C("ytPubsub2Pubsub2TopicToKeys")||{};B("ytPubsub2Pubsub2TopicToKeys",kl,void 0);var ll=C("ytPubsub2Pubsub2IsAsync")||{};B("ytPubsub2Pubsub2IsAsync",ll,void 0);
B("ytPubsub2Pubsub2SkipSubKey",null,void 0);function ml(a,b){var c=nl();c&&c.publish.call(c,a.toString(),a,b)}
function ol(a){var b=pl,c=nl();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=C("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(jl[d])try{if(f&&b instanceof hl&&b!=e)try{var h=b.h,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.ia){var l=new h;h.ia=l.version}var n=h.ia}catch(p){}if(!n||k.version!=n)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{f=Reflect.construct(h,
hb(k.args))}catch(p){throw p.message="yt.pubsub2.Data.deserialize(): "+p.message,p;}}catch(p){throw p.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+p.message,p;}a.call(window,f)}catch(p){Sg(p)}},ll[b.toString()]?C("yt.scheduler.instance")?uh.M(g):lh(g,0):g())});
jl[d]=!0;kl[b.toString()]||(kl[b.toString()]=[]);kl[b.toString()].push(d);return d}
function ql(){var a=rl,b=ol(function(c){a.apply(void 0,arguments);sl(b)});
return b}
function sl(a){var b=nl();b&&("number"===typeof a&&(a=[a]),E(a,function(c){b.unsubscribeByKey(c);delete jl[c]}))}
function nl(){return C("ytPubsub2Pubsub2Instance")}
;function tl(a,b){Dk.call(this,a,b);this.options=b;Mj(a)}
v(tl,Dk);function ul(a,b){var c;return function(){c||(c=new tl(a,b));return c}}
tl.prototype.j=function(a,b,c){c=void 0===c?{}:c;return(this.options.Za?Uk:Tk)(a,b,Object.assign({},c))};
tl.prototype.delete=function(a){a=void 0===a?{}:a;return(this.options.Za?Yk:Vk)(this.name,a)};
function vl(a,b){return ul(a,b)}
;var wl;
function xl(){if(wl)return wl();var a={};wl=vl("LogsDatabaseV2",{ta:(a.LogsRequestsStore={La:2},a),Za:!1,upgrade:function(b,c,d){c(2)&&mk(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.h.indexNames.contains("newRequest")&&d.h.deleteIndex("newRequest"),d.h.createIndex("newRequestV2",["status","interface","timestamp"],{unique:!1}));c(7)&&b.h.objectStoreNames.contains("sapisid")&&b.h.deleteObjectStore("sapisid");c(9)&&b.h.objectStoreNames.contains("SWHealthLog")&&b.h.deleteObjectStore("SWHealthLog")},
version:9});return wl()}
;function yl(a){return Fk(xl(),a)}
function zl(a,b){var c,d,e,f;return x(function(g){if(1==g.h)return c={startTime:O(),transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},w(g,yl(b),2);if(3!=g.h)return d=g.i,e=Object.assign(Object.assign({},a),{options:JSON.parse(JSON.stringify(a.options)),interface:F("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),w(g,ok(d,e),3);f=g.i;c.kc=O();Al(c);return g.return(f)})}
function Bl(a,b){var c,d,e,f,g,h,k;return x(function(l){if(1==l.h)return c={startTime:O(),transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},w(l,yl(b),2);if(3!=l.h)return d=l.i,e=F("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,O()],h=IDBKeyRange.bound(f,g),k=void 0,w(l,lk(d,["LogsRequestsStore"],{mode:"readwrite",N:!0},function(n){return xk(n.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:"prev"},function(p){p.getValue()&&(k=p.getValue(),"NEW"===a&&(k.status="QUEUED",
p.update(k)))})}),3);
c.kc=O();Al(c);return l.return(k)})}
function Cl(a,b){var c;return x(function(d){if(1==d.h)return w(d,yl(b),2);c=d.i;return d.return(lk(c,["LogsRequestsStore"],{mode:"readwrite",N:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",ik(f.h.put(g,void 0)).then(function(){return g})})}))})}
function Dl(a,b,c){c=void 0===c?!0:c;var d;return x(function(e){if(1==e.h)return w(e,yl(b),2);d=e.i;return e.return(lk(d,["LogsRequestsStore"],{mode:"readwrite",N:!0},function(f){var g=f.objectStore("LogsRequestsStore");return g.get(a).then(function(h){return h?(h.status="NEW",c&&(h.sendCount+=1),ik(g.h.put(h,void 0)).then(function(){return h})):Q.resolve(void 0)})}))})}
function El(a,b){var c;return x(function(d){if(1==d.h)return w(d,yl(b),2);c=d.i;return d.return(c.delete("LogsRequestsStore",a))})}
function Fl(a){var b,c;return x(function(d){if(1==d.h)return w(d,yl(a),2);b=d.i;c=O()-2592E6;return w(d,lk(b,["LogsRequestsStore"],{mode:"readwrite",N:!0},function(e){return uk(e.objectStore("LogsRequestsStore"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function Gl(){return x(function(a){return w(a,Xk(),0)})}
function Al(a){N("nwl_csi_killswitch")||.01>=Math.random()&&ml("nwl_transaction_latency_payload",a)}
;var Hl={},Il=vl("ServiceWorkerLogsDatabase",{ta:(Hl.SWHealthLog={La:1},Hl),Za:!0,upgrade:function(a,b){b(1)&&mk(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}).h.createIndex("swHealthNewRequest",["interface","timestamp"],{unique:!1})},
version:1});function Jl(a){return Fk(Il(),a)}
function Kl(a){var b,c;return x(function(d){if(1==d.h)return w(d,Jl(a),2);b=d.i;c=O()-2592E6;return w(d,lk(b,["SWHealthLog"],{mode:"readwrite",N:!0},function(e){return uk(e.objectStore("SWHealthLog"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function Ll(a){var b;return x(function(c){if(1==c.h)return w(c,Jl(a),2);b=c.i;return w(c,b.clear("SWHealthLog"),0)})}
;function Ml(){this.h=new Map;this.i=!1}
function Nl(){if(!Ml.h){var a=C("yt.networkRequestMonitor.instance")||new Ml;B("yt.networkRequestMonitor.instance",a,void 0);Ml.h=a}return Ml.h}
Ml.prototype.X=function(a,b){b&&(this.i=!0);a=a.split("?")[0];this.h.get(a)||this.h.set(a,b)};
Ml.prototype.ob=function(a){return(a=this.h.get(a.split("?")[0]))?!1:!1===a&&this.i?!0:null};
Ml.prototype.isEndpointCFR=Ml.prototype.ob;Ml.prototype.requestComplete=Ml.prototype.X;Ml.getInstance=Nl;var Ol;function Pl(){Ol||(Ol=new wj("yt.offline"));return Ol}
function Ql(a){if(N("offline_error_handling")){var b=Pl().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);Pl().set("errors",b,2592E3,!0)}}
function Rl(){if(N("offline_error_handling")){var a=Pl().get("errors",!0);if(a){for(var b in a)if(a[b]){var c=new Jj(b,"sent via offline_errors");c.name=a[b].name;c.stack=a[b].stack;c.level=a[b].level;Sg(c)}Pl().set("errors",{},2592E3,!0)}}}
;var Sl=Xg("network_polling_interval",3E4);function T(){ze.call(this);this.K=0;this.P=this.m=!1;this.l=this.Qa();N("use_shared_nsm")?(Ce.h||(Ce.h=new Ce(uh)),this.j=Ce.h):(Tl(this),Ul(this))}
v(T,ze);function Vl(){if(!T.h){var a=C("yt.networkStatusManager.instance")||new T;B("yt.networkStatusManager.instance",a,void 0);T.h=a}return T.h}
m=T.prototype;m.H=function(){var a;return N("use_shared_nsm")&&this.j?null===(a=this.j)||void 0===a?void 0:a.H():this.l};
m.ga=function(a){var b;N("use_shared_nsm")&&this.j?null===(b=this.j)||void 0===b?void 0:b.j=a:a!==this.l&&(this.l=a)};
m.Qb=function(a){!N("use_shared_nsm")&&(this.m=!0,void 0===a?0:a)&&(this.K||Wl(this))};
m.Qa=function(){var a=window.navigator.onLine;return void 0===a?!0:a};
m.Hb=function(){this.P=!0};
m.V=function(a,b){return N("use_shared_nsm")&&this.j?this.j.V(a,b):ze.prototype.V.call(this,a,b)};
function Ul(a){window.addEventListener("online",function(){return x(function(b){if(1==b.h)return w(b,a.Z(),2);a.P&&Rl();b.h=0})})}
function Tl(a){window.addEventListener("offline",function(){return x(function(b){return w(b,a.Z(),0)})})}
function Wl(a){a.K=ph(function(){return x(function(b){if(1==b.h)return a.l?a.Qa()||!a.m?b.o(3):w(b,a.Z(),3):w(b,a.Z(),3);Wl(a);b.h=0})},Sl)}
m.Z=function(a){var b=this;if(N("use_shared_nsm")&&this.j){var c=De(this.j,a);c.then(function(d){N("use_cfr_monitor")&&Nl().X("generate_204",d)});
return c}return this.u?this.u:this.u=new Promise(function(d){var e,f,g;return x(function(h){switch(h.h){case 1:return e=window.AbortController?new window.AbortController:void 0,f=null===e||void 0===e?void 0:e.signal,g=!1,ta(h,2,3),e&&(b.C=uh.M(function(){e.abort()},a||2E4)),w(h,fetch("/generate_204",{method:"HEAD",
signal:f}),5);case 5:g=!0;case 3:wa(h);N("use_cfr_monitor")&&Nl().X("generate_204",g);b.u=void 0;b.C&&uh.ca(b.C);g!==b.l&&(b.l=g,b.l&&b.m?Ae(b,"ytnetworkstatus-online"):b.m&&Ae(b,"ytnetworkstatus-offline"));d(g);xa(h);break;case 2:va(h),g=!1,h.o(3)}})})};
T.prototype.sendNetworkCheckRequest=T.prototype.Z;T.prototype.listen=T.prototype.V;T.prototype.enableErrorFlushing=T.prototype.Hb;T.prototype.getWindowStatus=T.prototype.Qa;T.prototype.monitorNetworkStatusChange=T.prototype.Qb;T.prototype.networkStatusHint=T.prototype.ga;T.prototype.isNetworkAvailable=T.prototype.H;T.getInstance=Vl;function Xl(a){a=void 0===a?{}:a;ze.call(this);var b=this;this.l=this.K=0;this.m="ytnetworkstatus-offline";this.u="ytnetworkstatus-online";N("use_shared_nsm")&&(this.m="networkstatus-offline",this.u="networkstatus-online");this.j=Vl();var c=C("yt.networkStatusManager.instance.monitorNetworkStatusChange").bind(this.j);c&&c(a.jb);a.Fa&&!N("use_shared_nsm")&&(c=C("yt.networkStatusManager.instance.enableErrorFlushing").bind(this.j))&&c();if(c=C("yt.networkStatusManager.instance.listen").bind(this.j))a.Ia?
(this.Ia=a.Ia,c(this.u,function(){Yl(b,"publicytnetworkstatus-online");N("use_shared_nsm")&&a.Fa&&Rl()}),c(this.m,function(){Yl(b,"publicytnetworkstatus-offline")})):(c(this.u,function(){Ae(b,"publicytnetworkstatus-online");
N("use_shared_nsm")&&a.Fa&&Rl()}),c(this.m,function(){Ae(b,"publicytnetworkstatus-offline")}))}
v(Xl,ze);Xl.prototype.H=function(){var a=C("yt.networkStatusManager.instance.isNetworkAvailable").bind(this.j);return a?a():!0};
Xl.prototype.ga=function(a){var b=C("yt.networkStatusManager.instance.networkStatusHint").bind(this.j);b&&b(a)};
Xl.prototype.Z=function(a){var b=this,c;return x(function(d){return(c=C("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.j))?d.return(c(a)):d.return(!0)})};
function Yl(a,b){a.Ia?a.l?(uh.ca(a.K),a.K=uh.M(function(){a.C!==b&&(Ae(a,b),a.C=b,a.l=O())},a.Ia-(O()-a.l))):(Ae(a,b),a.C=b,a.l=O()):Ae(a,b)}
;var Zl;function $l(){Zk.call(this,{I:{Fb:Fl,oa:El,lb:Bl,Pb:Cl,Ya:Dl,set:zl},L:am(),handleError:Sg,qa:Tg,Y:bm,now:O,Ab:Ql,S:th(),Xa:"publicytnetworkstatus-online",Wa:"publicytnetworkstatus-offline",Da:!0,Ca:.1,Ha:Xg("potential_esf_error_limit",10),D:N,sa:!Kj()});this.j=new ed;this.Da&&Math.random()<=this.Ca&&this.B&&Kl(this.B);N("networkless_immediately_drop_sw_health_store")&&cm(this);N("networkless_immediately_drop_all_requests")&&Gl();Yk("LogsDatabaseV2")}
v($l,Zk);function dm(){var a=C("yt.networklessRequestController.instance");a||(a=new $l,B("yt.networklessRequestController.instance",a,void 0),N("networkless_logging")&&Qk().then(function(b){return x(function(c){if(1==c.h)return a.B=b,w(c,$k(a),2);a.j.resolve();c.h=0})}));
return a}
$l.prototype.writeThenSend=function(a,b){b||(b={});Kj()||(this.h=!1);Zk.prototype.writeThenSend.call(this,a,b)};
$l.prototype.sendThenWrite=function(a,b,c){b||(b={});Kj()||(this.h=!1);Zk.prototype.sendThenWrite.call(this,a,b,c)};
$l.prototype.sendAndWrite=function(a,b){b||(b={});Kj()||(this.h=!1);Zk.prototype.sendAndWrite.call(this,a,b)};
function cm(a){var b;x(function(c){if(!a.B)throw b=Yj("clearSWHealthLogsDb"),b;return c.return(Ll(a.B).catch(function(d){a.handleError(d)}))})}
function bm(a,b,c){N("use_cfr_monitor")&&em(a,b);var d;if(null===(d=b.postParams)||void 0===d?0:d.requestTimeMs)b.postParams.requestTimeMs=Math.round(O());c&&0===Object.keys(b).length?ii(a):Xh(a,b)}
function am(){Zl||(Zl=new Xl({Fa:!0,jb:!0}));return Zl}
function em(a,b){var c=b.onError?b.onError:function(){};
b.onError=function(e,f){Nl().X(a,!1);c(e,f)};
var d=b.onSuccess?b.onSuccess:function(){};
b.onSuccess=function(e,f){Nl().X(a,!0);d(e,f)}}
;var fm=!1,gm=0,hm=0,im,jm=y.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:fm,potentialEsfErrorCounter:hm};B("ytNetworklessLoggingInitializationOptions",jm,void 0);
function km(){var a;x(function(b){switch(b.h){case 1:return w(b,Qk(),2);case 2:a=b.i;if(!a||!Kj()&&!N("nwl_init_require_datasync_id_killswitch")){b.o(0);break}fm=!0;jm.isNwlInitialized=fm;return w(b,Yk("LogsDatabaseV2"),4);case 4:if(!(.1>=Math.random())){b.o(5);break}return w(b,Fl(a),6);case 6:return w(b,Kl(a),5);case 5:lm();mm().H()&&nm();mm().V("publicytnetworkstatus-online",nm);mm().V("publicytnetworkstatus-offline",om);if(!N("networkless_immediately_drop_sw_health_store")){b.o(8);break}return w(b,
pm(),8);case 8:if(N("networkless_immediately_drop_all_requests"))return w(b,Gl(),0);b.o(0)}})}
function qm(a,b){function c(d){var e=mm().H();if(!rm()||!d||e&&N("vss_networkless_bypass_write"))sm(a,b);else{var f={url:a,options:b,timestamp:O(),status:"NEW",sendCount:0};zl(f,d).then(function(g){f.id=g;mm().H()&&tm(f)}).catch(function(g){tm(f);
mm().H()?Sg(g):Ql(g)})}}
b=void 0===b?{}:b;N("skip_is_supported_killswitch")?Qk().then(function(d){c(d)}):c(Pk())}
function um(a,b){function c(d){if(rm()&&d){var e={url:a,options:b,timestamp:O(),status:"NEW",sendCount:0},f=!1,g=b.onSuccess?b.onSuccess:function(){};
e.options.onSuccess=function(k,l){N("use_cfr_monitor")&&Nl().X(e.url,!0);void 0!==e.id?El(e.id,d):f=!0;N("vss_network_hint")&&mm().ga(!0);g(k,l)};
if(N("use_cfr_monitor")){var h=b.onError?b.onError:function(){};
e.options.onError=function(k,l){Nl().X(e.url,!1);h(k,l)}}sm(e.url,e.options);
zl(e,d).then(function(k){e.id=k;f&&El(e.id,d)}).catch(function(k){mm().H()?Sg(k):Ql(k)})}else sm(a,b)}
b=void 0===b?{}:b;N("skip_is_supported_killswitch")?Qk().then(function(d){c(d)}):c(Pk())}
function nm(){var a=Pk();if(!a)throw Yj("throttleSend");gm||(gm=uh.M(function(){var b;return x(function(c){if(1==c.h)return w(c,Bl("NEW",a),2);if(3!=c.h)return b=c.i,b?w(c,tm(b),3):(om(),c.return());gm&&(gm=0,nm());c.h=0})},100))}
function om(){uh.ca(gm);gm=0}
function tm(a){var b,c,d;return x(function(e){switch(e.h){case 1:b=Pk();if(!b)throw c=Yj("immediateSend"),c;if(void 0===a.id){e.o(2);break}return w(e,Cl(a.id,b),3);case 3:(d=e.i)?a=d:Tg(Error("The request cannot be found in the database."));case 2:if(vm(a,2592E6)){e.o(4);break}Tg(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===a.id){e.o(5);break}return w(e,El(a.id,b),5);case 5:return e.return();case 4:a.skipRetry||(a=wm(a));var f=a,g,h;if(null===(h=null===(g=null===
f||void 0===f?void 0:f.options)||void 0===g?void 0:g.postParams)||void 0===h?0:h.requestTimeMs)f.options.postParams.requestTimeMs=Math.round(O());a=f;if(!a){e.o(0);break}if(!a.skipRetry||void 0===a.id){e.o(8);break}return w(e,El(a.id,b),8);case 8:sm(a.url,a.options,!!a.skipRetry),e.h=0}})}
function wm(a){var b=Pk();if(!b)throw Yj("updateRequestHandlers");var c=a.options.onError?a.options.onError:function(){};
a.options.onError=function(e,f){var g;return x(function(h){switch(h.h){case 1:N("use_cfr_monitor")&&Nl().X(a.url,!1);g=fl(f);if(!(N("nwl_consider_error_code")&&g||!N("nwl_consider_error_code")&&xm()<=Xg("potential_esf_error_limit",10))){h.o(2);break}if(N("skip_checking_network_on_cfr_failure")&&(!N("skip_checking_network_on_cfr_failure")||Nl().ob(a.url))){h.o(3);break}return w(h,mm().Z(),3);case 3:if(mm().H()){h.o(2);break}c(e,f);if(!N("nwl_consider_error_code")||void 0===(null===a||void 0===a?void 0:
a.id)){h.o(6);break}return w(h,Dl(a.id,b,!1),6);case 6:return h.return();case 2:if(N("nwl_consider_error_code")&&!g&&xm()>Xg("potential_esf_error_limit",10))return h.return();C("ytNetworklessLoggingInitializationOptions")&&jm.potentialEsfErrorCounter++;hm++;if(void 0===(null===a||void 0===a?void 0:a.id)){h.o(8);break}return 1>a.sendCount?w(h,Dl(a.id,b),12):w(h,El(a.id,b),8);case 12:uh.M(function(){mm().H()&&nm()},5E3);
case 8:c(e,f),h.h=0}})};
var d=a.options.onSuccess?a.options.onSuccess:function(){};
a.options.onSuccess=function(e,f){return x(function(g){if(1==g.h)return N("use_cfr_monitor")&&Nl().X(a.url,!0),void 0===(null===a||void 0===a?void 0:a.id)?g.o(2):w(g,El(a.id,b),2);N("vss_network_hint")&&mm().ga(!0);d(e,f);g.h=0})};
return a}
function vm(a,b){a=a.timestamp;return O()-a>=b?!1:!0}
function lm(){var a=Pk();if(!a)throw Yj("retryQueuedRequests");Bl("QUEUED",a).then(function(b){b&&!vm(b,12E4)?uh.M(function(){return x(function(c){if(1==c.h)return void 0===b.id?c.o(2):w(c,Dl(b.id,a),2);lm();c.h=0})}):mm().H()&&nm()})}
function pm(){var a,b;return x(function(c){a=Pk();if(!a)throw b=Yj("clearSWHealthLogsDb"),b;return c.return(Ll(a).catch(function(d){Sg(d)}))})}
function mm(){if(N("use_new_nwl"))return am();im||(im=new Xl({Fa:!0,jb:!0}));return im}
function sm(a,b,c){c&&0===Object.keys(b).length?ii(a):Xh(a,b)}
function rm(){return C("ytNetworklessLoggingInitializationOptions")?jm.isNwlInitialized:fm}
function xm(){return C("ytNetworklessLoggingInitializationOptions")?jm.potentialEsfErrorCounter:hm}
;function ym(a){var b=this;this.config_=null;a?this.config_=a:oj()&&(this.config_=Qi());ph(function(){Bj(b)},5E3)}
ym.prototype.isReady=function(){!this.config_&&oj()&&(this.config_=Qi());return!!this.config_};
function Ui(a,b,c,d){function e(z){z=void 0===z?!1:z;var A;if(d.retry&&"www.youtube-nocookie.com"!=h&&(z||N("skip_ls_gel_retry")||"application/json"!==g.headers["Content-Type"]||(A=zj(b,c,l,k)),A)){var J=g.onSuccess,R=g.onFetchSuccess;g.onSuccess=function(S,U){Aj(A);J(S,U)};
c.onFetchSuccess=function(S,U){Aj(A);R(S,U)}}try{z&&d.retry&&!d.rb.bypassNetworkless?(g.method="POST",d.rb.writeThenSend?N("use_new_nwl")?dm().writeThenSend(r,g):qm(r,g):N("use_new_nwl")?dm().sendAndWrite(r,g):um(r,g)):(g.method="POST",g.postParams||(g.postParams={}),Xh(r,g))}catch(S){if("InvalidAccessError"==S.name)A&&(Aj(A),A=0),Tg(Error("An extension is blocking network request."));
else throw S;}A&&ph(function(){Bj(a)},5E3)}
!F("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&Tg(new Jj("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new Jj("innertube xhrclient not ready",b,c,d);Sg(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(z,A){if(d.onSuccess)d.onSuccess(A)},
onFetchSuccess:function(z){if(d.onSuccess)d.onSuccess(z)},
onError:function(z,A){if(d.onError)d.onError(A)},
onFetchError:function(z){if(d.onError)d.onError(z)},
timeout:d.timeout,withCredentials:!0};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.Mb)&&(h=f);var k=a.config_.Ob||!1,l=uj(k,h,d);Object.assign(g.headers,l);(f=g.headers.Authorization)&&!h&&(g.headers["x-origin"]=window.location.origin);var n="/youtubei/"+a.config_.innertubeApiVersion+"/"+b,p={alt:"json"},u=a.config_.Nb&&f;N("omit_innertube_api_key_for_bearer_auth_header")&&(u=u&&f.startsWith("Bearer"));u||(p.key=a.config_.innertubeApiKey);var r=Lh(""+
h+n,p||{},!0);N("use_new_nwl")&&dm().h||!N("use_new_nwl")&&rm()?Ok().then(function(z){e(z)}):e(!1)}
;function V(a,b,c){c=void 0===c?{}:c;var d=ym;F("ytLoggingEventsDefaultDisabled",!1)&&ym==ym&&(d=null);aj(a,b,d,c)}
;var zm=[{Va:function(a){return"Cannot read property '"+a.key+"'"},
Ga:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Va:function(a){return"Cannot call '"+a.key+"'"},
Ga:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Va:function(a){return a.key+" is not defined"},
Ga:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var Bm={fa:[],ba:[{cb:Am,weight:500}]};function Am(a){if("JavaException"===a.name)return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function Cm(){this.ba=[];this.fa=[]}
var Dm;function Em(){if(!Dm){var a=Dm=new Cm;a.fa.length=0;a.ba.length=0;Bm.fa&&a.fa.push.apply(a.fa,Bm.fa);Bm.ba&&a.ba.push.apply(a.ba,Bm.ba)}return Dm}
;var Fm=new L;function Gm(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=Hm(b);if(Infinity===e)break;var f=e>>3;switch(e&7){case 0:e=Hm(b);if(2===f)return e;break;case 1:if(2===f)return;d+=8;break;case 2:e=Hm(b);if(2===f)return a.substr(d,e);d+=e;break;case 5:if(2===f)return;d+=4;break;default:return}}while(d<c)}
function Hm(a){var b=a(),c=b&127;if(128>b)return c;b=a();c|=(b&127)<<7;if(128>b)return c;b=a();c|=(b&127)<<14;if(128>b)return c;b=a();return 128>b?c|(b&127)<<21:Infinity}
;function Im(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=Jm(d,a[d],b,c),500<e));d++);d=e}else if("object"===typeof a)for(e in a){if(a[e]){var f=a[e];var g=b;var h=c;g="string"!==typeof f||"clickTrackingParams"!==e&&"trackingParams"!==e?0:(f=Gm(atob(f.replace(/-/g,"+").replace(/_/g,"/"))))?Jm(e+".ve",f,g,h):0;d+=g;d+=Jm(e,a[e],b,c);if(500<d)break}}else c[b]=Km(a),d+=c[b].length;else c[b]=Km(a),d+=c[b].length;return d}
function Jm(a,b,c,d){c+="."+a;a=Km(b);d[c]=a;return c.length+a.length}
function Km(a){try{return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;var Lm=new Set,Mm=0,Nm=0,Om=0,Pm=[],Qm=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function Rm(a){Sm(a)}
function Tm(a){Sm(a,"WARNING")}
function Sm(a,b,c,d,e,f){f=void 0===f?{}:f;f.name=c||F("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||F("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0);c=f||{};b=void 0===b?"ERROR":b;b=void 0===b?"ERROR":b;if(a&&(a.hasOwnProperty("level")&&a.level&&(b=a.level),N("console_log_js_exceptions")&&(d=[],d.push("Name: "+a.name),d.push("Message: "+a.message),a.hasOwnProperty("params")&&d.push("Error Params: "+JSON.stringify(a.params)),a.hasOwnProperty("args")&&d.push("Error args: "+JSON.stringify(a.args)),d.push("File name: "+
a.fileName),d.push("Stacktrace: "+a.stack),window.console.log(d.join("\n"),a)),!(5<=Mm))){var g=Yd(a);d=g.message||"Unknown Error";e=g.name||"UnknownError";var h=g.stack||a.i||"Not available";h.startsWith(e+": "+d)&&(f=h.split("\n"),f.shift(),h=f.join("\n"));f=g.lineNumber||"Not available";g=g.fileName||"Not available";var k=0;if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var l=0;l<a.args.length&&!(k=Im(a.args[l],"params."+l,c,k),500<=k);l++);else if(a.hasOwnProperty("params")&&a.params){var n=
a.params;if("object"===typeof a.params)for(l in n){if(n[l]){var p="params."+l,u=Km(n[l]);c[p]=u;k+=p.length+u.length;if(500<k)break}}else c.params=Km(n)}if(Pm.length)for(l=0;l<Pm.length&&!(k=Im(Pm[l],"params.context."+l,c,k),500<=k);l++);navigator.vendor&&!c.hasOwnProperty("vendor")&&(c["device.vendor"]=navigator.vendor);l={message:d,name:e,lineNumber:f,fileName:g,stack:h,params:c,sampleWeight:1};c=Number(a.columnNumber);isNaN(c)||(l.lineNumber=l.lineNumber+":"+c);if("IGNORED"===a.level)a=0;else a:{a=
Em();c=t(a.fa);for(d=c.next();!d.done;d=c.next())if(d=d.value,l.message&&l.message.match(d.rn)){a=d.weight;break a}a=t(a.ba);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.cb(l)){a=c.weight;break a}a=1}l.sampleWeight=a;a=t(zm);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.Ga[l.name])for(e=t(c.Ga[l.name]),d=e.next();!d.done;d=e.next())if(f=d.value,d=l.message.match(f.regexp)){l.params["params.error.original"]=d[0];e=f.groups;f={};for(g=0;g<e.length;g++)f[e[g]]=d[g+1],l.params["params.error."+
e[g]]=d[g+1];l.message=c.Va(f);break}l.params||(l.params={});a=Em();l.params["params.errorServiceSignature"]="msg="+a.fa.length+"&cb="+a.ba.length;l.params["params.serviceWorker"]="false";y.document&&y.document.querySelectorAll&&(l.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));yb("sample").constructor!==wb&&(l.params["params.fconst"]="true");window.yterr&&"function"===typeof window.yterr&&window.yterr(l);if(0!==l.sampleWeight&&!Lm.has(l.message)){"ERROR"===
b?(Fm.ja("handleError",l),N("record_app_crashed_web")&&0===Om&&1===l.sampleWeight&&(Om++,a={appCrashType:"APP_CRASH_TYPE_BREAKPAD"},N("report_client_error_with_app_crash_ks")||(a.systemHealth={crashData:{clientError:{logMessage:{message:l.message}}}}),V("appCrashed",a)),Nm++):"WARNING"===b&&Fm.ja("handleWarning",l);if(N("kevlar_gel_error_routing")){a=b;b:{c=t(Qm);for(d=c.next();!d.done;d=c.next())if(fi(d.value.toLowerCase())){c=!0;break b}c=!1}if(c)c=void 0;else{d={stackTrace:l.stack};l.fileName&&
(d.filename=l.fileName);c=l.lineNumber&&l.lineNumber.split?l.lineNumber.split(":"):[];0!==c.length&&(1!==c.length||isNaN(Number(c[0]))?2!==c.length||isNaN(Number(c[0]))||isNaN(Number(c[1]))||(d.lineNumber=Number(c[0]),d.columnNumber=Number(c[1])):d.lineNumber=Number(c[0]));c={level:"ERROR_LEVEL_UNKNOWN",message:l.message,errorClassName:l.name,sampleWeight:l.sampleWeight};"ERROR"===a?c.level="ERROR_LEVEL_ERROR":"WARNING"===a&&(c.level="ERROR_LEVEL_WARNNING");d={isObfuscated:!0,browserStackInfo:d};
e={pageUrl:window.location.href,kvPairs:[]};F("FEXP_EXPERIMENTS")&&(e.experimentIds=F("FEXP_EXPERIMENTS"));f=F("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS",void 0);g=Mg.EXPERIMENT_FLAGS;if((!g||!g.web_disable_gel_stp_ecatcher_killswitch)&&f)for(h=t(Object.keys(f)),g=h.next();!g.done;g=h.next())g=g.value,e.kvPairs.push({key:g,value:String(f[g])});if(f=l.params)for(h=t(Object.keys(f)),g=h.next();!g.done;g=h.next())g=g.value,e.kvPairs.push({key:"client."+g,value:String(f[g])});f=F("SERVER_NAME",void 0);
g=F("SERVER_VERSION",void 0);f&&g&&(e.kvPairs.push({key:"server.name",value:f}),e.kvPairs.push({key:"server.version",value:g}));c={errorMetadata:e,stackTrace:d,logMessage:c}}c&&(V("clientError",c),("ERROR"===a||N("errors_flush_gel_always_killswitch"))&&Ki())}if(!N("suppress_error_204_logging")){a=l.params||{};b={urlParams:{a:"logerror",t:"jserror",type:l.name,msg:l.message.substr(0,250),line:l.lineNumber,level:b,"client.name":a.name},postParams:{url:F("PAGE_NAME",window.location.href),file:l.fileName},
method:"POST"};a.version&&(b["client.version"]=a.version);if(b.postParams){l.stack&&(b.postParams.stack=l.stack);c=t(Object.keys(a));for(d=c.next();!d.done;d=c.next())d=d.value,b.postParams["client."+d]=a[d];if(a=F("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS",void 0))for(c=t(Object.keys(a)),d=c.next();!d.done;d=c.next())d=d.value,b.postParams[d]=a[d];a=F("SERVER_NAME",void 0);c=F("SERVER_VERSION",void 0);a&&c&&(b.postParams["server.name"]=a,b.postParams["server.version"]=c)}Xh(F("ECATCHER_REPORT_HOST",
"")+"/error_204",b)}try{Lm.add(l.message)}catch(r){}Mm++}}}
function Um(a){var b=Ea.apply(1,arguments),c=a;c.args||(c.args=[]);c.args.push.apply(c.args,ha(b))}
;var Vm={Wc:3611,lc:27686,mc:85013,nc:23462,pc:42016,qc:62407,sc:26926,oc:43781,tc:51236,uc:79148,wc:50160,xc:77504,Jc:87907,Kc:18630,Lc:54445,Mc:80935,Nc:105675,Oc:37521,Pc:47786,Qc:98349,Rc:123695,Sc:6827,Tc:29434,Uc:7282,Vc:124448,Zc:32276,Yc:76278,bd:93911,cd:106531,dd:27259,ed:27262,fd:27263,hd:21759,jd:27107,kd:62936,ld:49568,md:38408,nd:80637,od:68727,pd:68728,qd:80353,rd:80356,sd:74610,td:45707,ud:83962,vd:83970,wd:46713,xd:89711,yd:74612,zd:93265,Ad:74611,Bd:131380,Dd:128979,Ed:139311,Fd:128978,
Cd:131391,Gd:105350,Id:139312,Jd:134800,Hd:131392,Ld:113533,Md:93252,Nd:99357,Pd:94521,Qd:114252,Rd:113532,Sd:94522,Od:94583,Td:88E3,Ud:139580,Vd:93253,Wd:93254,Xd:94387,Yd:94388,Zd:93255,ae:97424,Kd:72502,be:110111,ce:76019,ee:117092,ge:117093,de:89431,he:110466,ie:77240,je:60508,ke:137401,le:137402,me:137046,ne:73393,oe:113534,pe:92098,qe:131381,re:84517,se:83759,te:80357,ue:86113,we:72598,xe:72733,ye:107349,ze:124275,Ae:118203,Be:133275,Ce:133274,De:133272,Ee:133273,Fe:133276,He:117431,Ge:133797,
Ie:128572,Je:133405,Ke:117429,Le:117430,Me:117432,Ne:120080,Oe:117259,Pe:121692,Qe:132972,Re:133051,Se:133658,Te:132971,Ue:97615,Ve:31402,Xe:133624,Ye:133623,Ze:133622,We:133621,af:84774,bf:95117,cf:98930,df:98931,ef:98932,ff:43347,gf:129889,hf:45474,jf:100352,kf:84758,lf:98443,mf:117985,nf:74613,pf:74614,qf:64502,rf:136032,sf:74615,tf:74616,uf:122224,vf:74617,wf:77820,xf:74618,yf:93278,zf:93274,Af:93275,Bf:93276,Cf:22110,Df:29433,Ef:133798,Ff:132295,Hf:120541,Jf:82047,Kf:113550,Lf:75836,Mf:75837,
Nf:42352,Of:84512,Pf:76065,Qf:75989,Rf:16623,Sf:32594,Tf:27240,Uf:32633,Vf:74858,Xf:3945,Wf:16989,Yf:45520,Zf:25488,ag:25492,cg:25494,dg:55760,eg:14057,fg:18451,gg:57204,hg:57203,ig:17897,jg:57205,kg:18198,lg:17898,mg:17909,ng:43980,og:46220,pg:11721,qg:49954,rg:96369,sg:3854,tg:56251,ug:25624,vg:16906,wg:99999,xg:68172,yg:27068,zg:47973,Ag:72773,Bg:26970,Cg:26971,Dg:96805,Eg:17752,Fg:73233,Gg:109512,Hg:22256,Ig:14115,Jg:22696,Kg:89278,Lg:89277,Mg:109513,Ng:43278,Og:43459,Pg:43464,Qg:89279,Rg:43717,
Sg:55764,Tg:22255,Ug:89281,Vg:40963,Wg:43277,Xg:43442,Yg:91824,Zg:120137,ah:96367,bh:36850,dh:72694,eh:37414,fh:36851,hh:124863,gh:121343,ih:73491,jh:54473,kh:43375,lh:46674,mh:139095,nh:32473,oh:72901,ph:72906,qh:50947,rh:50612,sh:50613,th:50942,uh:84938,vh:84943,wh:84939,xh:84941,yh:84944,zh:84940,Ah:84942,Bh:35585,Ch:51926,Dh:79983,Eh:63238,Fh:18921,Gh:63241,Hh:57893,Ih:41182,Jh:135732,Kh:33424,Lh:22207,Mh:42993,Nh:36229,Oh:22206,Ph:22205,Qh:18993,Rh:19001,Sh:18990,Th:18991,Uh:18997,Vh:18725,Wh:19003,
Xh:36874,Yh:44763,Zh:33427,ai:67793,bi:22182,ci:37091,di:34650,fi:50617,gi:47261,hi:22287,ii:25144,ji:97917,ki:62397,li:125598,mi:137935,ni:36961,oi:108035,ri:27426,si:27857,ti:27846,vi:27854,wi:69692,xi:61411,yi:39299,zi:38696,Ai:62520,Bi:36382,Ci:108701,Di:50663,Ei:36387,Fi:14908,Gi:37533,Hi:105443,Ii:61635,Ji:62274,Ki:133818,Li:65702,Mi:65703,Ni:65701,Oi:76256,Pi:37671,Qi:49953,Si:36216,Ti:28237,Ui:39553,Vi:29222,Wi:26107,Xi:38050,Yi:26108,aj:120745,Zi:26109,bj:26110,cj:66881,dj:28236,ej:14586,
fj:57929,gj:74723,hj:44098,ij:44099,lj:23528,mj:61699,jj:134104,kj:134103,nj:59149,oj:101951,pj:97346,qj:118051,rj:95102,sj:64882,tj:119505,uj:63595,vj:63349,wj:95101,xj:75240,yj:27039,zj:68823,Aj:21537,Bj:83464,Cj:75707,Dj:83113,Ej:101952,Fj:101953,Hj:79610,Ij:125755,Jj:24402,Kj:24400,Lj:32925,Mj:57173,Nj:122502,Oj:138480,Pj:64423,Qj:64424,Rj:33986,Sj:100828,Tj:129089,Uj:21409,Yj:135155,Zj:135156,ak:135157,bk:135158,ck:135159,dk:135160,ek:135161,fk:135162,gk:135163,hk:135164,ik:135165,jk:135166,
Vj:11070,Wj:11074,Xj:17880,kk:14001,mk:30709,nk:30707,pk:30711,qk:30710,rk:30708,lk:26984,sk:63648,tk:63649,uk:51879,vk:111059,wk:5754,xk:20445,zk:130975,yk:130976,Ak:110386,Bk:113746,Ck:66557,Ek:17310,Fk:28631,Gk:21589,Hk:68012,Ik:60480,Jk:138664,Kk:141121,Lk:31571,Mk:141978,Nk:76980,Ok:41577,Pk:45469,Qk:38669,Rk:13768,Sk:13777,Tk:62985,Uk:4724,Vk:59369,Wk:43927,Xk:43928,Yk:12924,Zk:100355,dl:56219,fl:27669,il:10337,bl:47896,jl:122629,ll:139723,kl:139722,ml:121258,nl:107598,ol:127991,pl:96639,ql:107536,
rl:130169,sl:96661,ul:96658,vl:116646,wl:121122,xl:96660,yl:127738,zl:127083,Al:104443,Bl:96659,Cl:106442,Dl:134840,El:63667,Fl:63668,Gl:63669,Hl:130686,Il:78314,Jl:55761,Kl:127098,Ll:134841,Ml:96368,Nl:67374,Ol:48992,Pl:49956,Ql:31961,Rl:26388,Sl:23811,Tl:5E4,Ul:126250,Vl:96370,Wl:47355,Xl:47356,Yl:37935,Zl:45521,am:21760,bm:83769,cm:49977,dm:49974,em:93497,fm:93498,gm:34325,hm:140759,im:115803,jm:123707,km:100081,lm:35309,mm:68314,nm:25602,om:100339,pm:59018,qm:18248,rm:50625,sm:9729,tm:37168,um:37169,
vm:21667,wm:16749,xm:18635,ym:39305,zm:18046,Am:53969,Bm:8213,Cm:93926,Dm:102852,Em:110099,Fm:22678,Gm:69076,Hm:137575,Jm:139224,Km:100856,Lm:17736,Mm:3832,Nm:55759,Om:64031,Um:93044,Vm:93045,Wm:34388,Xm:17657,Ym:17655,Zm:39579,an:39578,bn:77448,cn:8196,dn:11357,en:69877,fn:8197,gn:82039};function Wm(){var a=qb(Xm),b;return Lf(new Ef(function(c,d){a.onSuccess=function(e){Rh(e)?c(new Ym(e)):d(new Zm("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new Zm("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new Zm("Request timed out","net.timeout",e))};
b=Xh("//googleads.g.doubleclick.net/pagead/id",a)}),function(c){c instanceof Mf&&b.abort();
return Jf(c)})}
function Zm(a,b,c){Za.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
v(Zm,Za);function Ym(a){this.xhr=a}
;function $m(){this.i=0;this.h=null}
$m.prototype.then=function(a,b,c){return 1===this.i&&a?(a=a.call(c,this.h),Df(a)?a:an(a)):2===this.i&&b?(a=b.call(c,this.h),Df(a)?a:bn(a)):this};
$m.prototype.getValue=function(){return this.h};
$m.prototype.$goog_Thenable=!0;function bn(a){var b=new $m;a=void 0===a?null:a;b.i=2;b.h=void 0===a?null:a;return b}
function an(a){var b=new $m;a=void 0===a?null:a;b.i=1;b.h=void 0===a?null:a;return b}
;function cn(){if(Rd())return!0;var a=F("INNERTUBE_CLIENT_NAME");return!a||"WEB"!==a&&"MWEB"!==a||ei&&fi("applewebkit")&&!fi("version")&&(!fi("safari")||fi("gsa/"))||sc&&fi("version/")?!0:(a=Pd.get("CONSENT",void 0))?a.startsWith("YES+"):!0}
;function dn(a){Za.call(this,a.message||a.description||a.name);this.isMissing=a instanceof en;this.isTimeout=a instanceof Zm&&"net.timeout"==a.errorCode;this.isCanceled=a instanceof Mf}
v(dn,Za);dn.prototype.name="BiscottiError";function en(){Za.call(this,"Biscotti ID is missing from server")}
v(en,Za);en.prototype.name="BiscottiMissingError";var Xm={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},fn=null;function Bh(){if(N("disable_biscotti_fetch_entirely_for_all_web_clients"))return Jf(Error("Biscotti id fetching has been disabled entirely."));if(!cn())return Jf(Error("User has not consented - not fetching biscotti id."));if("1"==ob())return Jf(Error("Biscotti ID is not available in private embed mode"));fn||(fn=Lf(Wm().then(gn),function(a){return hn(2,a)}));
return fn}
function gn(a){a=a.xhr.responseText;if(0!=a.lastIndexOf(")]}'",0))throw new en;a=JSON.parse(a.substr(4));if(1<(a.type||1))throw new en;a=a.id;Ch(a);fn=an(a);jn(18E5,2);return a}
function hn(a,b){b=new dn(b);Ch("");fn=bn(b);0<a&&jn(12E4,a-1);throw b;}
function jn(a,b){lh(function(){Lf(Wm().then(gn,function(c){return hn(b,c)}),Ka)},a)}
function kn(){try{var a=C("yt.ads.biscotti.getId_");return a?a():Bh()}catch(b){return Jf(b)}}
;function ln(a){if("1"!=ob()){a&&Ah();try{kn().then(function(){},function(){}),lh(ln,18E5)}catch(b){Sg(b)}}}
;var mn=Date.now().toString();
function nn(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;16>a;a++){b=Date.now();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(256*Math.random())}if(mn)for(a=1,b=0;b<mn.length;b++)d[a%16]=d[a%16]^d[(a-1)%16]/4^mn.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var on,pn=y.ytLoggingDocDocumentNonce_;pn||(pn=nn(),Xa("ytLoggingDocDocumentNonce_",pn));on=pn;var qn={Gf:0,Xc:1,gd:2,Ri:3,If:4,Im:5,Gj:6,al:7,Dk:8,0:"DEFAULT",1:"CHAT",2:"CONVERSATIONS",3:"MINIPLAYER",4:"DIALOG",5:"VOZ",6:"MUSIC_WATCH_TABS",7:"SHARE",8:"PUSH_NOTIFICATIONS"};function rn(a){this.h=a}
function sn(a){return new rn({trackingParams:a})}
rn.prototype.getAsJson=function(){var a={};void 0!==this.h.trackingParams?a.trackingParams=this.h.trackingParams:(a.veType=this.h.veType,void 0!==this.h.veCounter&&(a.veCounter=this.h.veCounter),void 0!==this.h.elementIndex&&(a.elementIndex=this.h.elementIndex));void 0!==this.h.dataElement&&(a.dataElement=this.h.dataElement.getAsJson());void 0!==this.h.youtubeData&&(a.youtubeData=this.h.youtubeData);return a};
rn.prototype.toString=function(){return JSON.stringify(this.getAsJson())};
rn.prototype.isClientVe=function(){return!this.h.trackingParams&&!!this.h.veType};function tn(a){a=void 0===a?0:a;return 0==a?"client-screen-nonce":"client-screen-nonce."+a}
function un(a){a=void 0===a?0:a;return 0==a?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function vn(a){return F(un(void 0===a?0:a),void 0)}
B("yt_logging_screen.getRootVeType",vn,void 0);function wn(a){return(a=vn(void 0===a?0:a))?new rn({veType:a,youtubeData:void 0}):null}
function xn(){var a=F("csn-to-ctt-auth-info");a||(a={},M("csn-to-ctt-auth-info",a));return a}
function yn(a){a=void 0===a?0:a;var b=F(tn(a));if(!b&&!F("USE_CSN_FALLBACK",!0))return null;b||!N("use_undefined_csn_any_layer")&&0!=a||(b="UNDEFINED_CSN");return b?b:null}
B("yt_logging_screen.getCurrentCsn",yn,void 0);function zn(a,b,c){var d=xn();(c=yn(c))&&delete d[c];b&&(d[a]=b)}
function An(a){return xn()[a]}
B("yt_logging_screen.getCttAuthInfo",An,void 0);function Bn(a,b,c,d){c=void 0===c?0:c;if(a!==F(tn(c))||b!==F(un(c)))zn(a,d,c),M(tn(c),a),M(un(c),b),b=function(){setTimeout(function(){if(a){var e={clientDocumentNonce:on,clientScreenNonce:a};N("use_default_heartbeat_client")?V("foregroundHeartbeatScreenAssociated",e):aj("foregroundHeartbeatScreenAssociated",e,ym)}},0)},"requestAnimationFrame"in window?window.requestAnimationFrame(b):b()}
B("yt_logging_screen.setCurrentScreen",Bn,void 0);function Cn(a){gl.call(this,1,arguments);this.csn=a}
v(Cn,gl);var pl=new hl("screen-created",Cn),Dn=[],Fn=En,Gn=0;function Hn(a,b,c,d){var e=d.filter(function(f){f.csn!==b?(f.csn=b,f=!0):f=!1;return f});
c={csn:b,parentVe:c.getAsJson(),childVes:db(e,function(f){return f.getAsJson()})};
d=t(d);for(e=d.next();!e.done;e=d.next())e=e.value.getAsJson(),(mb(e)||!e.trackingParams&&!e.veType)&&Tm(Error("Child VE logged with no data"));d={cttAuthInfo:An(b),ha:b};"UNDEFINED_CSN"==b?In("visualElementAttached",c,d):a?aj("visualElementAttached",c,a,d):V("visualElementAttached",c,d)}
function En(){for(var a=Math.random()+"",b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);255<e&&(b[c++]=e&255,e>>=8);b[c++]=e}return Hc(b,3)}
function In(a,b,c){Dn.push({payloadName:a,payload:b,options:c});Gn||(Gn=ql())}
function rl(a){if(Dn){for(var b=t(Dn),c=b.next();!c.done;c=b.next())c=c.value,c.payload&&(c.payload.csn=a.csn,aj(c.payloadName,c.payload,null,c.options));Dn.length=0}Gn=0}
;function Jn(){this.i=new Set;this.h=new Set;this.j=new Map}
Jn.prototype.clear=function(){this.i.clear();this.h.clear();this.j.clear()};
La(Jn);function Kn(a){var b=Ea.apply(1,arguments);if(!Ln(a)||b.some(function(e){return!Ln(e)}))throw Error("Only objects may be merged.");
var c=a;b=t(b);for(var d=b.next();!d.done;d=b.next())Mn(c,d.value);return c}
function Mn(a,b){for(var c in b)if(Ln(b[c])){if(c in a&&!Ln(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});Mn(a[c],b[c])}else if(Nn(b[c])){if(c in a&&!Nn(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);On(a[c],b[c])}else a[c]=b[c];return a}
function On(a,b){b=t(b);for(var c=b.next();!c.done;c=b.next())c=c.value,Ln(c)?a.push(Mn({},c)):Nn(c)?a.push(On([],c)):a.push(c);return a}
function Ln(a){return"object"===typeof a&&!Array.isArray(a)}
function Nn(a){return"object"===typeof a&&Array.isArray(a)}
;function Pn(a,b){gl.call(this,1,arguments)}
v(Pn,gl);function Qn(a,b){gl.call(this,1,arguments)}
v(Qn,gl);var Rn=new hl("aft-recorded",Pn),Sn=new hl("timing-sent",Qn);var Tn=window;function Un(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
var W=Tn.performance||Tn.mozPerformance||Tn.msPerformance||Tn.webkitPerformance||new Un;var Vn=!1,Wn={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",
'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",'script[name="mobile_blazer_watch_mod"]':"mbwj"};
Va(W.clearResourceTimings||W.webkitClearResourceTimings||W.mozClearResourceTimings||W.msClearResourceTimings||W.oClearResourceTimings||Ka,W);function Xn(a){var b=Yn(a);if(b.aft)return b.aft;a=F((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=a.length,d=0;d<c;d++){var e=b[a[d]];if(e)return e}return NaN}
function Zn(){var a;if(N("csi_use_performance_navigation_timing")){var b,c,d,e=null===(d=null===(c=null===(b=null===(a=null===W||void 0===W?void 0:W.getEntriesByType)||void 0===a?void 0:a.call(W,"navigation"))||void 0===b?void 0:b[0])||void 0===c?void 0:c.toJSON)||void 0===d?void 0:d.call(c);e?(e.requestStart=$n(e.requestStart),e.responseEnd=$n(e.responseEnd),e.redirectStart=$n(e.redirectStart),e.redirectEnd=$n(e.redirectEnd),e.domainLookupEnd=$n(e.domainLookupEnd),e.connectStart=$n(e.connectStart),
e.connectEnd=$n(e.connectEnd),e.responseStart=$n(e.responseStart),e.secureConnectionStart=$n(e.secureConnectionStart),e.domainLookupStart=$n(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=W.timing}else a=W.timing;return a}
function ao(){return N("csi_use_time_origin")&&W.timeOrigin?Math.floor(W.timeOrigin):W.timing.navigationStart}
function $n(a){return Math.round(ao()+a)}
function bo(a){var b;(b=C("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},Xa("ytcsi."+(a||"")+"data_",b));return b}
function eo(a){a=bo(a);a.info||(a.info={});return a.info}
function Yn(a){a=bo(a);a.tick||(a.tick={});return a.tick}
function fo(a){var b=bo(a).nonce;b||(b=nn(),bo(a).nonce=b);return b}
function go(a){var b=Yn(a||""),c=Xn(a);c&&!Vn&&(ml(Rn,new Pn(Math.round(c-b._start),a)),Vn=!0)}
;function ho(){if(W.getEntriesByType){var a=W.getEntriesByType("paint");if(a=fb(a,function(b){return"first-paint"===b.name}))return $n(a.startTime)}a=W.timing;
return a.Rb?Math.max(0,a.Rb):0}
;function io(){var a=C("ytcsi.debug");a||(a=[],B("ytcsi.debug",a,void 0),B("ytcsi.reference",{},void 0));return a}
function jo(a){a=a||"";var b=C("ytcsi.reference");b||(io(),b=C("ytcsi.reference"));if(b[a])return b[a];var c=io(),d={timerName:a,info:{},tick:{},span:{}};c.push(d);return b[a]=d}
;var ko=y.ytLoggingLatencyUsageStats_||{};B("ytLoggingLatencyUsageStats_",ko,void 0);function lo(){this.h=0}
function mo(){lo.h||(lo.h=new lo);return lo.h}
lo.prototype.tick=function(a,b,c,d){no(this,"tick_"+a+"_"+b)||V("latencyActionTicked",{tickName:a,clientActionNonce:b},{timestamp:c,cttAuthInfo:d})};
lo.prototype.info=function(a,b,c){var d=Object.keys(a).join("");no(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,V("latencyActionInfo",a,{cttAuthInfo:c}))};
lo.prototype.span=function(a,b,c){var d=Object.keys(a).join("");no(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,V("latencyActionSpan",a,{cttAuthInfo:c}))};
function no(a,b){ko[b]=ko[b]||{count:0};var c=ko[b];c.count++;c.time=O();a.h||(a.h=ph(function(){var d=O(),e;for(e in ko)ko[e]&&6E4<d-ko[e].time&&delete ko[e];a&&(a.h=0)},5E3));
return 5<c.count?(6===c.count&&1>1E5*Math.random()&&(c=new Jj("CSI data exceeded logging limit with key",b.split("_")),0<=b.indexOf("plev")||Tm(c)),!0):!1}
;var X={},oo=(X.auto_search="LATENCY_ACTION_AUTO_SEARCH",X.ad_to_ad="LATENCY_ACTION_AD_TO_AD",X.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",X["analytics.explore"]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE",X.app_startup="LATENCY_ACTION_APP_STARTUP",X["artist.analytics"]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS",X["artist.events"]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS",X["artist.presskit"]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE",X.browse="LATENCY_ACTION_BROWSE",X.channels="LATENCY_ACTION_CHANNELS",X.creator_channel_dashboard=
"LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD",X["channel.analytics"]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS",X["channel.comments"]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS",X["channel.content"]="LATENCY_ACTION_CREATOR_POST_LIST",X["channel.copyright"]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT",X["channel.editing"]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING",X["channel.monetization"]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION",X["channel.music"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC",X["channel.playlists"]=
"LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS",X["channel.translations"]="LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS",X["channel.videos"]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS",X["channel.live_streaming"]="LATENCY_ACTION_CREATOR_LIVE_STREAMING",X.chips="LATENCY_ACTION_CHIPS",X["dialog.copyright_strikes"]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES",X["dialog.uploads"]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS",X.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",X.embed="LATENCY_ACTION_EMBED",X.entity_key_serialization_perf=
"LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",X.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",X.explore="LATENCY_ACTION_EXPLORE",X.home="LATENCY_ACTION_HOME",X.library="LATENCY_ACTION_LIBRARY",X.live="LATENCY_ACTION_LIVE",X.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",X.onboarding="LATENCY_ACTION_ONBOARDING",X.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",X.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",X.parent_tools_dashboard=
"LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",X.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",X["post.comments"]="LATENCY_ACTION_CREATOR_POST_COMMENTS",X["post.edit"]="LATENCY_ACTION_CREATOR_POST_EDIT",X.prebuffer="LATENCY_ACTION_PREBUFFER",X.prefetch="LATENCY_ACTION_PREFETCH",X.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",X.profile_switcher="LATENCY_ACTION_LOGIN",X.reel_watch="LATENCY_ACTION_REEL_WATCH",X.results="LATENCY_ACTION_RESULTS",X.search_ui="LATENCY_ACTION_SEARCH_UI",X.search_suggest=
"LATENCY_ACTION_SUGGEST",X.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",X.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",X.seek="LATENCY_ACTION_PLAYER_SEEK",X.settings="LATENCY_ACTION_SETTINGS",X.tenx="LATENCY_ACTION_TENX",X.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",X.watch="LATENCY_ACTION_WATCH",X.watch_it_again="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",X["watch,watch7"]="LATENCY_ACTION_WATCH",X["watch,watch7_html5"]="LATENCY_ACTION_WATCH",X["watch,watch7ad"]="LATENCY_ACTION_WATCH",X["watch,watch7ad_html5"]=
"LATENCY_ACTION_WATCH",X.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",X.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",X["video.analytics"]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS",X["video.comments"]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS",X["video.edit"]="LATENCY_ACTION_CREATOR_VIDEO_EDIT",X["video.editor"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR",X["video.editor_async"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC",X["video.live_settings"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS",X["video.live_streaming"]=
"LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING",X["video.monetization"]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION",X["video.translations"]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS",X.voice_assistant="LATENCY_ACTION_VOICE_ASSISTANT",X.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",X.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",X),Y={},po=(Y.ad_allowed="adTypesAllowed",Y.yt_abt="adBreakType",Y.ad_cpn="adClientPlaybackNonce",Y.ad_docid="adVideoId",Y.yt_ad_an=
"adNetworks",Y.ad_at="adType",Y.aida="appInstallDataAgeMs",Y.browse_id="browseId",Y.p="httpProtocol",Y.t="transportProtocol",Y.cs="commandSource",Y.cpn="clientPlaybackNonce",Y.ccs="creatorInfo.creatorCanaryState",Y.ctop="creatorInfo.topEntityType",Y.csn="clientScreenNonce",Y.docid="videoId",Y.GetHome_rid="requestIds",Y.GetSearch_rid="requestIds",Y.GetPlayer_rid="requestIds",Y.GetWatchNext_rid="requestIds",Y.GetBrowse_rid="requestIds",Y.GetLibrary_rid="requestIds",Y.is_continuation="isContinuation",
Y.is_nav="isNavigation",Y.b_p="kabukiInfo.browseParams",Y.is_prefetch="kabukiInfo.isPrefetch",Y.is_secondary_nav="kabukiInfo.isSecondaryNav",Y.nav_type="kabukiInfo.navigationType",Y.prev_browse_id="kabukiInfo.prevBrowseId",Y.query_source="kabukiInfo.querySource",Y.voz_type="kabukiInfo.vozType",Y.yt_lt="loadType",Y.mver="creatorInfo.measurementVersion",Y.yt_ad="isMonetized",Y.nr="webInfo.navigationReason",Y.nrsu="navigationRequestedSameUrl",Y.ncnp="webInfo.nonPreloadedNodeCount",Y.pnt="performanceNavigationTiming",
Y.prt="playbackRequiresTap",Y.plt="playerInfo.playbackType",Y.pis="playerInfo.playerInitializedState",Y.paused="playerInfo.isPausedOnLoad",Y.yt_pt="playerType",Y.fmt="playerInfo.itag",Y.yt_pl="watchInfo.isPlaylist",Y.yt_pre="playerInfo.preloadType",Y.yt_ad_pr="prerollAllowed",Y.pa="previousAction",Y.yt_red="isRedSubscriber",Y.rce="mwebInfo.responseContentEncoding",Y.rc="resourceInfo.resourceCache",Y.scrh="screenHeight",Y.scrw="screenWidth",Y.st="serverTimeMs",Y.ssdm="shellStartupDurationMs",Y.br_trs=
"tvInfo.bedrockTriggerState",Y.kebqat="kabukiInfo.earlyBrowseRequestInfo.abandonmentType",Y.kebqa="kabukiInfo.earlyBrowseRequestInfo.adopted",Y.label="tvInfo.label",Y.is_mdx="tvInfo.isMdx",Y.preloaded="tvInfo.isPreloaded",Y.aac_type="tvInfo.authAccessCredentialType",Y.upg_player_vis="playerInfo.visibilityState",Y.query="unpluggedInfo.query",Y.upg_chip_ids_string="unpluggedInfo.upgChipIdsString",Y.yt_vst="videoStreamType",Y.vph="viewportHeight",Y.vpw="viewportWidth",Y.yt_vis="isVisible",Y.rcl="mwebInfo.responseContentLength",
Y.GetSettings_rid="requestIds",Y.GetTrending_rid="requestIds",Y.GetMusicSearchSuggestions_rid="requestIds",Y.REQUEST_ID="requestIds",Y),qo="isContinuation isNavigation kabukiInfo.earlyBrowseRequestInfo.adopted kabukiInfo.isPrefetch kabukiInfo.isSecondaryNav isMonetized navigationRequestedSameUrl performanceNavigationTiming playerInfo.isPausedOnLoad prerollAllowed isRedSubscriber tvInfo.isMdx tvInfo.isPreloaded isVisible watchInfo.isPlaylist playbackRequiresTap".split(" "),ro={},so=(ro.ccs="CANARY_STATE_",
ro.mver="MEASUREMENT_VERSION_",ro.pis="PLAYER_INITIALIZED_STATE_",ro.yt_pt="LATENCY_PLAYER_",ro.pa="LATENCY_ACTION_",ro.ctop="TOP_ENTITY_TYPE_",ro.yt_vst="VIDEO_STREAM_TYPE_",ro),to="all_vc ap aq c cbr cbrand cbrver cmodel cos cosver cplatform ctheme cver ei l_an l_mm plid srt yt_fss yt_li vpst vpni2 vpil2 icrc icrt pa GetAccountOverview_rid GetHistory_rid cmt d_vpct d_vpnfi d_vpni nsru pc pfa pfeh pftr pnc prerender psc rc start tcrt tcrc ssr vpr vps yt_abt yt_fn yt_fs yt_pft yt_pre yt_pt yt_pvis ytu_pvis yt_ref yt_sts tds".split(" ");
function uo(a){return!!F("FORCE_CSI_ON_GEL",!1)||N("csi_on_gel")||N("enable_csi_on_gel")||N("unplugged_tvhtml5_csi_on_gel")||!!bo(a).useGel}
function vo(a,b,c){var d=wo(c);d.gelTicks&&(d.gelTicks["tick_"+a]=!0);c||b||O();if(uo(c)){jo(c||"").tick[a]=b||O();d=fo(c);var e=bo(c).cttAuthInfo;"_start"===a?(a=mo(),no(a,"baseline_"+d)||V("latencyActionBaselined",{clientActionNonce:d},{timestamp:b,cttAuthInfo:e})):mo().tick(a,d,b,e);go(c);return!0}return!1}
function xo(a,b,c){c=wo(c);if(c.gelInfos)c.gelInfos["info_"+a]=!0;else{var d={};c.gelInfos=(d["info_"+a]=!0,d)}if(a.match("_rid")){var e=a.split("_rid")[0];a="REQUEST_ID"}if(a in po){c=po[a];0<=bb(qo,c)&&(b=!!b);a in so&&"string"===typeof b&&(b=so[a]+b.toUpperCase());a=b;b=c.split(".");for(var f=d={},g=0;g<b.length-1;g++){var h=b[g];f[h]={};f=f[h]}f[b[b.length-1]]="requestIds"===c?[{id:a,endpoint:e}]:a;return Kn({},d)}0<=bb(to,a)||Tm(new Jj("Unknown label logged with GEL CSI",a))}
function wo(a){a=bo(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function yo(a){a=wo(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
;function zo(a,b,c){null!==b&&(eo(c)[a]=b,uo(c)?(a=xo(a,b,c))&&uo(c)&&(b=jo(c||""),Kn(b.info,a),Kn(yo(c),a),b=fo(c),c=bo(c).cttAuthInfo,mo().info(a,b,c)):jo(c||"").info[a]=b)}
function Z(a,b,c){var d=Yn(c);if(!b&&"_"!==a[0]){var e=a;W.mark&&(0==e.lastIndexOf("mark_",0)||(e="mark_"+e),c&&(e+=" ("+c+")"),W.mark(e))}e=b||O();d[a]=e;vo(a,b,c)||c||(Ao(),jo("").tick[a]=b||O());return d[a]}
function Bo(){var a=fo(void 0);requestAnimationFrame(function(){setTimeout(function(){a===fo(void 0)&&Z("ol",void 0,void 0)},0)})}
function Ao(){if(!C("yt.timing.pingSent_")){var a=F("TIMING_ACTION",void 0),b=Yn();if(a=!!C("ytglobal.timingready_")&&a)a="_start"in Yn(void 0);if(a&&Xn()){go();a=!0;var c=F("TIMING_WAIT",[]);if(c.length)for(var d=0,e=c.length;d<e;++d)if(!(c[d]in b)){a=!1;break}if(a&&!uo()){c=Yn();d=eo();e=c._start;var f=F("CSI_SERVICE_NAME","youtube");a={v:2,s:f,action:F("TIMING_ACTION",void 0)};b=d.srt;void 0!==c.srt&&delete d.srt;c.aft=Xn();var g=Yn(void 0),h=g.pbr,k=g.vc;g=g.pbs;h&&k&&g&&h<k&&k<g&&eo(void 0).yt_pvis&&
"youtube"===f&&(zo("yt_lt","hot_bg"),f=c.vc,h=c.pbs,delete c.aft,d.aft=Math.round(h-f));for(var l in d)"_"!==l.charAt(0)&&(a[l]=d[l]);c.ps=O();l={};f=[];for(var n in c)"_"!==n.charAt(0)&&(h=Math.round(c[n]-e),l[n]=h,f.push(n+"."+h));a.rt=f.join(",");n=!!d.ap;c="";for(var p in a)a.hasOwnProperty(p)&&(c+="&"+p+"="+a[p]);p="/csi_204?"+c.substring(1);window.navigator&&n?li(p):ii(p);B("yt.timing.pingSent_",!0,void 0);ml(Sn,new Qn(l.aft+(Number(b)||0)))}}}}
function Co(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=bh+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function Do(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;"SCRIPT"===d?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):"LINK"===d&&(c=a.href);bc()&&a.setAttribute("nonce",bc());return c?(a=W.getEntriesByName(c))&&a[0]&&(a=a[0],c=ao(),Z("rsf_"+b,c+Math.round(a.fetchStart)),Z("rse_"+b,c+Math.round(a.responseEnd)),void 0!==a.transferSize&&0===a.transferSize)?!0:!1:!1}
function Eo(){var a=window.location.protocol,b=W.getEntriesByType("resource");b=cb(b,function(c){return 0===c.name.indexOf(a+"//fonts.gstatic.com/s/")});
(b=eb(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&0<b.startTime&&0<b.responseEnd&&(Z("wffs",$n(b.startTime)),Z("wffe",$n(b.responseEnd)))}
var Fo=window;Fo.ytcsi&&(Fo.ytcsi.info=zo,Fo.ytcsi.tick=Z);function Go(){this.A=[];this.F=[];this.h=[];this.l=[];this.m=[];this.i=new Set;this.u=new Map}
function Ho(a,b,c){c=void 0===c?0:c;b.then(function(d){var e,f;a.i.has(c)&&a.j&&a.j();var g=yn(c),h=wn(c);g&&h&&((null===(e=null===d||void 0===d?void 0:d.response)||void 0===e?0:e.trackingParams)&&Hn(a.client,g,h,[sn(d.response.trackingParams)]),(null===(f=null===d||void 0===d?void 0:d.playerResponse)||void 0===f?0:f.trackingParams)&&Hn(a.client,g,h,[sn(d.playerResponse.trackingParams)]))})}
function Io(a,b,c,d){d=void 0===d?0:d;if(a.i.has(d))a.A.push([b,c]);else{var e=yn(d);c=c||wn(d);e&&c&&Hn(a.client,e,c,[b])}}
Go.prototype.clickCommand=function(a,b,c){a=a.clickTrackingParams;c=void 0===c?0:c;if(a)if(c=yn(void 0===c?0:c)){var d=this.client;var e="INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK";a={csn:c,ve:sn(a).getAsJson(),gestureType:e};b&&(a.clientData=b);b={cttAuthInfo:An(c),ha:c};"UNDEFINED_CSN"==c?In("visualElementGestured",a,b):d?aj("visualElementGestured",a,d,b):V("visualElementGestured",a,b);b=!0}else b=!1;else b=!1;return b};
function Jo(a,b,c){c=void 0===c?{}:c;a.i.add(c.layer||0);a.j=function(){Ko(a,b,c);var f=wn(c.layer);if(f){for(var g=t(a.A),h=g.next();!h.done;h=g.next())h=h.value,Io(a,h[0],h[1]||f,c.layer);f=t(a.F);for(g=f.next();!g.done;g=f.next()){var k=g.value;g=void 0;g=void 0===g?0:g;h=yn(g);var l=k[0]||wn(g);h&&l&&(g=a.client,k=k[1],k={csn:h,ve:l.getAsJson(),clientData:k},l={cttAuthInfo:An(h),ha:h},"UNDEFINED_CSN"==h?In("visualElementStateChanged",k,l):g?aj("visualElementStateChanged",k,g,l):V("visualElementStateChanged",
k,l))}}};
yn(c.layer)||a.j();if(c.ib)for(var d=t(c.ib),e=d.next();!e.done;e=d.next())Ho(a,e.value,c.layer);else Sm(Error("Delayed screen needs a data promise."))}
function Ko(a,b,c){c=void 0===c?{}:c;c.layer||(c.layer=0);var d=void 0!==c.Sb?c.Sb:c.layer;var e=yn(d);d=wn(d);var f;d&&(void 0!==c.parentCsn?f={clientScreenNonce:c.parentCsn,visualElement:d}:e&&"UNDEFINED_CSN"!==e&&(f={clientScreenNonce:e,visualElement:d}));var g,h=F("EVENT_ID");"UNDEFINED_CSN"===e&&h&&(g={servletData:{serializedServletEventId:h}});try{var k=a.client;h=f;var l=c.hb,n=c.cttAuthInfo,p=c.nn,u=Fn(),r={csn:u,pageVe:(new rn({veType:b,youtubeData:g})).getAsJson()};h&&h.visualElement?(r.implicitGesture=
{parentCsn:h.clientScreenNonce,gesturedVe:h.visualElement.getAsJson()},p&&(r.implicitGesture.gestureType=p)):h&&Tm(new Jj("newScreen() parent element does not have a VE - rootVe",b));l&&(r.cloneCsn=l);l={cttAuthInfo:n,ha:u};k?aj("screenCreated",r,k,l):V("screenCreated",r,l);ml(pl,new Cn(u));var z=u}catch(A){Um(A,{un:b,rootVe:d,parentVisualElement:void 0,mn:e,tn:f,hb:c.hb});Sm(A);return}Bn(z,b,c.layer,c.cttAuthInfo);if((b=e&&"UNDEFINED_CSN"!==e&&d)&&!(b=N("screen_manager_skip_hide_killswitch"))){a:{b=
t(Object.values(qn));for(f=b.next();!f.done;f=b.next())if(yn(f.value)==e){b=!0;break a}b=!1}b=!b}b&&(b=a.client,f=!0,k=(f=void 0===f?!1:f)?16:8,d={csn:e,ve:d.getAsJson(),eventType:k},f={cttAuthInfo:An(e),ha:e,Jb:f},"UNDEFINED_CSN"==e?In("visualElementHidden",d,f):b?aj("visualElementHidden",d,b,f):V("visualElementHidden",d,f));a.h[a.h.length-1]&&!a.h[a.h.length-1].csn&&(a.h[a.h.length-1].csn=z||"");zo("csn",z);Jn.getInstance().clear();d=wn(c.layer);e&&"UNDEFINED_CSN"!==e&&d&&(N("web_mark_root_visible")||
N("music_web_mark_root_visible"))&&(e=z,z={csn:e,ve:d.getAsJson(),eventType:1},b={cttAuthInfo:An(e),ha:e},"UNDEFINED_CSN"==e?In("visualElementShown",z,b):V("visualElementShown",z,b));a.i.delete(c.layer||0);a.j=void 0;e=t(a.u);for(z=e.next();!z.done;z=e.next())b=t(z.value),z=b.next().value,b=b.next().value,b.has(c.layer)&&d&&Io(a,z,d,c.layer);for(c=0;c<a.l.length;c++){e=a.l[c];try{e()}catch(A){Sm(A)}}for(c=a.l.length=0;c<a.m.length;c++){e=a.m[c];try{e()}catch(A){Sm(A)}}}
;function Lo(a){a&&(a.dataset?a.dataset[Mo("loaded")]="true":a.setAttribute("data-loaded","true"))}
function No(a,b){return a?a.dataset?a.dataset[Mo(b)]:a.getAttribute("data-"+b):null}
var Oo={};function Mo(a){return Oo[a]||(Oo[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;var Po=/\.vflset|-vfl[a-zA-Z0-9_+=-]+/,Qo=/-[a-zA-Z]{2,3}_[a-zA-Z]{2,3}(?=(\/|$))/;function Ro(a,b,c){c=void 0===c?null:c;if(window.spf&&spf.script){c="";if(a){var d=a.indexOf("jsbin/"),e=a.lastIndexOf(".js"),f=d+6;-1<d&&-1<e&&e>f&&(c=a.substring(f,e),c=c.replace(Po,""),c=c.replace(Qo,""),c=c.replace("debug-",""),c=c.replace("tracing-",""))}spf.script.load(a,c,b)}else So(a,b,c)}
function So(a,b,c){c=void 0===c?null:c;var d=To(a),e=document.getElementById(d),f=e&&No(e,"loaded"),g=e&&!f;f?b&&b():(b&&(f=qi(d,b),b=""+Pa(b),Uo[b]=f),g||(e=Vo(a,d,function(){No(e,"loaded")||(Lo(e),ti(d),lh(Wa(ui,d),0))},c)))}
function Vo(a,b,c,d){d=void 0===d?null:d;var e=wd(document,"SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);pd(e,vf(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function Wo(a){a=To(a);var b=document.getElementById(a);b&&(ui(a),b.parentNode.removeChild(b))}
function Xo(a,b){a&&b&&(a=""+Pa(b),(a=Uo[a])&&si(a))}
function To(a){var b=document.createElement("a");Zb(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+dc(a)}
var Uo={};var Yo=[],Zo=!1;function $o(){if(!N("disable_biscotti_fetch_for_ad_blocker_detection")&&!N("disable_biscotti_fetch_entirely_for_all_web_clients")&&cn()&&"1"!=ob()){var a=function(){Zo=!0;"google_ad_status"in window?M("DCLKSTAT",1):M("DCLKSTAT",2)};
try{Ro("//static.doubleclick.net/instream/ad_status.js",a)}catch(b){}Yo.push(uh.M(function(){if(!(Zo||"google_ad_status"in window)){try{Xo("//static.doubleclick.net/instream/ad_status.js",a)}catch(b){}Zo=!0;M("DCLKSTAT",3)}},5E3))}}
function ap(){var a=Number(F("DCLKSTAT",0));return isNaN(a)?0:a}
;function bp(){this.i=!1;this.h=null}
bp.prototype.initialize=function(a,b,c,d){d=void 0===d?!1:d;var e,f;if(a.program){var g=null!==(e=a.interpreterScript)&&void 0!==e?e:null,h=null!==(f=a.interpreterUrl)&&void 0!==f?f:null;if(a.interpreterSafeScript){g=a.interpreterSafeScript;yb("From proto message. b/166824318");g=g.privateDoNotAccessOrElseSafeScriptWrappedValue||"";var k=vb();g=k?k.createScript(g):g;g=(new Ab(g)).toString()}a.interpreterSafeUrl&&(h=a.interpreterSafeUrl,yb("From proto message. b/166824318"),h=Eb(h.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue||
"").toString());cp(this,g,h,a.program,b,c,d)}else Tm(Error("Cannot initialize botguard without program"))};
function cp(a,b,c,d,e,f,g){g=void 0===g?!1:g;c?(a.i=!0,Ro(c,function(){a.i=!1;var h=0<=c.indexOf("/th/");(h?window.trayride:window.botguard)?dp(a,d,!!g,h,e):(Wo(c),Tm(new Jj("Unable to load Botguard","from "+c)))},f)):b&&(f=wd(document,"SCRIPT"),f.textContent=b,f.nonce=bc(),document.head.appendChild(f),document.head.removeChild(f),((b=b.includes("trayride"))?window.trayride:window.botguard)?dp(a,d,!!g,b,e):Tm(Error("Unable to load Botguard from JS")))}
bp.prototype.isInitialized=function(){return!!this.h};
function dp(a,b,c,d,e){var f,g;if(N("use_bg_facade"))if(c=d?"trayride":"botguard",window[c])try{var h=new fd({program:b,globalName:c});e&&h.fc.then(function(){e(b)});
a.h=h}catch(k){k instanceof Error&&Tm(k)}else Tm(Error("VM not loaded, cannot start"));else if(h=d?null===(f=window.trayride)||void 0===f?void 0:f.ad:null===(g=window.botguard)||void 0===g?void 0:g.bg)if(c)try{ep(a,new h(b,e?function(){e(b)}:Ka))}catch(k){k instanceof Error&&Tm(k)}else{try{ep(a,new h(b))}catch(k){k instanceof Error&&Tm(k)}e&&e(b)}else Tm(Error("Failed to finish initializing VM"))}
bp.prototype.invoke=function(a){a=void 0===a?{}:a;if(this.h){if(this.h.yb)return this.h.yb({gb:a});if(this.h.hot)return this.h.hot(void 0,void 0,a);if(this.h.invoke)return this.h.invoke(void 0,void 0,a);Tm(Error("VM has unknown interface"))}return null};
bp.prototype.dispose=function(){this.h=null};
function ep(a,b){a.h=b}
;var fp=new bp;function gp(){return fp.isInitialized()}
function hp(a){a=void 0===a?{}:a;return fp.invoke(a)}
;function ip(){}
ip.getInstance=function(){var a=C("ytglobal.storage_");a||(a=new ip,B("ytglobal.storage_",a,void 0));return a};
ip.prototype.estimate=function(){var a,b,c;return x(function(d){c=navigator;return(null===(a=c.storage)||void 0===a?0:a.estimate)?d.return(c.storage.estimate()):(null===(b=c.webkitTemporaryStorage)||void 0===b?0:b.queryUsageAndQuota)?d.return(jp()):d.return()})};
function jp(){var a=navigator;return new Promise(function(b,c){var d;null!==(d=a.webkitTemporaryStorage)&&void 0!==d&&d.queryUsageAndQuota?a.webkitTemporaryStorage.queryUsageAndQuota(function(e,f){b({usage:e,quota:f})},function(e){c(e)}):c(Error("webkitTemporaryStorage is not supported."))})}
B("ytglobal.storageClass_",ip,void 0);function kp(a,b){var c=this;this.handleError=a;this.h=b;this.i=!1;void 0===self.document||self.addEventListener("beforeunload",function(){c.i=!0});
this.j=Math.random()<=Xg("ytidb_transaction_ended_event_rate_limit",.02)}
kp.prototype.logEvent=function(a,b){switch(a){case "IDB_DATA_CORRUPTED":N("idb_data_corrupted_killswitch")||this.h("idbDataCorrupted",b);break;case "IDB_UNEXPECTEDLY_CLOSED":this.h("idbUnexpectedlyClosed",b);break;case "IS_SUPPORTED_COMPLETED":N("idb_is_supported_completed_killswitch")||this.h("idbIsSupportedCompleted",b);break;case "QUOTA_EXCEEDED":lp(this,b);break;case "TRANSACTION_ENDED":this.j&&this.h("idbTransactionEnded",b);break;case "TRANSACTION_UNEXPECTEDLY_ABORTED":a=Object.assign(Object.assign({},
b),{hasWindowUnloaded:this.i}),this.h("idbTransactionAborted",a)}};
function lp(a,b){ip.getInstance().estimate().then(function(c){c=Object.assign(Object.assign({},b),{isSw:void 0===self.document,isIframe:self!==self.top,deviceStorageUsageMbytes:mp(null===c||void 0===c?void 0:c.usage),deviceStorageQuotaMbytes:mp(null===c||void 0===c?void 0:c.quota)});a.h("idbQuotaExceeded",c)})}
function mp(a){return"undefined"===typeof a?"-1":String(Math.ceil(a/1048576))}
;var np=window;
function op(){var a=np.uaChPolyfill.state;if(0===a.type)V("clientHintsPolyfillEvent",{clientHintsSupported:!1});else{var b=navigator.userAgent,c=void 0!==a.syntheticUa&&a.syntheticUa===b,d={clientHintsSupported:!0,uaAccessedBeforePolyfill:a.didAccessUaBeforePolyfillAvailable,syntheticUaMatches:c};a.didAccessUaBeforePolyfillAvailable&&(d.uaAccessBeforePolyfillCount=a.uaAccessBeforePolyfillCount,a.firstAccessUaError&&(d.firstUaAccessStack=String(a.firstAccessUaError.stack).replace(/\n/g,""),Sm(a.firstAccessUaError)),
d.polyfillAvailabilityDelayMs=a.polyfillAvailabilityDelay);V("clientHintsPolyfillEvent",d);c||(b={syntheticUa:a.syntheticUa,ua:b},b.brand=a.data.brands.map(function(e){return'"'+e.brand+'"; v="'+e.version+'"'}),b.mobileness=a.data.mobile,a=a.data.values,a.architecture&&(b.platformArchitecture=a.architecture),a.model&&(b.model=a.model),a.platform&&(b.platformBrand=a.platform),a.platformVersion&&(b.platformVersion=a.platformVersion),a.uaFullVersion&&(b.fullVersion=a.uaFullVersion),V("clientHintsPolyfillDiagnostics",
b))}}
var pp=!1;function qp(){var a;1===(null===(a=np.uaChPolyfill)||void 0===a?void 0:a.state.type)?pp||(np.uaChPolyfill.onReady=qp,pp=!0):np.uaChPolyfill&&op()}
;function rp(a,b,c){K.call(this);var d=this;c=c||F("POST_MESSAGE_ORIGIN",void 0)||window.document.location.protocol+"//"+window.document.location.hostname;this.j=b||null;this.J="*";this.l=c;this.sessionId=null;this.channel="widget";this.K=!!a;this.C=function(e){a:if(!("*"!=d.l&&e.origin!=d.l||d.j&&e.source!=d.j||"string"!==typeof e.data)){try{var f=JSON.parse(e.data)}catch(g){break a}if(!(null==f||d.K&&(d.sessionId&&d.sessionId!=f.id||d.channel&&d.channel!=f.channel))&&f)switch(f.event){case "listening":"null"!=
e.origin&&(d.l=d.J=e.origin);d.j=e.source;d.sessionId=f.id;d.i&&(d.i(),d.i=null);break;case "command":d.m&&(!d.u||0<=bb(d.u,f.func))&&d.m(f.func,f.args,e.origin)}}};
this.u=this.i=this.m=null;window.addEventListener("message",this.C)}
v(rp,K);rp.prototype.sendMessage=function(a,b){if(b=b||this.j){this.sessionId&&(a.id=this.sessionId);this.channel&&(a.channel=this.channel);try{var c=JSON.stringify(a);b.postMessage(c,this.J)}catch(d){Tg(d)}}};
rp.prototype.G=function(){window.removeEventListener("message",this.C);K.prototype.G.call(this)};function sp(){this.i=[];this.isReady=!1;this.j={};var a=this.h=new rp(!!F("WIDGET_ID_ENFORCE")),b=this.Ub.bind(this);a.m=b;a.u=null;this.h.channel="widget";if(a=F("WIDGET_ID"))this.h.sessionId=a}
m=sp.prototype;m.Ub=function(a,b,c){"addEventListener"===a&&b?(a=b[0],this.j[a]||"onReady"===a||(this.addEventListener(a,tp(this,a)),this.j[a]=!0)):this.ab(a,b,c)};
m.ab=function(){};
function tp(a,b){return function(c){return a.sendMessage(b,c)}}
m.addEventListener=function(){};
m.Kb=function(){this.isReady=!0;this.sendMessage("initialDelivery",this.Pa());this.sendMessage("onReady");E(this.i,this.xb,this);this.i=[]};
m.Pa=function(){return null};
function up(a,b){a.sendMessage("infoDelivery",b)}
m.xb=function(a){this.isReady?this.h.sendMessage(a):this.i.push(a)};
m.sendMessage=function(a,b){this.xb({event:a,info:void 0===b?null:b})};
m.dispose=function(){this.h=null};function vp(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function wp(a,b,c){if("string"===typeof a)return{videoId:a,startSeconds:b,suggestedQuality:c};b=["endSeconds","startSeconds","mediaContentUrl","suggestedQuality","videoId"];c={};for(var d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}
function xp(a,b,c,d){if(Oa(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};"string"===typeof a&&16===a.length?b.list="PL"+a:b.playlist=a;return b}
;function yp(a){sp.call(this);this.listeners=[];this.api=a;this.addEventListener("onReady",this.onReady.bind(this));this.addEventListener("onVideoProgress",this.cc.bind(this));this.addEventListener("onVolumeChange",this.dc.bind(this));this.addEventListener("onApiChange",this.Wb.bind(this));this.addEventListener("onPlaybackQualityChange",this.Yb.bind(this));this.addEventListener("onPlaybackRateChange",this.Zb.bind(this));this.addEventListener("onStateChange",this.ac.bind(this));this.addEventListener("onWebglSettingsChanged",
this.ec.bind(this))}
v(yp,sp);m=yp.prototype;
m.ab=function(a,b,c){if(this.api.isExternalMethodAvailable(a,c)){b=b||[];if(0<b.length&&vp(a)){var d=b;if(Oa(d[0])&&!Array.isArray(d[0]))var e=d[0];else switch(e={},a){case "loadVideoById":case "cueVideoById":e=wp(d[0],void 0!==d[1]?Number(d[1]):void 0,d[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":e=d[0];"string"===typeof e&&(e={mediaContentUrl:e,startSeconds:void 0!==d[1]?Number(d[1]):void 0,suggestedQuality:d[2]});b:{if((d=e.mediaContentUrl)&&(d=/\/([ve]|embed)\/([^#?]+)/.exec(d))&&d[2]){d=
d[2];break b}d=null}e.videoId=d;e=wp(e);break;case "loadPlaylist":case "cuePlaylist":e=xp(d[0],d[1],d[2],d[3])}b.length=1;b[0]=e}this.api.handleExternalCall(a,b,c);vp(a)&&up(this,this.Pa())}};
m.onReady=function(){var a=this.Kb.bind(this);this.h.i=a};
m.addEventListener=function(a,b){this.listeners.push({eventType:a,listener:b});this.api.addEventListener(a,b)};
m.Pa=function(){if(!this.api)return null;var a=this.api.getApiInterface();gb(a,"getVideoData");for(var b={apiInterface:a},c=0,d=a.length;c<d;c++){var e=a[c];if(0===e.search("get")||0===e.search("is")){var f=0;0===e.search("get")?f=3:0===e.search("is")&&(f=2);f=e.charAt(f).toLowerCase()+e.substr(f+1);try{var g=this.api[e]();b[f]=g}catch(h){}}}b.videoData=this.api.getVideoData();b.currentTimeLastUpdated_=Date.now()/1E3;return b};
m.ac=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&(a.storyboardFormat=this.api.getStoryboardFormat());up(this,a)};
m.Yb=function(a){up(this,{playbackQuality:a})};
m.Zb=function(a){up(this,{playbackRate:a})};
m.Wb=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],l=this.api.getOption(e,k);b[e][k]=l}}this.sendMessage("apiInfoDelivery",b)};
m.dc=function(){up(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
m.cc=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());up(this,a)};
m.ec=function(){var a={sphericalProperties:this.api.getSphericalProperties()};up(this,a)};
m.dispose=function(){sp.prototype.dispose.call(this);for(var a=0;a<this.listeners.length;a++){var b=this.listeners[a];this.api.removeEventListener(b.eventType,b.listener)}this.listeners=[]};function zp(a){K.call(this);this.i={};this.started=!1;this.connection=a;this.connection.subscribe("command",this.tb,this)}
v(zp,K);m=zp.prototype;m.start=function(){this.started||this.h()||(this.started=!0,this.connection.la("RECEIVING"))};
m.la=function(a,b){this.started&&!this.h()&&this.connection.la(a,b)};
m.tb=function(a,b,c){if(this.started&&!this.h()){var d=b||{};switch(a){case "addEventListener":"string"===typeof d.event&&this.addListener(d.event);break;case "removeEventListener":"string"===typeof d.event&&this.removeListener(d.event);break;default:this.api.isReady()&&this.api.isExternalMethodAvailable(a,c||null)&&(b=Ap(a,b||{}),c=this.api.handleExternalCall(a,b,c||null),(c=Bp(a,c))&&this.la(a,c))}}};
m.addListener=function(a){if(!(a in this.i)){var b=this.Xb.bind(this,a);this.i[a]=b;this.addEventListener(a,b)}};
m.Xb=function(a,b){this.started&&!this.h()&&this.connection.la(a,this.Oa(a,b))};
m.Oa=function(a,b){if(null!=b)return{value:b}};
m.removeListener=function(a){a in this.i&&(this.removeEventListener(a,this.i[a]),delete this.i[a])};
m.G=function(){var a=this.connection;a.h()||Wf(a.i,"command",this.tb,this);this.connection=null;for(var b in this.i)this.i.hasOwnProperty(b)&&this.removeListener(b);K.prototype.G.call(this)};function Cp(a,b){zp.call(this,b);this.api=a;this.start()}
v(Cp,zp);Cp.prototype.addEventListener=function(a,b){this.api.addEventListener(a,b)};
Cp.prototype.removeEventListener=function(a,b){this.api.removeEventListener(a,b)};
function Ap(a,b){switch(a){case "loadVideoById":return a=wp(b),[a];case "cueVideoById":return a=wp(b),[a];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return a=xp(b),[a];case "cuePlaylist":return a=xp(b),[a];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];
case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function Bp(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
Cp.prototype.Oa=function(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}return zp.prototype.Oa.call(this,a,b)};
Cp.prototype.G=function(){zp.prototype.G.call(this);delete this.api};function Dp(a){a=void 0===a?!1:a;K.call(this);this.i=new L(a);Wd(this,Wa(Ud,this.i))}
D(Dp,K);Dp.prototype.subscribe=function(a,b,c){return this.h()?0:this.i.subscribe(a,b,c)};
Dp.prototype.l=function(a,b){this.h()||this.i.ja.apply(this.i,arguments)};function Ep(a,b,c){Dp.call(this);this.j=a;this.destination=b;this.id=c}
v(Ep,Dp);Ep.prototype.la=function(a,b){this.h()||this.j.la(this.destination,this.id,a,b)};
Ep.prototype.G=function(){this.destination=this.j=null;Dp.prototype.G.call(this)};function Fp(a,b,c){K.call(this);this.destination=a;this.origin=c;this.i=ih(window,"message",this.j.bind(this));this.connection=new Ep(this,a,b);Wd(this,Wa(Ud,this.connection))}
v(Fp,K);Fp.prototype.la=function(a,b,c,d){this.h()||a!==this.destination||(a={id:b,command:c},d&&(a.data=d),this.destination.postMessage(xf(a),this.origin))};
Fp.prototype.j=function(a){var b;if(b=!this.h())if(b=a.origin===this.origin)a:{b=this.destination;do{b:{var c=a.source;do{if(c===b){c=!0;break b}if(c===c.parent)break;c=c.parent}while(null!=c);c=!1}if(c){b=!0;break a}b=b.opener}while(null!=b);b=!1}if(b&&(b=a.data,"string"===typeof b)){try{b=JSON.parse(b)}catch(d){return}b.command&&(c=this.connection,c.h()||c.l("command",b.command,b.data,a.origin))}};
Fp.prototype.G=function(){jh(this.i);this.destination=null;K.prototype.G.call(this)};function Gp(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||qb(b);this.assets=a.assets||{};this.attrs=a.attrs||qb(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
Gp.prototype.clone=function(){var a=new Gp,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];"object"==Ma(c)?a[b]=qb(c):a[b]=c}return a};var Hp=/cssbin\/(?:debug-)?([a-zA-Z0-9_-]+?)(?:-2x|-web|-rtl|-vfl|.css)/;function Ip(a){a=a||"";if(window.spf){var b=a.match(Hp);spf.style.load(a,b?b[1]:"",void 0)}else Jp(a)}
function Jp(a){var b=Kp(a),c=document.getElementById(b),d=c&&No(c,"loaded");d||c&&!d||(c=Lp(a,b,function(){No(c,"loaded")||(Lo(c),ti(b),lh(Wa(ui,b),0))}))}
function Lp(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=vf(a);$b(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function Kp(a){var b=wd(document,"A");yb("This URL is never added to the DOM");Zb(b,new Nb(a,Ob));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+dc(a)}
;function Mp(){K.call(this);this.i=[]}
v(Mp,K);Mp.prototype.G=function(){for(;this.i.length;){var a=this.i.pop();a.target.removeEventListener(a.name,a.cb,void 0)}K.prototype.G.call(this)};function Np(){Mp.apply(this,arguments)}
v(Np,Mp);function Op(a,b,c,d){K.call(this);var e=this;this.K=b;this.webPlayerContextConfig=d;this.Ja=!1;this.api={};this.xa=this.u=null;this.P=new L;this.i={};this.aa=this.ya=this.elementId=this.Ka=this.config=null;this.T=!1;this.l=this.C=null;this.za={};this.Bb=["onReady"];this.lastError=null;this.bb=NaN;this.J={};this.Cb=new Np(this);this.na=0;this.j=this.m=a;Wd(this,Wa(Ud,this.P));Pp(this);Qp(this);Wd(this,Wa(Ud,this.Cb));c?this.na=lh(function(){e.loadNewVideoConfig(c)},0):d&&(Rp(this),Sp(this))}
v(Op,K);m=Op.prototype;m.getId=function(){return this.K};
m.loadNewVideoConfig=function(a){if(!this.h()){this.na&&(mh(this.na),this.na=0);var b=a||{};b instanceof Gp||(b=new Gp(b));this.config=b;this.setConfig(a);Sp(this);this.isReady()&&Tp(this)}};
function Rp(a){var b,c;a.webPlayerContextConfig?c=a.webPlayerContextConfig.rootElementId:c=a.config.attrs.id;a.elementId=c||a.elementId;"video-player"===a.elementId&&(a.elementId=a.K,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.K:a.config.attrs.id=a.K);(null===(b=a.j)||void 0===b?void 0:b.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
m.setConfig=function(a){var b;this.Ka=a;this.config=Up(a);Rp(this);this.ya||(this.ya=Vp(this,(null===(b=this.config.args)||void 0===b?void 0:b.jsapicallback)||"onYouTubePlayerReady"));this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if(null===(c=this.config)||void 0===c?0:c.attrs)a=this.config.attrs,(c=a.width)&&this.j&&(this.j.style.width=Fd(Number(c)||c)),(a=a.height)&&this.j&&(this.j.style.height=Fd(Number(a)||a))};
function Tp(a){var b;a.config&&!0!==a.config.loaded&&(a.config.loaded=!0,!a.config.args||"0"!==a.config.args.autoplay&&0!==a.config.args.autoplay&&!1!==a.config.args.autoplay?a.api.loadVideoByPlayerVars(null!==(b=a.config.args)&&void 0!==b?b:null):a.api.cueVideoByPlayerVars(a.config.args))}
function Wp(a){var b=!0,c=Xp(a);c&&a.config&&(a=Yp(a),b=No(c,"version")===a);return b&&!!C("yt.player.Application.create")}
function Sp(a){if(!a.h()&&!a.T){var b=Wp(a);if(b&&"html5"===(Xp(a)?"html5":null))a.aa="html5",a.isReady()||Zp(a);else if($p(a),a.aa="html5",b&&a.l&&a.m)a.m.appendChild(a.l),Zp(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.C=function(){c=!0;var d=aq(a,"player_bootstrap_method")?C("yt.player.Application.createAlternate")||C("yt.player.Application.create"):C("yt.player.Application.create");var e=a.config?Up(a.config):void 0;d&&d(a.m,e,a.webPlayerContextConfig);Zp(a)};
a.T=!0;b?a.C():(Ro(Yp(a),a.C),(b=bq(a))&&Ip(b),cq(a)&&!c&&B("yt.player.Application.create",null,void 0))}}}
function Xp(a){var b=sd(a.elementId);!b&&a.j&&a.j.querySelector&&(b=a.j.querySelector("#"+a.elementId));return b}
function Zp(a){var b;if(!a.h()){var c=Xp(a),d=!1;c&&c.getApiInterface&&c.getApiInterface()&&(d=!0);d?(a.T=!1,!aq(a,"html5_remove_not_servable_check_killswitch")&&(null===c||void 0===c?0:c.isNotServable)&&a.config&&(null===c||void 0===c?0:c.isNotServable(null===(b=a.config.args)||void 0===b?void 0:b.video_id))||dq(a)):a.bb=lh(function(){Zp(a)},50)}}
function dq(a){Pp(a);a.Ja=!0;var b=Xp(a);if(b){a.u=eq(a,b,"addEventListener");a.xa=eq(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=eq(a,b,f))}}for(var g in a.i)a.i.hasOwnProperty(g)&&a.u&&a.u(g,a.i[g]);Tp(a);a.ya&&a.ya(a.api);a.P.ja("onReady",a.api)}
function eq(a,b,c){var d=b[c];return function(){var e=Ea.apply(0,arguments);try{return a.lastError=null,d.apply(b,e)}catch(f){"sendAbandonmentPing"!==c&&(f.params=c,a.lastError=f,Tm(f))}}}
function Pp(a){a.Ja=!1;if(a.xa)for(var b in a.i)a.i.hasOwnProperty(b)&&a.xa(b,a.i[b]);for(var c in a.J)a.J.hasOwnProperty(c)&&mh(Number(c));a.J={};a.u=null;a.xa=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.Ka};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
m.isReady=function(){return this.Ja};
function Qp(a){a.addEventListener("WATCH_LATER_VIDEO_ADDED",function(b){ti("WATCH_LATER_VIDEO_ADDED",b)});
a.addEventListener("WATCH_LATER_VIDEO_REMOVED",function(b){ti("WATCH_LATER_VIDEO_REMOVED",b)});
a.addEventListener("onAdAnnounce",function(b){ti("a11y-announce",b)})}
m.addEventListener=function(a,b){var c=this,d=Vp(this,b);d&&(0<=bb(this.Bb,a)||this.i[a]||(b=fq(this,a),this.u&&this.u(a,b)),this.P.subscribe(a,d),"onReady"===a&&this.isReady()&&lh(function(){d(c.api)},0))};
m.removeEventListener=function(a,b){this.h()||(b=Vp(this,b))&&Wf(this.P,a,b)};
function Vp(a,b){var c=b;if("string"===typeof b){if(a.za[b])return a.za[b];c=function(){var d=Ea.apply(0,arguments),e=C(b);if(e)try{e.apply(y,d)}catch(f){Sm(f)}};
a.za[b]=c}return c?c:null}
function fq(a,b){var c="ytPlayer"+b+a.K;a.i[b]=c;y[c]=function(d){var e=lh(function(){if(!a.h()){a.P.ja(b,null!==d&&void 0!==d?d:void 0);var f=a.J,g=String(e);g in f&&delete f[g]}},0);
nb(a.J,String(e))};
return c}
m.getPlayerType=function(){return this.aa||(Xp(this)?"html5":null)};
m.getLastError=function(){return this.lastError};
function $p(a){a.cancel();Pp(a);a.aa=null;a.config&&(a.config.loaded=!1);var b=Xp(a);b&&(Wp(a)||!cq(a)?a.l=b:(b&&b.destroy&&b.destroy(),a.l=null));if(a.m)for(a=a.m;b=a.firstChild;)a.removeChild(b)}
m.cancel=function(){this.C&&Xo(Yp(this),this.C);mh(this.bb);this.T=!1};
m.G=function(){$p(this);if(this.l&&this.config&&this.l.destroy)try{this.l.destroy()}catch(b){Sm(b)}this.za=null;for(var a in this.i)this.i.hasOwnProperty(a)&&(y[this.i[a]]=null);this.Ka=this.config=this.api=null;delete this.m;delete this.j;K.prototype.G.call(this)};
function cq(a){var b,c;a=null===(c=null===(b=a.config)||void 0===b?void 0:b.args)||void 0===c?void 0:c.fflags;return!!a&&-1!==a.indexOf("player_destroy_old_version=true")}
function Yp(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function bq(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function aq(a,b){var c;if(a.webPlayerContextConfig)var d=a.webPlayerContextConfig.serializedExperimentFlags;else if(null===(c=a.config)||void 0===c?0:c.args)d=a.config.args.fflags;return"true"===Fh(d||"","&")[b]}
function Up(a){for(var b={},c=t(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]="object"===typeof e?qb(e):e}return b}
;var gq={},hq="player_uid_"+(1E9*Math.random()>>>0);function iq(a,b,c){var d="player";c=void 0===c?!0:c;d="string"===typeof d?sd(d):d;var e=hq+"_"+Pa(d),f=gq[e];if(f&&c)return jq(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new Op(d,e,a,b);gq[e]=f;ti("player-added",f.api);Wd(f,function(){delete gq[f.getId()]});
return f.api}
function jq(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var kq=null,lq=null,mq=null;function nq(){var a=kq.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
;function oq(a,b,c){a="ST-"+dc(a).toString(36);b=b?ic(b):"";c=c||5;cn()&&dj(a,b,c)}
;function pq(a,b,c){b=void 0===b?{}:b;c=void 0===c?!1:c;var d=F("EVENT_ID");d&&(b.ei||(b.ei=d));if(b){d=a;var e=void 0===e?!0:e;var f=F("VALID_SESSION_TEMPDATA_DOMAINS",[]),g=gc(window.location.href);g&&f.push(g);g=gc(d);if(0<=bb(f,g)||!g&&0==d.lastIndexOf("/",0))if(N("autoescape_tempdata_url")&&(f=document.createElement("a"),Zb(f,d),d=f.href),d){g=d.match(ec);d=g[5];f=g[6];g=g[7];var h="";d&&(h+=d);f&&(h+="?"+f);g&&(h+="#"+g);d=h;f=d.indexOf("#");if(d=0>f?d:d.substr(0,f))if(e&&!b.csn&&(b.itct||b.ved)&&
(b=Object.assign({csn:yn()},b)),k){var k=parseInt(k,10);isFinite(k)&&0<k&&oq(d,b,k)}else oq(d,b)}}if(c)return!1;if((window.ytspf||{}).enabled)spf.navigate(a);else{var l=void 0===l?{}:l;var n=void 0===n?"":n;var p=void 0===p?window:p;c=p.location;a=jc(a,l)+n;var u=void 0===u?nd:u;a:{u=void 0===u?nd:u;for(l=0;l<u.length;++l)if(n=u[l],n instanceof ld&&n.isValid(a)){u=new jd(a,hd);break a}u=void 0}c.href=od(u||kd)}return!0}
;B("yt.setConfig",M,void 0);B("yt.config.set",M,void 0);B("yt.setMsg",Vg,void 0);B("yt.msgs.set",Vg,void 0);B("yt.logging.errors.log",Sm,void 0);
B("writeEmbed",function(){var a=F("PLAYER_CONFIG",void 0);if(!a){var b=F("PLAYER_VARS",void 0);b&&(a={args:b})}ln(!0);"gvn"===a.args.ps&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=F("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);N("embeds_js_api_set_1p_cookie")&&(c=Kh(),c.embedsTokenValue&&(a.args.embedsTokenValue=c.embedsTokenValue));M("FORCE_CSI_ON_GEL",!0);
c=["ol"];jo("").info.actionType="embed";c&&M("TIMING_AFT_KEYS",c);M("TIMING_ACTION","embed");c=F("TIMING_INFO",{});for(var d in c)c.hasOwnProperty(d)&&zo(d,c[d]);zo("is_nav",1);(d=yn())&&zo("csn",d);(d=F("PREVIOUS_ACTION",void 0))&&!uo()&&zo("pa",d);d=eo();c=F("CLIENT_PROTOCOL");var e=F("CLIENT_TRANSPORT");c&&zo("p",c);e&&zo("t",e);zo("yt_vis",Co());zo("yt_lt","cold");c=Zn();if(e=ao())Z("srt",c.responseStart),1!==d.prerender&&(zo("yt_sts","n",void 0),Z("_start",e,void 0));d=ho();0<d&&Z("fpt",d);d=
Zn();d.isPerformanceNavigationTiming&&zo("pnt",1,void 0);Z("nreqs",d.requestStart,void 0);Z("nress",d.responseStart,void 0);Z("nrese",d.responseEnd,void 0);0<d.redirectEnd-d.redirectStart&&(Z("nrs",d.redirectStart,void 0),Z("nre",d.redirectEnd,void 0));0<d.domainLookupEnd-d.domainLookupStart&&(Z("ndnss",d.domainLookupStart,void 0),Z("ndnse",d.domainLookupEnd,void 0));0<d.connectEnd-d.connectStart&&(Z("ntcps",d.connectStart,void 0),Z("ntcpe",d.connectEnd,void 0));d.secureConnectionStart>=ao()&&0<d.connectEnd-
d.secureConnectionStart&&(Z("nstcps",d.secureConnectionStart,void 0),Z("ntcpe",d.connectEnd,void 0));W&&W.getEntriesByType&&Eo();d=[];if(document.querySelector&&W&&W.getEntriesByName)for(var f in Wn)Wn.hasOwnProperty(f)&&(c=Wn[f],Do(f,c)&&d.push(c));for(f=0;f<d.length;f++)zo("rc",d[f]);if(uo(void 0)){f={actionType:oo[F("TIMING_ACTION",void 0)]||"LATENCY_ACTION_UNKNOWN",previousAction:oo[F("PREVIOUS_ACTION",void 0)]||"LATENCY_ACTION_UNKNOWN"};if(d=yn())f.clientScreenNonce=d;d=fo(void 0);c=bo(void 0).cttAuthInfo;
mo().info(f,d,c)}f=eo();c=Yn();if("cold"===f.yt_lt&&(d=wo(),e=d.gelTicks?d.gelTicks:d.gelTicks={},d=d.gelInfos?d.gelInfos:d.gelInfos={},uo())){for(var g in c)"tick_"+g in e||vo(g,c[g]);g=yo();c=fo();e=bo().cttAuthInfo;var h={},k=!1,l;for(l in f)if(!("info_"+l in d)){var n=xo(l,f[l]);n&&(Kn(g,n),Kn(h,n),k=!0)}k&&mo().info(h,c,e)}B("ytglobal.timingready_",!0,void 0);Ao();(l=F("WEB_PLAYER_CONTEXT_CONFIGS",void 0))&&"WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER"in l?(l=l.WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER,
l.serializedForcedExperimentIds||(g=Kh(),g.forced_experiments&&(l.serializedForcedExperimentIds=g.forced_experiments)),kq=iq(a,l,!1)):kq=iq(a);kq.addEventListener("onVideoDataChange",nq);a=F("POST_MESSAGE_ID","player");F("ENABLE_JS_API")?mq=new yp(kq):F("ENABLE_POST_API")&&"string"===typeof a&&"string"===typeof b&&(lq=new Fp(window.parent,a,b),mq=new Cp(kq,lq.connection));$o();if(!N("ytidb_create_logger_embed_killswitch"))for(a={},Fj=new kp(void 0===a.handleError?Rm:a.handleError,void 0===a.logEvent?
V:a.logEvent);0<Ej.length;)switch(a=Ej.shift(),a.type){case "ERROR":Fj.handleError(a.payload);break;case "EVENT":Fj.logEvent(a.eventType,a.payload)}N("networkless_logging_web_embedded")&&(N("embeds_web_enable_new_nwl")?dm():km());N("embeds_enable_ua_ch_polyfill")&&qp()},void 0);
var qq=Rg(function(){Bo();var a=fj.getInstance(),b=!!((ij("f"+(Math.floor(119/31)+1))||0)&67108864),c=1<window.devicePixelRatio;if(document.body&&df(document.body,"exp-invert-logo"))if(c&&!df(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!df(d,"inverted-hdpi")){var e=bf(d);cf(d,e+(0<e.length?" inverted-hdpi":"inverted-hdpi"))}}else!c&&df(document.body,"inverted-hdpi")&&ef();if(b!=c){b="f"+(Math.floor(119/31)+1);d=ij(b)||0;d=c?d|67108864:
d&-67108865;0==d?delete ej[b]:(c=d.toString(16),ej[b]=c.toString());c=!0;N("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.h;d=[];for(var f in ej)d.push(f+"="+encodeURIComponent(String(ej[f])));dj(b,d.join("&"),63072E3,a.i,c)}Go.h||(Go.h=new Go);a=Go.h;f=16623;var g=void 0===g?{}:g;Object.values(Vm).includes(f)||(Tm(new Jj("createClientScreen() called with a non-page VE",f)),f=83769);g.isHistoryNavigation||a.h.push({rootVe:f,key:g.key||""});a.A=[];a.F=[];g.ib?Jo(a,f,g):Ko(a,f,g)}),rq=Rg(function(){kq&&
kq.sendAbandonmentPing&&kq.sendAbandonmentPing();
F("PL_ATT")&&fp.dispose();for(var a=0,b=Yo.length;a<b;a++)uh.ca(Yo[a]);Yo.length=0;Wo("//static.doubleclick.net/instream/ad_status.js");Zo=!1;M("DCLKSTAT",0);(0,Vd)(mq,lq);kq&&(kq.removeEventListener("onVideoDataChange",nq),kq.destroy())});
window.addEventListener?(window.addEventListener("load",qq),window.addEventListener("unload",rq)):window.attachEvent&&(window.attachEvent("onload",qq),window.attachEvent("onunload",rq));Xa("yt.abuse.player.botguardInitialized",C("yt.abuse.player.botguardInitialized")||gp);Xa("yt.abuse.player.invokeBotguard",C("yt.abuse.player.invokeBotguard")||hp);Xa("yt.abuse.dclkstatus.checkDclkStatus",C("yt.abuse.dclkstatus.checkDclkStatus")||ap);
Xa("yt.player.exports.navigate",C("yt.player.exports.navigate")||pq);Xa("yt.util.activity.init",C("yt.util.activity.init")||wh);Xa("yt.util.activity.getTimeSinceActive",C("yt.util.activity.getTimeSinceActive")||zh);Xa("yt.util.activity.setTimestamp",C("yt.util.activity.setTimestamp")||xh);}).call(this);
