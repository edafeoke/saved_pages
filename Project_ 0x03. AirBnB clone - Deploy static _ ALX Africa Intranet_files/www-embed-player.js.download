(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
'use strict';var n;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ea(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var fa=ea(this);function p(a,b){if(b)a:{var c=fa;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
p("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.h=f;ba(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d="jscomp_symbol_"+(1E9*Math.random()>>>0)+"_",e=0;return b});
p("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=fa[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ha(aa(this))}})}return a});
function ha(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function r(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];return b?b.call(a):{next:aa(a)}}
function ia(a){if(!(a instanceof Array)){a=r(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
var ja="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},ka=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if("undefined"!=typeof Reflect&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){void 0===e&&(e=c);
e=ja(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),la;
if("function"==typeof Object.setPrototypeOf)la=Object.setPrototypeOf;else{var ma;a:{var na={a:!0},oa={};try{oa.__proto__=na;ma=oa.a;break a}catch(a){}ma=!1}la=ma?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var pa=la;
function u(a,b){a.prototype=ja(b.prototype);a.prototype.constructor=a;if(pa)pa(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.Z=b.prototype}
function qa(){this.D=!1;this.l=null;this.i=void 0;this.h=1;this.o=this.m=0;this.A=this.j=null}
function ra(a){if(a.D)throw new TypeError("Generator is already running");a.D=!0}
qa.prototype.u=function(a){this.i=a};
function sa(a,b){a.j={zb:b,Db:!0};a.h=a.m||a.o}
qa.prototype.return=function(a){this.j={return:a};this.h=this.o};
function v(a,b,c){a.h=c;return{value:b}}
qa.prototype.s=function(a){this.h=a};
function ta(a,b,c){a.m=b;void 0!=c&&(a.o=c)}
function ua(a,b){a.h=b;a.m=0}
function va(a){a.m=0;var b=a.j.zb;a.j=null;return b}
function wa(a){a.A=[a.j];a.m=0;a.o=0}
function xa(a){var b=a.A.splice(0)[0];(b=a.j=a.j||b)?b.Db?a.h=a.m||a.o:void 0!=b.s&&a.o<b.s?(a.h=b.s,a.j=null):a.h=a.o:a.h=0}
function ya(a){this.h=new qa;this.i=a}
function za(a,b){ra(a.h);var c=a.h.l;if(c)return Aa(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return Ba(a)}
function Aa(a,b,c,d){try{var e=b.call(a.h.l,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.D=!1,e;var f=e.value}catch(g){return a.h.l=null,sa(a.h,g),Ba(a)}a.h.l=null;d.call(a.h,f);return Ba(a)}
function Ba(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.D=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,sa(a.h,c)}a.h.D=!1;if(a.h.j){b=a.h.j;a.h.j=null;if(b.Db)throw b.zb;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
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
p("Reflect",function(a){return a?a:{}});
p("Reflect.construct",function(){return ka});
p("Reflect.setPrototypeOf",function(a){return a?a:pa?function(b,c){try{return pa(b,c),!0}catch(d){return!1}}:null});
p("Promise",function(a){function b(g){this.h=0;this.j=void 0;this.i=[];this.D=!1;var h=this.l();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(null==this.h){this.h=[];var h=this;this.j(function(){h.o()})}this.h.push(g)};
var e=fa.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.o=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.l(l)}}}this.h=null};
c.prototype.l=function(g){this.j(function(){throw g;})};
b.prototype.l=function(){function g(l){return function(m){k||(k=!0,l.call(h,m))}}
var h=this,k=!1;return{resolve:g(this.S),reject:g(this.o)}};
b.prototype.S=function(g){if(g===this)this.o(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.ga(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.L(g):this.m(g)}};
b.prototype.L=function(g){var h=void 0;try{h=g.then}catch(k){this.o(k);return}"function"==typeof h?this.sa(h,g):this.m(g)};
b.prototype.o=function(g){this.u(2,g)};
b.prototype.m=function(g){this.u(1,g)};
b.prototype.u=function(g,h){if(0!=this.h)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.h);this.h=g;this.j=h;2===this.h&&this.Y();this.A()};
b.prototype.Y=function(){var g=this;e(function(){if(g.K()){var h=fa.console;"undefined"!==typeof h&&h.error(g.j)}},1)};
b.prototype.K=function(){if(this.D)return!1;var g=fa.CustomEvent,h=fa.Event,k=fa.dispatchEvent;if("undefined"===typeof k)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=fa.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.j;return k(g)};
b.prototype.A=function(){if(null!=this.i){for(var g=0;g<this.i.length;++g)f.i(this.i[g]);this.i=null}};
var f=new c;b.prototype.ga=function(g){var h=this.l();g.Ma(h.resolve,h.reject)};
b.prototype.sa=function(g,h){var k=this.l();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(w,t){return"function"==typeof w?function(z){try{l(w(z))}catch(B){m(B)}}:t}
var l,m,q=new b(function(w,t){l=w;m=t});
this.Ma(k(g,l),k(h,m));return q};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.Ma=function(g,h){function k(){switch(l.h){case 1:g(l.j);break;case 2:h(l.j);break;default:throw Error("Unexpected state: "+l.h);}}
var l=this;null==this.i?f.i(k):this.i.push(k);this.D=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=r(g),m=l.next();!m.done;m=l.next())d(m.value).Ma(h,k)})};
b.all=function(g){var h=r(g),k=h.next();return k.done?d([]):new b(function(l,m){function q(z){return function(B){w[z]=B;t--;0==t&&l(w)}}
var w=[],t=0;do w.push(void 0),t++,d(k.value).Ma(q(w.length-1),m),k=h.next();while(!k.done)})};
return b});
function Fa(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
p("WeakMap",function(a){function b(k){this.h=(h+=Math.random()+1).toString();if(k){k=r(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return"object"===l&&null!==k||"function"===l}
function e(k){if(!Fa(k,g)){var l=new c;ba(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(m){if(m instanceof c)return m;Object.isExtensible(m)&&e(m);return l(m)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),m=new a([[k,2],[l,3]]);if(2!=m.get(k)||3!=m.get(l))return!1;m.delete(k);m.set(l,4);return!m.has(k)&&4==m.get(l)}catch(q){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!Fa(k,g))throw Error("WeakMap key fail: "+k);k[g][this.h]=l;return this};
b.prototype.get=function(k){return d(k)&&Fa(k,g)?k[g][this.h]:void 0};
b.prototype.has=function(k){return d(k)&&Fa(k,g)&&Fa(k[g],this.h)};
b.prototype.delete=function(k){return d(k)&&Fa(k,g)&&Fa(k[g],this.h)?delete k[g][this.h]:!1};
return b});
p("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h.h;return ha(function(){if(l){for(;l.head!=h.h;)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;"object"==l||"function"==l?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var m=h.data_[l];if(m&&Fa(h.data_,l))for(h=0;h<m.length;h++){var q=m[h];if(k!==k&&q.key!==q.key||k===q.key)return{id:l,list:m,index:h,entry:q}}return{id:l,list:m,index:-1,entry:void 0}}
function e(h){this.data_={};this.h=b();this.size=0;if(h){h=r(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(r([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var l=k.entries(),m=l.next();if(m.done||m.value[0]!=h||"s"!=m.value[1])return!1;m=l.next();return m.done||4!=m.value[0].x||"t"!=m.value[1]||!l.next().done?!1:!0}catch(q){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=0===h?0:h;var l=d(this,h);l.list||(l.list=this.data_[l.id]=[]);l.entry?l.entry.value=k:(l.entry={next:this.h,previous:this.h.previous,head:this.h,key:h,value:k},l.list.push(l.entry),this.h.previous.next=l.entry,this.h.previous=l.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this.data_[h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this.data_={};this.h=this.h.previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var l=this.entries(),m;!(m=l.next()).done;)m=m.value,h.call(k,m[1],m[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
function Ga(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
p("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ga(this,b,"endsWith");b+="";void 0===c&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;0<e&&0<c;)if(d[--c]!=b[--e])return!1;return 0>=e}});
p("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
p("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ga(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
function Ha(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
p("Array.prototype.entries",function(a){return a?a:function(){return Ha(this,function(b,c){return[b,c]})}});
p("Object.setPrototypeOf",function(a){return a||pa});
var Ia="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)Fa(d,e)&&(a[e]=d[e])}return a};
p("Object.assign",function(a){return a||Ia});
p("Set",function(a){function b(c){this.h=new Map;if(c){c=r(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(r([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
p("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)Fa(b,d)&&c.push([d,b[d]]);return c}});
p("Array.prototype.keys",function(a){return a?a:function(){return Ha(this,function(b){return b})}});
p("Array.prototype.values",function(a){return a?a:function(){return Ha(this,function(b,c){return c})}});
p("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
p("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
p("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==Ga(this,b,"includes").indexOf(b,c||0)}});
p("Array.from",function(a){return a?a:function(b,c,d){c=null!=c?c:function(h){return h};
var e=[],f="undefined"!=typeof Symbol&&Symbol.iterator&&b[Symbol.iterator];if("function"==typeof f){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
p("Number.isNaN",function(a){return a?a:function(b){return"number"===typeof b&&isNaN(b)}});
p("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
p("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)Fa(b,d)&&c.push(b[d]);return c}});
var y=this||self;function A(a,b,c){a=a.split(".");c=c||y;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function C(a,b){a=a.split(".");b=b||y;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b}
function Ja(){}
function Ka(a){a.oa=void 0;a.getInstance=function(){return a.oa?a.oa:a.oa=new a}}
function La(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function Ma(a){var b=La(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function Na(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Oa(a){return Object.prototype.hasOwnProperty.call(a,Pa)&&a[Pa]||(a[Pa]=++Qa)}
var Pa="closure_uid_"+(1E9*Math.random()>>>0),Qa=0;function Ra(a,b,c){return a.call.apply(a.bind,arguments)}
function Sa(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Ta(a,b,c){Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?Ta=Ra:Ta=Sa;return Ta.apply(null,arguments)}
function Va(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function Wa(a,b){A(a,b,void 0)}
function Xa(a,b){function c(){}
c.prototype=b.prototype;a.Z=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.oo=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function Ya(a){return a}
;function Za(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,Za);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));void 0!==b&&(this.Tb=b)}
Xa(Za,Error);Za.prototype.name="CustomError";function $a(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.j=!b&&/[?&]ae=1(&|$)/.test(a);this.l=!b&&/[?&]ae=2(&|$)/.test(a);if((this.h=/[?&]adurl=([^&]*)/.exec(a))&&this.h[1]){try{var c=decodeURIComponent(this.h[1])}catch(d){c=null}this.i=c}}
;function ab(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var cb=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},db=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},eb=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f="string"===typeof a?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},fb=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e="string"===typeof a?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},gb=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
db(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function hb(a,b){a:{for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return 0>b?null:"string"===typeof a?a.charAt(b):a[b]}
function ib(a,b){b=cb(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c}
function jb(a){var b=a.length;if(0<b){for(var c=Array(b),d=0;d<b;d++)c[d]=a[d];return c}return[]}
function kb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Ma(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function lb(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function mb(a){var b=nb,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function ob(a){for(var b in a)return!1;return!0}
function pb(a,b){if(null!==a&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function qb(){var a=D("PLAYER_VARS",{});return null!==a&&"privembed"in a?a.privembed:!1}
function rb(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function sb(a){var b={},c;for(c in a)b[c]=a[c];return b}
function tb(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();if("undefined"!==typeof Map&&a instanceof Map)return new Map(a);if("undefined"!==typeof Set&&a instanceof Set)return new Set(a);var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=tb(a[c]);return b}
var ub="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function vb(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<ub.length;f++)c=ub[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var wb;function xb(){if(void 0===wb){var a=null,b=y.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:Ya,createScript:Ya,createScriptURL:Ya})}catch(c){y.console&&y.console.error(c.message)}wb=a}else wb=a}return wb}
;function yb(a,b){this.h=a===zb&&b||""}
yb.prototype.ja=!0;yb.prototype.ia=function(){return this.h};
function Ab(a){return new yb(zb,a)}
var zb={};Ab("");var Bb={};function Cb(a){this.h=Bb===Bb?a:"";this.ja=!0}
Cb.prototype.ia=function(){return this.h.toString()};
Cb.prototype.toString=function(){return this.h.toString()};function Db(a,b){this.h=b===Eb?a:""}
n=Db.prototype;n.ja=!0;n.ia=function(){return this.h.toString()};
n.gb=!0;n.ab=function(){return 1};
n.toString=function(){return this.h+""};
function Fb(a){if(a instanceof Db&&a.constructor===Db)return a.h;La(a);return"type_error:TrustedResourceUrl"}
var Eb={};function Gb(a){var b=xb();a=b?b.createScriptURL(a):a;return new Db(a,Eb)}
;var Hb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]},Ib=/&/g,Jb=/</g,Kb=/>/g,Lb=/"/g,Mb=/'/g,Nb=/\x00/g,Ob=/[\x00&<>"']/;function Pb(a,b){this.h=b===Qb?a:""}
n=Pb.prototype;n.ja=!0;n.ia=function(){return this.h.toString()};
n.gb=!0;n.ab=function(){return 1};
n.toString=function(){return this.h.toString()};
function Rb(a){if(a instanceof Pb&&a.constructor===Pb)return a.h;La(a);return"type_error:SafeUrl"}
var Sb=RegExp('^(?:audio/(?:3gpp2|3gpp|aac|L16|midi|mp3|mp4|mpeg|oga|ogg|opus|x-m4a|x-matroska|x-wav|wav|webm)|font/\\w+|image/(?:bmp|gif|jpeg|jpg|png|tiff|webp|x-icon)|video/(?:mpeg|mp4|ogg|webm|quicktime|x-matroska))(?:;\\w+=(?:\\w+|"[\\w;,= ]+"))*$',"i"),Tb=/^data:(.*);base64,[a-z0-9+\/]+=*$/i,Ub=/^(?:(?:https?|mailto|ftp):|[^:/?#]*(?:[/?#]|$))/i,Qb={},Vb=new Pb("about:invalid#zClosurez",Qb);function Wb(){var a=y.navigator;return a&&(a=a.userAgent)?a:""}
function E(a){return-1!=Wb().indexOf(a)}
;function Xb(){return(E("Chrome")||E("CriOS"))&&!E("Edge")||E("Silk")}
;var Yb={};function Zb(a,b,c){this.h=c===Yb?a:"";this.i=b;this.ja=this.gb=!0}
Zb.prototype.ab=function(){return this.i};
Zb.prototype.ia=function(){return this.h.toString()};
Zb.prototype.toString=function(){return this.h.toString()};
function $b(a,b){var c=xb();a=c?c.createHTML(a):a;return new Zb(a,b,Yb)}
;function ac(a,b){b instanceof Pb||b instanceof Pb||(b="object"==typeof b&&b.ja?b.ia():String(b),Ub.test(b)||(b="about:invalid#zClosurez"),b=new Pb(b,Qb));a.href=Rb(b)}
function bc(a,b){a.rel="stylesheet";a.href=Fb(b).toString();(b=cc('style[nonce],link[rel="stylesheet"][nonce]',a.ownerDocument&&a.ownerDocument.defaultView))&&a.setAttribute("nonce",b)}
function dc(){return cc("script[nonce]",void 0)}
var ec=/^[\w+/_-]+[=]{0,2}$/;function cc(a,b){b=(b||y).document;return b.querySelector?(a=b.querySelector(a))&&(a=a.nonce||a.getAttribute("nonce"))&&ec.test(a)?a:"":""}
;function fc(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var gc=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function hc(a){return a?decodeURI(a):a}
function ic(a){return hc(a.match(gc)[3]||null)}
function jc(a){var b=a.match(gc);a=b[5];var c=b[6];b=b[7];var d="";a&&(d+=a);c&&(d+="?"+c);b&&(d+="#"+b);return d}
function kc(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)kc(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function lc(a){var b=[],c;for(c in a)kc(c,a[c],b);return b.join("&")}
function mc(a,b){b=lc(b);if(b){var c=a.indexOf("#");0>c&&(c=a.length);var d=a.indexOf("?");if(0>d||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.substr(0,d),e,a.substr(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;b=a[0]+(a[1]?"?"+a[1]:"")+a[2]}else b=a;return b}
var nc=/#|$/;function oc(){return E("iPhone")&&!E("iPod")&&!E("iPad")}
;function pc(a){pc[" "](a);return a}
pc[" "]=Ja;var qc=E("Opera"),rc=E("Trident")||E("MSIE"),sc=E("Edge"),tc=E("Gecko")&&!(-1!=Wb().toLowerCase().indexOf("webkit")&&!E("Edge"))&&!(E("Trident")||E("MSIE"))&&!E("Edge"),uc=-1!=Wb().toLowerCase().indexOf("webkit")&&!E("Edge"),vc=E("Android");function wc(){var a=y.document;return a?a.documentMode:void 0}
var xc;a:{var yc="",zc=function(){var a=Wb();if(tc)return/rv:([^\);]+)(\)|;)/.exec(a);if(sc)return/Edge\/([\d\.]+)/.exec(a);if(rc)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(uc)return/WebKit\/(\S+)/.exec(a);if(qc)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
zc&&(yc=zc?zc[1]:"");if(rc){var Ac=wc();if(null!=Ac&&Ac>parseFloat(yc)){xc=String(Ac);break a}}xc=yc}var Bc=xc,Cc;if(y.document&&rc){var Dc=wc();Cc=Dc?Dc:parseInt(Bc,10)||void 0}else Cc=void 0;var Ec=Cc;var Fc=oc()||E("iPod"),Gc=E("iPad");!E("Android")||Xb();Xb();var Hc=E("Safari")&&!(Xb()||E("Coast")||E("Opera")||E("Edge")||E("Edg/")||E("OPR")||E("Firefox")||E("FxiOS")||E("Silk")||E("Android"))&&!(oc()||E("iPad")||E("iPod"));var Ic={},Jc=null;
function Kc(a,b){Ma(a);void 0===b&&(b=0);if(!Jc){Jc={};for(var c="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),d=["+/=","+/","-_=","-_.","-_"],e=0;5>e;e++){var f=c.concat(d[e].split(""));Ic[e]=f;for(var g=0;g<f.length;g++){var h=f[g];void 0===Jc[h]&&(Jc[h]=g)}}}b=Ic[b];c=Array(Math.floor(a.length/3));d=b[64]||"";for(e=f=0;f<a.length-2;f+=3){var k=a[f],l=a[f+1];h=a[f+2];g=b[k>>2];k=b[(k&3)<<4|l>>4];l=b[(l&15)<<2|h>>6];h=b[h&63];c[e++]=""+g+k+l+h}g=0;h=d;switch(a.length-
f){case 2:g=a[f+1],h=b[(g&15)<<2]||d;case 1:a=a[f],c[e]=""+b[a>>2]+b[(a&3)<<4|g>>4]+h+d}return c.join("")}
;var Lc="function"===typeof Uint8Array;var Mc="function"===typeof Symbol&&"symbol"===typeof Symbol()?Symbol(void 0):void 0;function Nc(a){Object.isFrozen(a)||(Mc?a[Mc]|=1:void 0!==a.h?a.h|=1:Object.defineProperties(a,{h:{value:1,configurable:!0,writable:!0,enumerable:!1}}));return a}
;function Oc(a){return null!==a&&"object"===typeof a&&!Array.isArray(a)&&a.constructor===Object}
var Pc;function Qc(a){switch(typeof a){case "number":return isFinite(a)?a:String(a);case "object":if(a&&!Array.isArray(a)&&Lc&&null!=a&&a instanceof Uint8Array)return Kc(a)}return a}
;function Rc(a,b){if(null!=a){if(Array.isArray(a))a=Sc(a,b);else if(Oc(a)){var c={},d;for(d in a)c[d]=Rc(a[d],b);a=c}else a=b(a);return a}}
function Sc(a,b){for(var c=a.slice(),d=0;d<c.length;d++)c[d]=Rc(c[d],b);if(Array.isArray(a)){var e;Mc?e=a[Mc]:e=a.h;a=!!((null==e?0:e)&1)}else a=!1;a&&Nc(c);return c}
function Tc(a){if(a&&"object"==typeof a&&a.toJSON)return a.toJSON();a=Qc(a);return Array.isArray(a)?Sc(a,Tc):a}
function Uc(a){return Lc&&null!=a&&a instanceof Uint8Array?new Uint8Array(a):a}
;var Vc;function F(a,b,c){var d=Vc;Vc=null;a||(a=d);d=this.constructor.wo;a||(a=d?[d]:[]);this.j=(d?0:-1)-(this.constructor.uo||0);this.h=void 0;this.N=a;a:{d=this.N.length;a=d-1;if(d&&(d=this.N[a],Oc(d))){this.l=a-this.j;this.i=d;break a}void 0!==b&&-1<b?(this.l=Math.max(b,a+1-this.j),this.i=void 0):this.l=Number.MAX_VALUE}if(c)for(b=0;b<c.length;b++)if(a=c[b],a<this.l)a+=this.j,(d=this.N[a])?Array.isArray(d)&&Nc(d):this.N[a]=Wc;else{d=this.i||(this.i=this.N[this.l+this.j]={});var e=d[a];e?Array.isArray(e)&&
Nc(e):d[a]=Wc}}
var Wc=Object.freeze(Nc([]));function Xc(a,b,c){return-1===b?null:b>=a.l?a.i?a.i[b]:void 0:(void 0===c?0:c)&&a.i&&(c=a.i[b],null!=c)?c:a.N[b+a.j]}
function Yc(a,b,c){c=void 0===c?!1:c;var d=Xc(a,b,c);null==d&&(d=Wc);d===Wc&&(d=Nc(d.slice()),G(a,b,d,c));return d}
function G(a,b,c,d){b<a.l&&(void 0===d||!d)?a.N[b+a.j]=c:(a.i||(a.i=a.N[a.l+a.j]={}))[b]=c;return a}
function Zc(a,b,c,d){(c=$c(a,c))&&c!==b&&null!=d&&(a.h&&c in a.h&&(a.h[c]=void 0),G(a,c,void 0));return G(a,b,d)}
function $c(a,b){for(var c=0,d=0;d<b.length;d++){var e=b[d];null!=Xc(a,e)&&(0!==c&&G(a,c,void 0,!1),c=e)}return c}
function ad(a,b,c,d,e){if(-1===c)return null;a.h||(a.h={});var f=a.h[c];if(f)return f;e=Xc(a,c,void 0===e?!1:e);if(null==e&&!d)return f;b=new b(e);return a.h[c]=b}
function bd(a,b,c,d){a.h||(a.h={});var e=a.h[c];if(!e){d=Yc(a,c,void 0===d?!1:d);e=[];for(var f=0;f<d.length;f++)e[f]=new b(d[f]);a.h[c]=e}return e}
function H(a,b,c,d){a.h||(a.h={});var e=c?c.N:c;a.h[b]=c;return G(a,b,e,void 0===d?!1:d)}
function cd(a,b,c){var d=dd;a.h||(a.h={});var e=c?c.N:c;a.h[b]=c;Zc(a,b,d,e)}
function ed(a,b,c,d){var e=bd(a,c,b,void 0===e?!1:e);c=d?d:new c;a=Yc(a,b);e.push(c);a.push(c.N)}
F.prototype.toJSON=function(){var a=this.N;return Pc?a:Sc(a,Tc)};
function fd(a,b){return Qc(b)}
F.prototype.toString=function(){return this.N.toString()};
F.prototype.clone=function(){var a=this.constructor,b;Vc=b=Sc(this.N,Uc);a=new a(b);Vc=null;gd(a,this);return a};
function gd(a,b){b.o&&(a.o=b.o.slice());var c=b.h;if(c){b=b.i;for(var d in c){var e=c[d];if(e){var f=!(!b||!b[d]),g=+d;if(Array.isArray(e)){if(e.length)for(f=bd(a,e[0].constructor,g,f),g=0;g<Math.min(f.length,e.length);g++)gd(f[g],e[g])}else(f=ad(a,e.constructor,g,void 0,f))&&gd(f,e)}}}}
;function hd(a,b){var c=this.h;if(this.isRepeated){var d=!0;d=void 0===d?!1:d;if(b){var e=Nc([]);for(var f=0;f<b.length;f++)e[f]=b[f].N;a.h||(a.h={});a.h[c]=b}else a.h&&(a.h[c]=void 0),e=Wc;a=G(a,c,e,d)}else a=H(a,c,b,!0);return a}
;function id(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function jd(a){this.i=!1;var b=a.program;a=a.globalName;var c=new id;this.j=c.promise;this.l=r((0,y[a].a)(b,function(d,e){Promise.resolve().then(function(){c.resolve({Sb:d,Ac:e})})},!0)).next().value;
this.zc=c.promise.then(function(){})}
jd.prototype.snapshot=function(a){if(this.i)throw Error("Already disposed");return this.j.then(function(b){var c=b.Sb;return new Promise(function(d){c(function(e){d(e)},[a.ub,
a.Bc])})})};
jd.prototype.Nb=function(a){if(this.i)throw Error("Already disposed");return this.l([a.ub,a.Bc])};
jd.prototype.dispose=function(){this.i=!0;this.j.then(function(a){(a=a.Ac)&&a()})};
jd.prototype.h=function(){return this.i};var kd=window;Ab("csi.gstatic.com");Ab("googleads.g.doubleclick.net");Ab("partner.googleadservices.com");Ab("pubads.g.doubleclick.net");Ab("securepubads.g.doubleclick.net");Ab("tpc.googlesyndication.com");/*

 SPDX-License-Identifier: Apache-2.0
*/
var ld={};function md(){}
function nd(a){this.h=a}
u(nd,md);nd.prototype.toString=function(){return this.h};
var pd=new nd("about:invalid#zTSz",ld);function qd(a){if(a instanceof md)if(a instanceof nd)a=a.h;else throw Error("");else a=Rb(a);return a}
;function rd(a,b){a.src=Fb(b);var c;b=(a.ownerDocument&&a.ownerDocument.defaultView||window).document;var d=null===(c=b.querySelector)||void 0===c?void 0:c.call(b,"script[nonce]");(c=d?d.nonce||d.getAttribute("nonce")||"":"")&&a.setAttribute("nonce",c)}
;function sd(a,b){this.x=void 0!==a?a:0;this.y=void 0!==b?b:0}
n=sd.prototype;n.clone=function(){return new sd(this.x,this.y)};
n.equals=function(a){return a instanceof sd&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
n.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
n.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
n.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
n.scale=function(a,b){this.x*=a;this.y*="number"===typeof b?b:a;return this};function td(a,b){this.width=a;this.height=b}
n=td.prototype;n.clone=function(){return new td(this.width,this.height)};
n.aspectRatio=function(){return this.width/this.height};
n.isEmpty=function(){return!(this.width*this.height)};
n.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
n.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
n.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
n.scale=function(a,b){this.width*=a;this.height*="number"===typeof b?b:a;return this};function ud(a){var b=document;return"string"===typeof a?b.getElementById(a):a}
function vd(a,b){lb(b,function(c,d){c&&"object"==typeof c&&c.ja&&(c=c.ia());"style"==d?a.style.cssText=c:"class"==d?a.className=c:"for"==d?a.htmlFor=c:wd.hasOwnProperty(d)?a.setAttribute(wd[d],c):0==d.lastIndexOf("aria-",0)||0==d.lastIndexOf("data-",0)?a.setAttribute(d,c):a[d]=c})}
var wd={cellpadding:"cellPadding",cellspacing:"cellSpacing",colspan:"colSpan",frameborder:"frameBorder",height:"height",maxlength:"maxLength",nonce:"nonce",role:"role",rowspan:"rowSpan",type:"type",usemap:"useMap",valign:"vAlign",width:"width"};function xd(a,b,c){var d=arguments,e=document,f=d[1],g=yd(e,String(d[0]));f&&("string"===typeof f?g.className=f:Array.isArray(f)?g.className=f.join(" "):vd(g,f));2<d.length&&zd(e,g,d);return g}
function zd(a,b,c){function d(h){h&&b.appendChild("string"===typeof h?a.createTextNode(h):h)}
for(var e=2;e<c.length;e++){var f=c[e];if(!Ma(f)||Na(f)&&0<f.nodeType)d(f);else{a:{if(f&&"number"==typeof f.length){if(Na(f)){var g="function"==typeof f.item||"string"==typeof f.item;break a}if("function"===typeof f){g="function"==typeof f.item;break a}}g=!1}db(g?jb(f):f,d)}}}
function yd(a,b){b=String(b);"application/xhtml+xml"===a.contentType&&(b=b.toLowerCase());return a.createElement(b)}
function Ad(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;function Bd(a){var b=Cd;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a(b[c],c,b)}
function Dd(){var a=[];Bd(function(b){a.push(b)});
return a}
var Cd={Qc:"allow-forms",Rc:"allow-modals",Sc:"allow-orientation-lock",Tc:"allow-pointer-lock",Uc:"allow-popups",Vc:"allow-popups-to-escape-sandbox",Wc:"allow-presentation",Xc:"allow-same-origin",Yc:"allow-scripts",Zc:"allow-top-navigation",bd:"allow-top-navigation-by-user-activation"},Ed=ab(function(){return Dd()});
function Fd(){var a=Gd(),b={};db(Ed(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function Gd(){var a=void 0===a?document:a;return a.createElement("iframe")}
;function Hd(a){this.isValid=a}
function Id(a){return new Hd(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var Jd=[Id("data"),Id("http"),Id("https"),Id("mailto"),Id("ftp"),new Hd(function(a){return/^[^:]*([/?#]|$)/.test(a)})];function Kd(a){"number"==typeof a&&(a=Math.round(a)+"px");return a}
;var Ld=(new Date).getTime();var Md=new function(a,b){this.flag=a;this.defaultValue=void 0===b?!1:b}(1959);function Nd(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if("http"!==c&&"https"!==c&&"chrome-extension"!==c&&"moz-extension"!==c&&"file"!==c&&"android-app"!==
c&&"chrome-search"!==c&&"chrome-untrusted"!==c&&"chrome"!==c&&"app"!==c&&"devtools"!==c)throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===c&&"80"!==e||"https"===c&&"443"!==e)a=":"+e}return c+"://"+b+a}
;function Od(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;m=l=0}
function b(q){for(var w=g,t=0;64>t;t+=4)w[t/4]=q[t]<<24|q[t+1]<<16|q[t+2]<<8|q[t+3];for(t=16;80>t;t++)q=w[t-3]^w[t-8]^w[t-14]^w[t-16],w[t]=(q<<1|q>>>31)&4294967295;q=e[0];var z=e[1],B=e[2],I=e[3],L=e[4];for(t=0;80>t;t++){if(40>t)if(20>t){var N=I^z&(B^I);var R=1518500249}else N=z^B^I,R=1859775393;else 60>t?(N=z&B|I&(z|B),R=2400959708):(N=z^B^I,R=3395469782);N=((q<<5|q>>>27)&4294967295)+N+L+R+w[t]&4294967295;L=I;I=B;B=(z<<30|z>>>2)&4294967295;z=q;q=N}e[0]=e[0]+q&4294967295;e[1]=e[1]+z&4294967295;e[2]=
e[2]+B&4294967295;e[3]=e[3]+I&4294967295;e[4]=e[4]+L&4294967295}
function c(q,w){if("string"===typeof q){q=unescape(encodeURIComponent(q));for(var t=[],z=0,B=q.length;z<B;++z)t.push(q.charCodeAt(z));q=t}w||(w=q.length);t=0;if(0==l)for(;t+64<w;)b(q.slice(t,t+64)),t+=64,m+=64;for(;t<w;)if(f[l++]=q[t++],m++,64==l)for(l=0,b(f);t+64<w;)b(q.slice(t,t+64)),t+=64,m+=64}
function d(){var q=[],w=8*m;56>l?c(h,56-l):c(h,64-(l-56));for(var t=63;56<=t;t--)f[t]=w&255,w>>>=8;b(f);for(t=w=0;5>t;t++)for(var z=24;0<=z;z-=8)q[w++]=e[t]>>z&255;return q}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var l,m;a();return{reset:a,update:c,digest:d,Wb:function(){for(var q=d(),w="",t=0;t<q.length;t++)w+="0123456789ABCDEF".charAt(Math.floor(q[t]/16))+"0123456789ABCDEF".charAt(q[t]%16);return w}}}
;function Pd(a,b,c){var d=String(y.location.href);return d&&a&&b?[b,Qd(Nd(d),a,c||null)].join(" "):null}
function Qd(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],db(d,function(h){e.push(h)}),Rd(e.join(" "));
var f=[],g=[];db(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];db(d,function(h){e.push(h)});
a=Rd(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function Rd(a){var b=Od();b.update(a);return b.Wb().toLowerCase()}
;var Sd={};function Td(a){this.h=a||{cookie:""}}
n=Td.prototype;n.isEnabled=function(){if(!y.navigator.cookieEnabled)return!1;if(!this.isEmpty())return!0;this.set("TESTCOOKIESENABLED","1",{Sa:60});if("1"!==this.get("TESTCOOKIESENABLED"))return!1;this.remove("TESTCOOKIESENABLED");return!0};
n.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.Do;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.Sa}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString();this.h.cookie=a+"="+b+c+g+h+d+(null!=e?";samesite="+
e:"")};
n.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=Hb(d[e]);if(0==f.lastIndexOf(c,0))return f.substr(c.length);if(f==a)return""}return b};
n.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{Sa:0,path:b,domain:c});return d};
n.eb=function(){return Ud(this).keys};
n.isEmpty=function(){return!this.h.cookie};
n.clear=function(){for(var a=Ud(this).keys,b=a.length-1;0<=b;b--)this.remove(a[b])};
function Ud(a){a=(a.h.cookie||"").split(";");for(var b=[],c=[],d,e,f=0;f<a.length;f++)e=Hb(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));return{keys:b,values:c}}
var Vd=new Td("undefined"==typeof document?null:document);function Wd(a){return!!Sd.FPA_SAMESITE_PHASE2_MOD||!(void 0===a||!a)}
function Xd(a){a=void 0===a?!1:a;var b=y.__SAPISID||y.__APISID||y.__3PSAPISID||y.__OVERRIDE_SID;Wd(a)&&(b=b||y.__1PSAPISID);if(b)return!0;var c=new Td(document);b=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID")||c.get("SID");Wd(a)&&(b=b||c.get("__Secure-1PAPISID"));return!!b}
function Yd(a,b,c,d){(a=y[a])||(a=(new Td(document)).get(b));return a?Pd(a,c,d):null}
function Zd(a){var b=void 0===b?!1:b;var c=Nd(String(y.location.href)),d=[];if(Xd(b)){c=0==c.indexOf("https:")||0==c.indexOf("chrome-extension:")||0==c.indexOf("moz-extension:");var e=c?y.__SAPISID:y.__APISID;e||(e=new Td(document),e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID"));(e=e?Pd(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e);c&&Wd(b)&&((b=Yd("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=Yd("__3PSAPISID","__Secure-3PAPISID","SAPISID3PHASH",a))&&d.push(a))}return 0==
d.length?null:d.join(" ")}
;function $d(a){a&&"function"==typeof a.dispose&&a.dispose()}
;function ae(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Ma(d)?ae.apply(null,d):$d(d)}}
;function J(){this.D=this.D;this.o=this.o}
J.prototype.D=!1;J.prototype.h=function(){return this.D};
J.prototype.dispose=function(){this.D||(this.D=!0,this.H())};
function be(a,b){a.D?b():(a.o||(a.o=[]),a.o.push(b))}
J.prototype.H=function(){if(this.o)for(;this.o.length;)this.o.shift()()};function ce(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
ce.prototype.stopPropagation=function(){this.j=!0};
ce.prototype.preventDefault=function(){this.defaultPrevented=!0};function de(a){var b=C("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||y.$googDebugFname||b}catch(g){e="Not available",c=!0}b=ee(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,fe[c])c=fe[c];else{c=String(c);if(!fe[c]){var f=/function\s+([^\(]+)/m.exec(c);fe[c]=f?f[1]:"[Anonymous]"}c=fe[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return{message:a.message,name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:a.stack}}
function ee(a,b){b||(b={});b[ge(a)]=!0;var c=a.stack||"";(a=a.Tb)&&!b[ge(a)]&&(c+="\nCaused by: ",a.stack&&0==a.stack.indexOf(a.toString())||(c+="string"===typeof a?a:a.message+"\n"),c+=ee(a,b));return c}
function ge(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var fe={};var he=function(){if(!y.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{y.addEventListener("test",Ja,b),y.removeEventListener("test",Ja,b)}catch(c){}return a}();function ie(a,b){ce.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
Xa(ie,ce);var je={2:"touch",3:"pen",4:"mouse"};
ie.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;if(b=a.relatedTarget){if(tc){a:{try{pc(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:je[a.pointerType]||"";this.state=a.state;
this.i=a;a.defaultPrevented&&ie.Z.preventDefault.call(this)};
ie.prototype.stopPropagation=function(){ie.Z.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
ie.prototype.preventDefault=function(){ie.Z.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var ke="closure_listenable_"+(1E6*Math.random()|0);var le=0;function me(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.Pa=e;this.key=++le;this.Ca=this.La=!1}
function ne(a){a.Ca=!0;a.listener=null;a.proxy=null;a.src=null;a.Pa=null}
;function oe(a){this.src=a;this.listeners={};this.h=0}
oe.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=pe(a,b,d,e);-1<g?(b=a[g],c||(b.La=!1)):(b=new me(b,this.src,f,!!d,e),b.La=c,a.push(b));return b};
oe.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=pe(e,b,c,d);return-1<b?(ne(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.h--),!0):!1};
function qe(a,b){var c=b.type;c in a.listeners&&ib(a.listeners[c],b)&&(ne(b),0==a.listeners[c].length&&(delete a.listeners[c],a.h--))}
function pe(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.Ca&&f.listener==b&&f.capture==!!c&&f.Pa==d)return e}return-1}
;var re="closure_lm_"+(1E6*Math.random()|0),se={},te=0;function ue(a,b,c,d,e){if(d&&d.once)ve(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)ue(a,b[f],c,d,e);else c=we(c),a&&a[ke]?a.ba(b,c,Na(d)?!!d.capture:!!d,e):xe(a,b,c,!1,d,e)}
function xe(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Na(e)?!!e.capture:!!e,h=ye(a);h||(a[re]=h=new oe(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=ze();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)he||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(Ae(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");te++}}
function ze(){function a(c){return b.call(a.src,a.listener,c)}
var b=Be;return a}
function ve(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)ve(a,b[f],c,d,e);else c=we(c),a&&a[ke]?a.i.add(String(b),c,!0,Na(d)?!!d.capture:!!d,e):xe(a,b,c,!0,d,e)}
function Ce(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Ce(a,b[f],c,d,e);else(d=Na(d)?!!d.capture:!!d,c=we(c),a&&a[ke])?a.i.remove(String(b),c,d,e):a&&(a=ye(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=pe(b,c,d,e)),(c=-1<a?b[a]:null)&&De(c))}
function De(a){if("number"!==typeof a&&a&&!a.Ca){var b=a.src;if(b&&b[ke])qe(b.i,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(Ae(c),d):b.addListener&&b.removeListener&&b.removeListener(d);te--;(c=ye(b))?(qe(c,a),0==c.h&&(c.src=null,b[re]=null)):ne(a)}}}
function Ae(a){return a in se?se[a]:se[a]="on"+a}
function Be(a,b){if(a.Ca)a=!0;else{b=new ie(b,this);var c=a.listener,d=a.Pa||a.src;a.La&&De(a);a=c.call(d,b)}return a}
function ye(a){a=a[re];return a instanceof oe?a:null}
var Ee="__closure_events_fn_"+(1E9*Math.random()>>>0);function we(a){if("function"===typeof a)return a;a[Ee]||(a[Ee]=function(b){return a.handleEvent(b)});
return a[Ee]}
;function Fe(){J.call(this);this.i=new oe(this);this.Y=this;this.K=null}
Xa(Fe,J);Fe.prototype[ke]=!0;Fe.prototype.addEventListener=function(a,b,c,d){ue(this,a,b,c,d)};
Fe.prototype.removeEventListener=function(a,b,c,d){Ce(this,a,b,c,d)};
function Ge(a,b){var c=a.K;if(c){var d=[];for(var e=1;c;c=c.K)d.push(c),++e}a=a.Y;c=b.type||b;"string"===typeof b?b=new ce(b,a):b instanceof ce?b.target=b.target||a:(e=b,b=new ce(c,a),vb(b,e));e=!0;if(d)for(var f=d.length-1;!b.j&&0<=f;f--){var g=b.h=d[f];e=He(g,c,!0,b)&&e}b.j||(g=b.h=a,e=He(g,c,!0,b)&&e,b.j||(e=He(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=He(g,c,!1,b)&&e}
Fe.prototype.H=function(){Fe.Z.H.call(this);if(this.i){var a=this.i,b=0,c;for(c in a.listeners){for(var d=a.listeners[c],e=0;e<d.length;e++)++b,ne(d[e]);delete a.listeners[c];a.h--}}this.K=null};
Fe.prototype.ba=function(a,b,c,d){return this.i.add(String(a),b,!1,c,d)};
function He(a,b,c,d){b=a.i.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.Ca&&g.capture==c){var h=g.listener,k=g.Pa||g.src;g.La&&qe(a.i,g);e=!1!==h.call(k,d)&&e}}return e&&!d.defaultPrevented}
;function Ie(a){var b,c;Fe.call(this);var d=this;this.A=this.l=0;this.V=null!==a&&void 0!==a?a:{M:function(e,f){return setTimeout(e,f)},
U:clearTimeout};this.j=null!==(c=null===(b=window.navigator)||void 0===b?void 0:b.onLine)&&void 0!==c?c:!0;this.m=function(){return x(function(e){return v(e,Je(d),0)})};
window.addEventListener("offline",this.m);window.addEventListener("online",this.m);this.A||Ke(this)}
u(Ie,Fe);Ie.prototype.dispose=function(){window.removeEventListener("offline",this.m);window.removeEventListener("online",this.m);this.V.U(this.A);delete Ie.h};
Ie.prototype.G=function(){return this.j};
function Ke(a){a.A=a.V.M(function(){var b;return x(function(c){if(1==c.h)return a.j?(null===(b=window.navigator)||void 0===b?0:b.onLine)?c.s(3):v(c,Je(a),3):v(c,Je(a),3);Ke(a);c.h=0})},3E4)}
function Je(a,b){return a.u?a.u:a.u=new Promise(function(c){var d,e,f;return x(function(g){switch(g.h){case 1:return d=window.AbortController?new window.AbortController:void 0,e=null===d||void 0===d?void 0:d.signal,f=!1,ta(g,2,3),d&&(a.l=a.V.M(function(){d.abort()},b||2E4)),v(g,fetch("/generate_204",{method:"HEAD",
signal:e}),5);case 5:f=!0;case 3:wa(g);a.u=void 0;a.l&&(a.V.U(a.l),a.l=0);f!==a.j&&(a.j=f,a.j?Ge(a,"networkstatus-online"):Ge(a,"networkstatus-offline"));c(f);xa(g);break;case 2:va(g),f=!1,g.s(3)}})})}
;var Le={Vn:"WEB_DISPLAY_MODE_UNKNOWN",Rn:"WEB_DISPLAY_MODE_BROWSER",Tn:"WEB_DISPLAY_MODE_MINIMAL_UI",Un:"WEB_DISPLAY_MODE_STANDALONE",Sn:"WEB_DISPLAY_MODE_FULLSCREEN"};function Me(){this.data_=[];this.h=-1}
Me.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&0===a%1&&this.data_[a]!=b&&(this.data_[a]=b,this.h=-1)};
Me.prototype.get=function(a){return!!this.data_[a]};
function Ne(a){-1==a.h&&(a.h=gb(a.data_,function(b,c,d){return c?b+Math.pow(2,d):b},0));
return a.h}
;function Oe(){var a={};this.C=function(b,c){return null!=a[b]?a[b]:c}}
;function Pe(a,b){this.j=a;this.l=b;this.i=0;this.h=null}
Pe.prototype.get=function(){if(0<this.i){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function Qe(a,b){a.l(b);100>a.i&&(a.i++,b.next=a.h,a.h=b)}
;var Re;
function Se(){var a=y.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!E("Presto")&&(a=function(){var e=yd(document,"IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=Ta(function(k){if(("*"==h||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!E("Trident")&&!E("MSIE")){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.sb;c.sb=null;e()}};
return function(e){d.next={sb:e};d=d.next;b.port2.postMessage(0)}}return function(e){y.setTimeout(e,0)}}
;function Te(a){y.setTimeout(function(){throw a;},0)}
;function Ue(){this.i=this.h=null}
Ue.prototype.add=function(a,b){var c=Ve.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
Ue.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var Ve=new Pe(function(){return new We},function(a){return a.reset()});
function We(){this.next=this.scope=this.h=null}
We.prototype.set=function(a,b){this.h=a;this.scope=b;this.next=null};
We.prototype.reset=function(){this.next=this.scope=this.h=null};function Xe(a,b){Ye||Ze();$e||(Ye(),$e=!0);af.add(a,b)}
var Ye;function Ze(){if(y.Promise&&y.Promise.resolve){var a=y.Promise.resolve(void 0);Ye=function(){a.then(bf)}}else Ye=function(){var b=bf;
"function"!==typeof y.setImmediate||y.Window&&y.Window.prototype&&!E("Edge")&&y.Window.prototype.setImmediate==y.setImmediate?(Re||(Re=Se()),Re(b)):y.setImmediate(b)}}
var $e=!1,af=new Ue;function bf(){for(var a;a=af.remove();){try{a.h.call(a.scope)}catch(b){Te(b)}Qe(Ve,a)}$e=!1}
;function cf(a,b){this.h=a[y.Symbol.iterator]();this.i=b;this.j=0}
cf.prototype[Symbol.iterator]=function(){return this};
cf.prototype.next=function(){var a=this.h.next();return{value:a.done?void 0:this.i.call(void 0,a.value,this.j++),done:a.done}};
function df(a,b){return new cf(a,b)}
;function ef(){this.blockSize=-1}
;function ff(){this.blockSize=-1;this.blockSize=64;this.h=[];this.o=[];this.m=[];this.j=[];this.j[0]=128;for(var a=1;a<this.blockSize;++a)this.j[a]=0;this.l=this.i=0;this.reset()}
Xa(ff,ef);ff.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.l=this.i=0};
function gf(a,b,c){c||(c=0);var d=a.m;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.h[0];c=a.h[1];var g=a.h[2],h=a.h[3],k=a.h[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var l=1518500249}else f=c^g^h,l=1859775393;else 60>e?(f=c&g|h&(c|g),l=2400959708):
(f=c^g^h,l=3395469782);f=(b<<5|b>>>27)+f+k+l+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+g&4294967295;a.h[3]=a.h[3]+h&4294967295;a.h[4]=a.h[4]+k&4294967295}
ff.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.o,f=this.i;d<b;){if(0==f)for(;d<=c;)gf(this,a,d),d+=this.blockSize;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){gf(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){gf(this,e);f=0;break}}this.i=f;this.l+=b}};
ff.prototype.digest=function(){var a=[],b=8*this.l;56>this.i?this.update(this.j,56-this.i):this.update(this.j,this.blockSize-(this.i-56));for(var c=this.blockSize-1;56<=c;c--)this.o[c]=b&255,b/=256;gf(this,this.o);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function hf(a){return"string"==typeof a.className?a.className:a.getAttribute&&a.getAttribute("class")||""}
function jf(a,b){"string"==typeof a.className?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function kf(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:hf(a).match(/\S+/g)||[],b=0<=cb(a,b));return b}
function lf(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):kf(a,"inverted-hdpi")&&jf(a,Array.prototype.filter.call(a.classList?a.classList:hf(a).match(/\S+/g)||[],function(b){return"inverted-hdpi"!=b}).join(" "))}
;var mf="StopIteration"in y?y.StopIteration:{message:"StopIteration",stack:""};function nf(){}
nf.prototype.da=function(){throw mf;};
nf.prototype.next=function(){return of};
var of={done:!0,value:void 0};function pf(a){return{value:a,done:!1}}
function qf(a){if(a.done)throw mf;return a.value}
nf.prototype.T=function(){return this};function rf(a){if(a instanceof sf||a instanceof tf||a instanceof uf)return a;if("function"==typeof a.da)return new sf(function(){return vf(a)});
if("function"==typeof a[Symbol.iterator])return new sf(function(){return a[Symbol.iterator]()});
if("function"==typeof a.T)return new sf(function(){return vf(a.T())});
throw Error("Not an iterator or iterable.");}
function vf(a){if(!(a instanceof nf))return a;var b=!1;return{next:function(){for(var c;!b;)try{c=a.da();break}catch(d){if(d!==mf)throw d;b=!0}return{value:c,done:b}}}}
function sf(a){this.h=a}
sf.prototype.T=function(){return new tf(this.h())};
sf.prototype[Symbol.iterator]=function(){return new uf(this.h())};
sf.prototype.i=function(){return new uf(this.h())};
function tf(a){this.h=a}
u(tf,nf);tf.prototype.da=function(){var a=this.h.next();if(a.done)throw mf;return a.value};
tf.prototype.next=function(){return this.h.next()};
tf.prototype[Symbol.iterator]=function(){return new uf(this.h)};
tf.prototype.i=function(){return new uf(this.h)};
function uf(a){sf.call(this,function(){return a});
this.j=a}
u(uf,sf);uf.prototype.next=function(){return this.j.next()};function wf(a,b){this.i={};this.h=[];this.la=this.size=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof wf)for(c=a.eb(),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
n=wf.prototype;n.eb=function(){xf(this);return this.h.concat()};
n.has=function(a){return yf(this.i,a)};
n.equals=function(a,b){if(this===a)return!0;if(this.size!=a.size)return!1;b=b||zf;xf(this);for(var c,d=0;c=this.h[d];d++)if(!b(this.get(c),a.get(c)))return!1;return!0};
function zf(a,b){return a===b}
n.isEmpty=function(){return 0==this.size};
n.clear=function(){this.i={};this.la=this.size=this.h.length=0};
n.remove=function(a){return this.delete(a)};
n.delete=function(a){return yf(this.i,a)?(delete this.i[a],--this.size,this.la++,this.h.length>2*this.size&&xf(this),!0):!1};
function xf(a){if(a.size!=a.h.length){for(var b=0,c=0;b<a.h.length;){var d=a.h[b];yf(a.i,d)&&(a.h[c++]=d);b++}a.h.length=c}if(a.size!=a.h.length){var e={};for(c=b=0;b<a.h.length;)d=a.h[b],yf(e,d)||(a.h[c++]=d,e[d]=1),b++;a.h.length=c}}
n.get=function(a,b){return yf(this.i,a)?this.i[a]:b};
n.set=function(a,b){yf(this.i,a)||(this.size+=1,this.h.push(a),this.la++);this.i[a]=b};
n.forEach=function(a,b){for(var c=this.eb(),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
n.clone=function(){return new wf(this)};
n.keys=function(){return rf(this.T(!0)).i()};
n.values=function(){return rf(this.T(!1)).i()};
n.entries=function(){var a=this;return df(this.keys(),function(b){return[b,a.get(b)]})};
n.T=function(a){xf(this);var b=0,c=this.la,d=this,e=new nf;e.next=function(){if(c!=d.la)throw Error("The map has changed since the iterator was created");if(b>=d.h.length)return of;var g=d.h[b++];return pf(a?g:d.i[g])};
var f=e.next;e.da=function(){return qf(f.call(e))};
return e};
function yf(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
;function Af(a){Bf();return Gb(a)}
var Bf=Ja;function Cf(a){var b=[];Df(new Ef,a,b);return b.join("")}
function Ef(){}
function Df(a,b,c){if(null==b)c.push("null");else{if("object"==typeof b){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),Df(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],"function"!=typeof f&&(c.push(e),Ff(d,c),c.push(":"),Df(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":Ff(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var Gf={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\x0B":"\\u000b"},Hf=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function Ff(a,b){b.push('"',a.replace(Hf,function(c){var d=Gf[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).substr(1),Gf[c]=d);return d}),'"')}
;function If(a){if(!a)return!1;try{return!!a.$goog_Thenable}catch(b){return!1}}
;function Jf(a){this.h=0;this.D=void 0;this.l=this.i=this.j=null;this.o=this.m=!1;if(a!=Ja)try{var b=this;a.call(void 0,function(c){Kf(b,2,c)},function(c){Kf(b,3,c)})}catch(c){Kf(this,3,c)}}
function Lf(){this.next=this.context=this.onRejected=this.i=this.h=null;this.j=!1}
Lf.prototype.reset=function(){this.context=this.onRejected=this.i=this.h=null;this.j=!1};
var Mf=new Pe(function(){return new Lf},function(a){a.reset()});
function Nf(a,b,c){var d=Mf.get();d.i=a;d.onRejected=b;d.context=c;return d}
function Of(a){return new Jf(function(b,c){c(a)})}
Jf.prototype.then=function(a,b,c){return Pf(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
Jf.prototype.$goog_Thenable=!0;function Qf(a,b){return Pf(a,null,b,void 0)}
Jf.prototype.cancel=function(a){if(0==this.h){var b=new Rf(a);Xe(function(){Sf(this,b)},this)}};
function Sf(a,b){if(0==a.h)if(a.j){var c=a.j;if(c.i){for(var d=0,e=null,f=null,g=c.i;g&&(g.j||(d++,g.h==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.h&&1==d?Sf(c,b):(f?(d=f,d.next==c.l&&(c.l=d),d.next=d.next.next):Tf(c),Uf(c,e,3,b)))}a.j=null}else Kf(a,3,b)}
function Vf(a,b){a.i||2!=a.h&&3!=a.h||Wf(a);a.l?a.l.next=b:a.i=b;a.l=b}
function Pf(a,b,c,d){var e=Nf(null,null,null);e.h=new Jf(function(f,g){e.i=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.onRejected=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof Rf?g(h):f(k)}catch(l){g(l)}}:g});
e.h.j=a;Vf(a,e);return e.h}
Jf.prototype.A=function(a){this.h=0;Kf(this,2,a)};
Jf.prototype.K=function(a){this.h=0;Kf(this,3,a)};
function Kf(a,b,c){if(0==a.h){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.h=1;a:{var d=c,e=a.A,f=a.K;if(d instanceof Jf){Vf(d,Nf(e||Ja,f||null,a));var g=!0}else if(If(d))d.then(e,f,a),g=!0;else{if(Na(d))try{var h=d.then;if("function"===typeof h){Xf(d,h,e,f,a);g=!0;break a}}catch(k){f.call(a,k);g=!0;break a}g=!1}}g||(a.D=c,a.h=b,a.j=null,Wf(a),3!=b||c instanceof Rf||Yf(a,c))}}
function Xf(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function Wf(a){a.m||(a.m=!0,Xe(a.u,a))}
function Tf(a){var b=null;a.i&&(b=a.i,a.i=b.next,b.next=null);a.i||(a.l=null);return b}
Jf.prototype.u=function(){for(var a;a=Tf(this);)Uf(this,a,this.h,this.D);this.m=!1};
function Uf(a,b,c,d){if(3==c&&b.onRejected&&!b.j)for(;a&&a.o;a=a.j)a.o=!1;if(b.h)b.h.j=null,Zf(b,c,d);else try{b.j?b.i.call(b.context):Zf(b,c,d)}catch(e){$f.call(null,e)}Qe(Mf,b)}
function Zf(a,b,c){2==b?a.i.call(a.context,c):a.onRejected&&a.onRejected.call(a.context,c)}
function Yf(a,b){a.o=!0;Xe(function(){a.o&&$f.call(null,b)})}
var $f=Te;function Rf(a){Za.call(this,a)}
Xa(Rf,Za);Rf.prototype.name="cancel";function K(a){J.call(this);this.u=1;this.l=[];this.m=0;this.i=[];this.j={};this.A=!!a}
Xa(K,J);n=K.prototype;n.subscribe=function(a,b,c){var d=this.j[a];d||(d=this.j[a]=[]);var e=this.u;this.i[e]=a;this.i[e+1]=b;this.i[e+2]=c;this.u=e+3;d.push(e);return e};
function ag(a,b,c,d){if(b=a.j[b]){var e=a.i;(b=b.find(function(f){return e[f+1]==c&&e[f+2]==d}))&&a.ya(b)}}
n.ya=function(a){var b=this.i[a];if(b){var c=this.j[b];0!=this.m?(this.l.push(a),this.i[a+1]=Ja):(c&&ib(c,a),delete this.i[a],delete this.i[a+1],delete this.i[a+2])}return!!b};
n.ma=function(a,b){var c=this.j[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.A)for(e=0;e<c.length;e++){var g=c[e];bg(this.i[g+1],this.i[g+2],d)}else{this.m++;try{for(e=0,f=c.length;e<f&&!this.h();e++)g=c[e],this.i[g+1].apply(this.i[g+2],d)}finally{if(this.m--,0<this.l.length&&0==this.m)for(;c=this.l.pop();)this.ya(c)}}return 0!=e}return!1};
function bg(a,b,c){Xe(function(){a.apply(b,c)})}
n.clear=function(a){if(a){var b=this.j[a];b&&(b.forEach(this.ya,this),delete this.j[a])}else this.i.length=0,this.j={}};
n.H=function(){K.Z.H.call(this);this.clear();this.l.length=0};function cg(a){this.h=a}
cg.prototype.set=function(a,b){void 0===b?this.h.remove(a):this.h.set(a,Cf(b))};
cg.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
cg.prototype.remove=function(a){this.h.remove(a)};function dg(a){this.h=a}
Xa(dg,cg);function eg(a){this.data=a}
function fg(a){return void 0===a||a instanceof eg?a:new eg(a)}
dg.prototype.set=function(a,b){dg.Z.set.call(this,a,fg(b))};
dg.prototype.i=function(a){a=dg.Z.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
dg.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function gg(a){this.h=a}
Xa(gg,dg);gg.prototype.set=function(a,b,c){if(b=fg(b)){if(c){if(c<Date.now()){gg.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Date.now()}gg.Z.set.call(this,a,b)};
gg.prototype.i=function(a){var b=gg.Z.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Date.now()||c&&c>Date.now())gg.prototype.remove.call(this,a);else return b}};function hg(){}
;function ig(){}
Xa(ig,hg);ig.prototype[Symbol.iterator]=function(){return rf(this.T(!0)).i()};
ig.prototype.clear=function(){var a=Array.from(this);a=r(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function jg(a){this.h=a}
Xa(jg,ig);n=jg.prototype;n.isAvailable=function(){if(!this.h)return!1;try{return this.h.setItem("__sak","1"),this.h.removeItem("__sak"),!0}catch(a){return!1}};
n.set=function(a,b){try{this.h.setItem(a,b)}catch(c){if(0==this.h.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
n.get=function(a){a=this.h.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
n.remove=function(a){this.h.removeItem(a)};
n.T=function(a){var b=0,c=this.h,d=new nf;d.next=function(){if(b>=c.length)return of;var f=c.key(b++);if(a)return pf(f);f=c.getItem(f);if("string"!==typeof f)throw"Storage mechanism: Invalid value was encountered";return pf(f)};
var e=d.next;d.da=function(){return qf(e.call(d))};
return d};
n.clear=function(){this.h.clear()};
n.key=function(a){return this.h.key(a)};function kg(){var a=null;try{a=window.localStorage||null}catch(b){}this.h=a}
Xa(kg,jg);function lg(a,b){this.i=a;this.h=null;var c;if(c=rc)c=!(9<=Number(Ec));if(c){mg||(mg=new wf);this.h=mg.get(a);this.h||(b?this.h=document.getElementById(b):(this.h=document.createElement("userdata"),this.h.addBehavior("#default#userData"),document.body.appendChild(this.h)),mg.set(a,this.h));try{this.h.load(this.i)}catch(d){this.h=null}}}
Xa(lg,ig);var ng={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},mg=null;function og(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return ng[b]})}
n=lg.prototype;n.isAvailable=function(){return!!this.h};
n.set=function(a,b){this.h.setAttribute(og(a),b);pg(this)};
n.get=function(a){a=this.h.getAttribute(og(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
n.remove=function(a){this.h.removeAttribute(og(a));pg(this)};
n.T=function(a){var b=0,c=this.h.XMLDocument.documentElement.attributes,d=new nf;d.next=function(){if(b>=c.length)return of;var f=c[b++];if(a)return pf(decodeURIComponent(f.nodeName.replace(/\./g,"%")).substr(1));f=f.nodeValue;if("string"!==typeof f)throw"Storage mechanism: Invalid value was encountered";return pf(f)};
var e=d.next;d.da=function(){return qf(e.call(d))};
return d};
n.clear=function(){for(var a=this.h.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);pg(this)};
function pg(a){try{a.h.save(a.i)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function qg(a,b){this.i=a;this.h=b+"::"}
Xa(qg,ig);qg.prototype.set=function(a,b){this.i.set(this.h+a,b)};
qg.prototype.get=function(a){return this.i.get(this.h+a)};
qg.prototype.remove=function(a){this.i.remove(this.h+a)};
qg.prototype.T=function(a){var b=this.i.T(!0),c=this,d=new nf;d.next=function(){try{var f=b.da()}catch(g){if(g===mf)return of;throw g;}for(;f.substr(0,c.h.length)!=c.h;)try{f=b.da()}catch(g){if(g===mf)return of;throw g;}return pf(a?f.substr(c.h.length):c.i.get(f))};
var e=d.next;d.da=function(){return qf(e.call(d))};
return d};function rg(a){F.call(this,a)}
u(rg,F);rg.prototype.getKey=function(){return Xc(this,1)};
rg.prototype.getValue=function(){return Xc(this,2===$c(this,sg)?2:-1)};
rg.prototype.setValue=function(a){return Zc(this,2,sg,a)};
var sg=[2,3,4,5,6];function tg(a){F.call(this,a)}
u(tg,F);function ug(a){F.call(this,a)}
u(ug,F);function vg(a){F.call(this,a)}
u(vg,F);function wg(a){F.call(this,a,-1,xg)}
u(wg,F);wg.prototype.getPlayerType=function(){return Xc(this,36)};
wg.prototype.setHomeGroupInfo=function(a){return H(this,81,a)};
var xg=[9,66,24,32,86,100,101];function yg(a){F.call(this,a,-1,zg)}
u(yg,F);var zg=[15,26,28];function Ag(a){F.call(this,a)}
u(Ag,F);Ag.prototype.setToken=function(a){return G(this,2,a)};function Bg(a){F.call(this,a,-1,Cg)}
u(Bg,F);Bg.prototype.setSafetyMode=function(a){return G(this,5,a)};
var Cg=[12];function Dg(a){F.call(this,a,-1,Eg)}
u(Dg,F);var Eg=[12];function Fg(a){F.call(this,a)}
u(Fg,F);var Gg={sh:0,dh:1,jh:2,kh:4,ph:8,lh:16,mh:32,rh:64,qh:128,fh:256,hh:512,oh:1024,gh:2048,ih:4096,eh:8192,nh:16384};function Hg(a){F.call(this,a)}
u(Hg,F);function Ig(a,b){H(a,1,b)}
Hg.prototype.X=function(a){G(this,2,a)};
function Jg(a){F.call(this,a)}
u(Jg,F);function Kg(a,b){H(a,1,b)}
;function Lg(a){F.call(this,a,-1,Mg)}
u(Lg,F);Lg.prototype.X=function(a){G(this,1,a)};
function Ng(a,b){H(a,2,b)}
var Mg=[3];function Og(a){F.call(this,a)}
u(Og,F);Og.prototype.X=function(a){G(this,1,a)};function Pg(a){F.call(this,a)}
u(Pg,F);Pg.prototype.X=function(a){G(this,1,a)};function Qg(a){F.call(this,a)}
u(Qg,F);Qg.prototype.X=function(a){G(this,1,a)};function Rg(a){F.call(this,a)}
u(Rg,F);function Sg(a){F.call(this,a)}
u(Sg,F);function Tg(a){F.call(this,a)}
u(Tg,F);function Ug(a){F.call(this,a)}
u(Ug,F);function Vg(a){F.call(this,a)}
u(Vg,F);
var dd=[23,24,11,6,7,5,2,3,20,21,28,32,37,229,241,45,59,225,288,72,73,78,208,156,202,215,74,76,79,80,111,85,91,97,100,102,105,119,126,127,136,146,157,158,159,163,164,168,176,222,383,177,178,179,411,184,188,189,190,191,193,194,195,196,198,199,200,201,203,204,205,206,258,259,260,261,209,226,227,232,233,234,240,247,248,251,254,255,270,278,291,293,300,304,308,309,310,311,313,314,319,321,323,324,328,330,331,332,337,338,340,344,348,350,351,352,353,354,355,356,357,358,361,363,364,368,369,370,373,374,375,
378,380,381,388,389,403,412,413,414,415,416,417,418,419,420,117];function Wg(a){F.call(this,a)}
u(Wg,F);function Xg(a){F.call(this,a)}
u(Xg,F);Xg.prototype.setVideoId=function(a){return Zc(this,1,Yg,a)};
Xg.prototype.getPlaylistId=function(){return Xc(this,2===$c(this,Yg)?2:-1)};
var Yg=[1,2];function Zg(a){F.call(this,a,-1,$g)}
u(Zg,F);var $g=[3];function ah(a){F.call(this,a,1)}
u(ah,F);function bh(a){F.call(this,a)}
u(bh,F);var ch;ch=new function(a,b,c,d){this.h=a;this.fieldName=b;this.isRepeated=d;this.i=hd}(406606992,{so:0},bh,0);function dh(){bh.apply(this,arguments)}
u(dh,bh);function eh(a,b){1<b.length?a[b[0]]=b[1]:1===b.length&&Object.assign(a,b[0])}
;var fh,gh,hh,ih=y.window,jh=(null===(fh=null===ih||void 0===ih?void 0:ih.yt)||void 0===fh?void 0:fh.config_)||(null===(gh=null===ih||void 0===ih?void 0:ih.ytcfg)||void 0===gh?void 0:gh.data_)||{},kh=(null===(hh=null===ih||void 0===ih?void 0:ih.ytcfg)||void 0===hh?void 0:hh.obfuscatedData_)||[];function lh(){ah.apply(this,arguments)}
u(lh,ah);var mh=new lh(kh),nh=jh.EXPERIMENT_FLAGS;if(!nh||!nh.jspb_i18n_extension){var oh=new dh;ch.i(mh,oh)}A("yt.config_",jh,void 0);A("yt.configJspb_",kh,void 0);function ph(){eh(jh,arguments)}
function D(a,b){return a in jh?jh[a]:b}
;function M(a){a=qh(a);return"string"===typeof a&&"false"===a?!1:!!a}
function rh(a,b){a=qh(a);return void 0===a&&void 0!==b?b:Number(a||0)}
function sh(){return D("EXPERIMENTS_TOKEN","")}
function qh(a){var b=D("EXPERIMENTS_FORCED_FLAGS",{});return void 0!==b[a]?b[a]:D("EXPERIMENT_FLAGS",{})[a]}
function th(){var a=[],b=D("EXPERIMENTS_FORCED_FLAGS",{});for(c in b)a.push({key:c,value:String(b[c])});var c=D("EXPERIMENT_FLAGS",{});for(var d in c)d.startsWith("force_")&&void 0===b[d]&&a.push({key:d,value:String(c[d])});return a}
;var uh={appSettingsCaptured:!0,visualElementAttached:!0,visualElementGestured:!0,visualElementHidden:!0,visualElementShown:!0,flowEvent:!0,visualElementStateChanged:!0,playbackAssociated:!0,youThere:!0,accountStateChangeSignedIn:!0,accountStateChangeSignedOut:!0},vh={latencyActionBaselined:!0,latencyActionInfo:!0,latencyActionTicked:!0,bedrockRepetitiveActionTimed:!0,adsClientStateChange:!0,streamzIncremented:!0,mdxDialAdditionalDataUpdateEvent:!0,tvhtml5WatchKeyEvent:!0,tvhtml5VideoSeek:!0,tokenRefreshEvent:!0,
adNotify:!0,adNotifyFilled:!0,tvhtml5LaunchUrlComponentChanged:!0,bedrockResourceConsumptionSnapshot:!0,deviceStartupMetrics:!0,mdxSignIn:!0,tvhtml5KeyboardLogging:!0,tvhtml5StartupSoundEvent:!0,tvhtml5LiveChatStatus:!0,tvhtml5DeviceStorageStatus:!0,tvhtml5LocalStorage:!0,directSignInEvent:!0,finalPayload:!0,tvhtml5SearchCompleted:!0,tvhtml5KeyboardPerformance:!0,adNotifyFailure:!0,latencyActionSpan:!0,tvhtml5AccountDialogOpened:!0,tvhtml5ApiTest:!0};var wh=0,xh=uc?"webkit":tc?"moz":rc?"ms":qc?"o":"";A("ytDomDomGetNextId",C("ytDomDomGetNextId")||function(){return++wh},void 0);var yh=[];function zh(a){yh.forEach(function(b){return b(a)})}
function Ah(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){Bh(b)}}:a}
function Bh(a,b,c,d){var e=C("yt.logging.errors.log");e?e(a,"ERROR",b,c,d):(e=D("ERRORS",[]),e.push([a,"ERROR",b,c,d]),ph("ERRORS",e));zh(a)}
function Ch(a,b,c,d){var e=C("yt.logging.errors.log");e?e(a,"WARNING",b,c,d):(e=D("ERRORS",[]),e.push([a,"WARNING",b,c,d]),ph("ERRORS",e))}
;var Dh={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function Eh(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in Dh||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.h=a.pageX;this.i=a.pageY}}catch(e){}}
function Fh(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.h=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.i=a.clientY+b}}
Eh.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
Eh.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
Eh.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var nb=y.ytEventsEventsListeners||{};A("ytEventsEventsListeners",nb,void 0);var Gh=y.ytEventsEventsCounter||{count:0};A("ytEventsEventsCounter",Gh,void 0);
function Hh(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return mb(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=Na(e[4])&&Na(d)&&rb(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
var Ih=ab(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function Jh(a,b,c,d){d=void 0===d?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=Hh(a,b,c,d);if(e)return e;e=++Gh.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new Eh(h);if(!Ad(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new Eh(h);
h.currentTarget=a;return c.call(a,h)};
g=Ah(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),Ih()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);nb[e]=[a,b,c,g,d];return e}
function Kh(a){a&&("string"==typeof a&&(a=[a]),db(a,function(b){if(b in nb){var c=nb[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?Ih()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete nb[b]}}))}
;var Lh=window.ytcsi&&window.ytcsi.now?window.ytcsi.now:window.performance&&window.performance.timing&&window.performance.now&&window.performance.timing.navigationStart?function(){return window.performance.timing.navigationStart+window.performance.now()}:function(){return(new Date).getTime()};function Mh(a,b){"function"===typeof a&&(a=Ah(a));return window.setTimeout(a,b)}
function Nh(a){window.clearTimeout(a)}
;function Oh(a){this.K=a;this.i=null;this.m=0;this.A=null;this.u=0;this.j=[];for(a=0;4>a;a++)this.j.push(0);this.l=0;this.S=Jh(window,"mousemove",Ta(this.Y,this));a=Ta(this.L,this);"function"===typeof a&&(a=Ah(a));this.ga=window.setInterval(a,25)}
Xa(Oh,J);Oh.prototype.Y=function(a){void 0===a.h&&Fh(a);var b=a.h;void 0===a.i&&Fh(a);this.i=new sd(b,a.i)};
Oh.prototype.L=function(){if(this.i){var a=Lh();if(0!=this.m){var b=this.A,c=this.i,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.m);this.j[this.l]=.5<Math.abs((d-this.u)/this.u)?1:0;for(c=b=0;4>c;c++)b+=this.j[c]||0;3<=b&&this.K();this.u=d}this.m=a;this.A=this.i;this.l=(this.l+1)%4}};
Oh.prototype.H=function(){window.clearInterval(this.ga);Kh(this.S)};function Ph(){}
function Qh(a,b){return Rh(a,0,b)}
Ph.prototype.M=function(a,b){return Rh(a,1,b)};
function Sh(a,b){Rh(a,2,b)}
function Th(a){var b=C("yt.scheduler.instance.addImmediateJob");b?b(a):a()}
;function Uh(){Ph.apply(this,arguments)}
u(Uh,Ph);function Vh(){Uh.h||(Uh.h=new Uh);return Uh.h}
function Rh(a,b,c){void 0!==c&&Number.isNaN(Number(c))&&(c=void 0);var d=C("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):Mh(a,c||0)}
Uh.prototype.U=function(a){if(void 0===a||!Number.isNaN(Number(a))){var b=C("yt.scheduler.instance.cancelJob");b?b(a):Nh(a)}};
Uh.prototype.start=function(){var a=C("yt.scheduler.instance.start");a&&a()};
Uh.prototype.pause=function(){var a=C("yt.scheduler.instance.pause");a&&a()};var Wh=Vh();var Xh={};
function Yh(a){var b=void 0===a?{}:a;a=void 0===b.kc?!1:b.kc;b=void 0===b.Yb?!0:b.Yb;if(null==C("_lact",window)){var c=parseInt(D("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;A("_lact",c,window);A("_fact",c,window);-1==c&&Zh();Jh(document,"keydown",Zh);Jh(document,"keyup",Zh);Jh(document,"mousedown",Zh);Jh(document,"mouseup",Zh);a?Jh(window,"touchmove",function(){$h("touchmove",200)},{passive:!0}):(Jh(window,"resize",function(){$h("resize",200)}),b&&Jh(window,"scroll",function(){$h("scroll",200)}));
new Oh(function(){$h("mouse",100)});
Jh(document,"touchstart",Zh,{passive:!0});Jh(document,"touchend",Zh,{passive:!0})}}
function $h(a,b){Xh[a]||(Xh[a]=!0,Wh.M(function(){Zh();Xh[a]=!1},b))}
function Zh(){null==C("_lact",window)&&Yh();var a=Date.now();A("_lact",a,window);-1==C("_fact",window)&&A("_fact",a,window);(a=C("ytglobal.ytUtilActivityCallback_"))&&a()}
function ai(){var a=C("_lact",window);return null==a?-1:Math.max(Date.now()-a,0)}
;function bi(){var a=ci;C("yt.ads.biscotti.getId_")||A("yt.ads.biscotti.getId_",a,void 0)}
function di(a){A("yt.ads.biscotti.lastId_",a,void 0)}
;var ei=/^[\w.]*$/,fi={q:!0,search_query:!0};function gi(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=hi(f[0]||""),h=hi(f[1]||"");g in c?Array.isArray(c[g])?kb(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(q){var k=q,l=f[0],m=String(gi);k.args=[{key:l,value:f[1],query:a,method:ii==m?"unchanged":m}];fi.hasOwnProperty(l)||Ch(k)}}return c}
var ii=String(gi);function ji(a){var b=[];lb(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];db(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function ki(a){"?"==a.charAt(0)&&(a=a.substr(1));return gi(a,"&")}
function li(a){return-1!=a.indexOf("?")?(a=(a||"").split("#")[0],a=a.split("?",2),ki(1<a.length?a[1]:a[0])):{}}
function mi(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=ki(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);return mc(a,e)+d}
function ni(a){if(!b)var b=window.location.href;var c=a.match(gc)[1]||null,d=ic(a);c&&d?(a=a.match(gc),b=b.match(gc),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?ic(b)==d&&(Number(b.match(gc)[4]||null)||null)==(Number(a.match(gc)[4]||null)||null):!0;return a}
function hi(a){return a&&a.match(ei)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function oi(a){var b=pi;a=void 0===a?C("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=Ld;e.flash="0";a:{try{var f=b.h.top.location.href}catch(bb){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=void 0===g?kd:g;try{var h=g.history.length}catch(bb){h=0}e.u_his=h;var k;e.u_h=null==(k=kd.screen)?void 0:k.height;var l;e.u_w=null==(l=kd.screen)?void 0:l.width;var m;e.u_ah=null==(m=kd.screen)?void 0:m.availHeight;var q;e.u_aw=
null==(q=kd.screen)?void 0:q.availWidth;var w;e.u_cd=null==(w=kd.screen)?void 0:w.colorDepth}catch(bb){}h=b.h;try{var t=h.screenX;var z=h.screenY}catch(bb){}try{var B=h.outerWidth;var I=h.outerHeight}catch(bb){}try{var L=h.innerWidth;var N=h.innerHeight}catch(bb){}try{var R=h.screenLeft;var W=h.screenTop}catch(bb){}try{L=h.innerWidth,N=h.innerHeight}catch(bb){}try{var od=h.screen.availWidth;var ca=h.screen.availTop}catch(bb){}t=[R,W,t,z,od,ca,B,I,L,N];try{var U=(b.h.top||window).document,da="CSS1Compat"==
U.compatMode?U.documentElement:U.body;var Ua=(new td(da.clientWidth,da.clientHeight)).round()}catch(bb){Ua=new td(-12245933,-12245933)}U=Ua;Ua={};da=new Me;y.SVGElement&&y.document.createElementNS&&da.set(0);z=Fd();z["allow-top-navigation-by-user-activation"]&&da.set(1);z["allow-popups-to-escape-sandbox"]&&da.set(2);y.crypto&&y.crypto.subtle&&da.set(3);y.TextDecoder&&y.TextEncoder&&da.set(4);da=Ne(da);Ua.bc=da;Ua.bih=U.height;Ua.biw=U.width;Ua.brdim=t.join();b=b.i;U="oa";Oe.oa&&Oe.hasOwnProperty(U)?
U=Oe.oa:(da=new Oe,Oe.oa=da,Oe.hasOwnProperty(U),U=da);b=(Ua.vis=U.C(Md.flag,Md.defaultValue)&&b.prerendering?3:{visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,Ua.wgl=!!kd.WebGLRenderingContext,Ua);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var pi=new function(){var a=window.document;this.h=window;this.i=a};
A("yt.ads_.signals_.getAdSignalsString",function(a){return ji(oi(a))},void 0);Date.now();var qi="XMLHttpRequest"in y?function(){return new XMLHttpRequest}:null;
function ri(){if(!qi)return null;var a=qi();return"open"in a?a:null}
function si(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;var ti={Authorization:"AUTHORIZATION","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL","X-YouTube-Page-Label":"PAGE_BUILD_LABEL",
"X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM"},ui="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(ia("client_dev_mss_url client_dev_regex_map client_dev_root_url expflag jsfeat jsmode client_rollout_override".split(" "))),vi=!1;
function wi(a,b){b=void 0===b?{}:b;var c=ni(a),d=M("web_ajax_ignore_global_headers_if_set"),e;for(e in ti){var f=D(ti[e]);!f||!c&&ic(a)||d&&void 0!==b[e]||(b[e]=f)}if(c||!ic(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!ic(a)){try{var g=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(h){}g&&(b["X-YouTube-Time-Zone"]=g)}if(c||!ic(a))b["X-YouTube-Ad-Signals"]=ji(oi(void 0));return b}
function xi(a){var b=window.location.search,c=ic(a);M("debug_handle_relative_url_for_query_forward_killswitch")||c||!ni(a)||(c=document.location.hostname);var d=hc(a.match(gc)[5]||null);d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=ki(b),f={};db(ui,function(g){e[g]&&(f[g]=e[g])});
return mi(a,f||{},!1)}
function yi(a,b){var c=b.format||"JSON";a=zi(a,b);var d=Ai(a,b),e=!1,f=Bi(a,function(k){if(!e){e=!0;h&&Nh(h);var l=si(k),m=null,q=400<=k.status&&500>k.status,w=500<=k.status&&600>k.status;if(l||q||w)m=Ci(a,c,k,b.convertToSafeHtml);if(l)a:if(k&&204==k.status)l=!0;else{switch(c){case "XML":l=0==parseInt(m&&m.return_code,10);break a;case "RAW":l=!0;break a}l=!!m}m=m||{};q=b.context||y;l?b.onSuccess&&b.onSuccess.call(q,k,m):b.onError&&b.onError.call(q,k,m);b.onFinish&&b.onFinish.call(q,k,m)}},b.method,
d,b.headers,b.responseType,b.withCredentials);
if(b.onTimeout&&0<b.timeout){var g=b.onTimeout;var h=Mh(function(){e||(e=!0,f.abort(),Nh(h),g.call(b.context||y,f))},b.timeout)}return f}
function zi(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=D("XSRF_FIELD_NAME",void 0);if(b=b.urlParams)b[c]&&delete b[c],a=mi(a,b||{},!0);return a}
function Ai(a,b){var c=D("XSRF_FIELD_NAME",void 0),d=D("XSRF_TOKEN",void 0),e=b.postBody||"",f=b.postParams,g=D("XSRF_FIELD_NAME",void 0),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||ic(a)&&!b.withCredentials&&ic(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);f&&"string"===typeof e&&(e=ki(e),vb(e,f),e=b.postBodyFormat&&"JSON"==b.postBodyFormat?JSON.stringify(e):lc(e));f=e||f&&!ob(f);!vi&&f&&
"POST"!=b.method&&(vi=!0,Bh(Error("AJAX request with postData should use POST")));return e}
function Ci(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,Ch(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?Di(a):null)e={},db(a.getElementsByTagName("*"),function(g){e[g.tagName]=Ei(g)})}d&&Fi(e);
return e}
function Fi(a){if(Na(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;Ab("HTML that is escaped and sanitized server-side and passed through yt.net.ajax");var d=$b(a[b],null);a[c]=d}else Fi(a[b])}}
function Di(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function Ei(a){var b="";db(a.childNodes,function(c){b+=c.nodeValue});
return b}
function Bi(a,b,c,d,e,f,g){function h(){4==(k&&"readyState"in k?k.readyState:0)&&b&&Ah(b)(k)}
c=void 0===c?"GET":c;d=void 0===d?"":d;var k=ri();if(!k)return null;"onloadend"in k?k.addEventListener("loadend",h,!1):k.onreadystatechange=h;M("debug_forward_web_query_parameters")&&(a=xi(a));k.open(c,a,!0);f&&(k.responseType=f);g&&(k.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=wi(a,e))for(var l in e)k.setRequestHeader(l,e[l]),"content-type"==l.toLowerCase()&&(c=!1);c&&k.setRequestHeader("Content-Type","application/x-www-form-urlencoded");k.send(d);
return k}
;var Gi=Fc||Gc;function Hi(a){var b=Wb();return b?0<=b.toLowerCase().indexOf(a):!1}
;var Ii={},Ji=0;
function Ki(a,b,c,d,e){e=void 0===e?"":e;if(a)if(c&&!Hi("cobalt")){if(a){a instanceof Pb||(a="object"==typeof a&&a.ja?a.ia():String(a),Ub.test(a)?a=new Pb(a,Qb):(a=String(a),a=a.replace(/(%0A|%0D)/g,""),a=(b=a.match(Tb))&&Sb.test(b[1])?new Pb(a,Qb):null));b=Rb(a||Vb);if("about:invalid#zClosurez"===b||b.startsWith("data"))a="";else{if(b instanceof Zb)a=b;else{var f="object"==typeof b;a=null;f&&b.gb&&(a=b.ab());b=f&&b.ja?b.ia():String(b);Ob.test(b)&&(-1!=b.indexOf("&")&&(b=b.replace(Ib,"&amp;")),-1!=
b.indexOf("<")&&(b=b.replace(Jb,"&lt;")),-1!=b.indexOf(">")&&(b=b.replace(Kb,"&gt;")),-1!=b.indexOf('"')&&(b=b.replace(Lb,"&quot;")),-1!=b.indexOf("'")&&(b=b.replace(Mb,"&#39;")),-1!=b.indexOf("\x00")&&(b=b.replace(Nb,"&#0;")));a=$b(b,a)}a instanceof Zb&&a.constructor===Zb?a=a.h:(La(a),a="type_error:SafeHtml");a=encodeURIComponent(String(Cf(a.toString())))}/^[\s\xa0]*$/.test(a)||(a=xd("IFRAME",{src:'javascript:"<body><img src=\\""+'+a+'+"\\"></body>"',style:"display:none"}),(9==a.nodeType?a:a.ownerDocument||
a.document).body.appendChild(a))}}else if(e)Bi(a,b,"POST",e,d);else if(D("USE_NET_AJAX_FOR_PING_TRANSPORT",!1)||d)Bi(a,b,"GET","",d);else{b:{try{var g=new $a({url:a});if(g.j&&g.i||g.l){var h=hc(a.match(gc)[5]||null),k;if(!(k=!h||!h.endsWith("/aclk"))){var l=a.search(nc);d:{for(c=0;0<=(c=a.indexOf("ri",c))&&c<l;){var m=a.charCodeAt(c-1);if(38==m||63==m){var q=a.charCodeAt(c+2);if(!q||61==q||38==q||35==q){var w=c;break d}}c+=3}w=-1}if(0>w)var t=null;else{var z=a.indexOf("&",w);if(0>z||z>l)z=l;w+=3;
t=decodeURIComponent(a.substr(w,z-w).replace(/\+/g," "))}k="1"!==t}f=!k;break b}}catch(B){}f=!1}f?Li(a)?(b&&b(),f=!0):f=!1:f=!1;f||Mi(a,b)}}
function Ni(){var a=void 0===a?"":a;Li("/generate_204",a)||Ki("/generate_204",void 0,void 0,void 0,a)}
function Li(a,b){try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,void 0===b?"":b))return!0}catch(c){}return!1}
function Mi(a,b){var c=new Image,d=""+Ji++;Ii[d]=c;c.onload=c.onerror=function(){b&&Ii[d]&&b();delete Ii[d]};
c.src=a}
;var Oi=y.ytPubsubPubsubInstance||new K,Pi=y.ytPubsubPubsubSubscribedKeys||{},Qi=y.ytPubsubPubsubTopicToKeys||{},Ri=y.ytPubsubPubsubIsSynchronous||{};function Si(a,b){var c=Ti();if(c&&b){var d=c.subscribe(a,function(){var e=arguments;var f=function(){Pi[d]&&b.apply&&"function"==typeof b.apply&&b.apply(window,e)};
try{Ri[a]?f():Mh(f,0)}catch(g){Bh(g)}},void 0);
Pi[d]=!0;Qi[a]||(Qi[a]=[]);Qi[a].push(d);return d}return 0}
function Ui(a){var b=Ti();b&&("number"===typeof a?a=[a]:"string"===typeof a&&(a=[parseInt(a,10)]),db(a,function(c){b.unsubscribeByKey(c);delete Pi[c]}))}
function Vi(a,b){var c=Ti();c&&c.publish.apply(c,arguments)}
function Wi(a){var b=Ti();if(b)if(b.clear(a),a)Xi(a);else for(var c in Qi)Xi(c)}
function Ti(){return y.ytPubsubPubsubInstance}
function Xi(a){Qi[a]&&(a=Qi[a],db(a,function(b){Pi[b]&&delete Pi[b]}),a.length=0)}
K.prototype.subscribe=K.prototype.subscribe;K.prototype.unsubscribeByKey=K.prototype.ya;K.prototype.publish=K.prototype.ma;K.prototype.clear=K.prototype.clear;A("ytPubsubPubsubInstance",Oi,void 0);A("ytPubsubPubsubTopicToKeys",Qi,void 0);A("ytPubsubPubsubIsSynchronous",Ri,void 0);A("ytPubsubPubsubSubscribedKeys",Pi,void 0);var Yi=window,O=Yi.ytcsi&&Yi.ytcsi.now?Yi.ytcsi.now:Yi.performance&&Yi.performance.timing&&Yi.performance.now&&Yi.performance.timing.navigationStart?function(){return Yi.performance.timing.navigationStart+Yi.performance.now()}:function(){return(new Date).getTime()};var Zi=rh("initial_gel_batch_timeout",2E3),$i=Math.pow(2,16)-1,aj=void 0;function bj(){this.j=this.h=this.i=0}
var cj=new bj,dj=new bj,ej=!0,fj=y.ytLoggingTransportGELQueue_||new Map;A("ytLoggingTransportGELQueue_",fj,void 0);var gj=y.ytLoggingTransportGELProtoQueue_||new Map;A("ytLoggingTransportGELProtoQueue_",gj,void 0);var hj=y.ytLoggingTransportTokensToCttTargetIds_||{};A("ytLoggingTransportTokensToCttTargetIds_",hj,void 0);var ij=y.ytLoggingTransportTokensToJspbCttTargetIds_||{};A("ytLoggingTransportTokensToJspbCttTargetIds_",ij,void 0);
function jj(a,b){if("log_event"===a.endpoint){var c=kj(a),d=fj.get(c)||[];fj.set(c,d);d.push(a.payload);lj(b,d,c)}}
function mj(a,b){if("log_event"===a.endpoint){var c=kj(a,!0),d=gj.get(c)||[];gj.set(c,d);d.push(a.payload);lj(b,d,c,!0)}}
function lj(a,b,c,d){d=void 0===d?!1:d;a&&(aj=new a);a=rh("tvhtml5_logging_max_batch")||rh("web_logging_max_batch")||100;var e=O(),f=d?dj.j:cj.j;b.length>=a?nj({writeThenSend:!0},M("flush_only_full_queue")?c:void 0,d):10<=e-f&&(oj(d),d?dj.j=e:cj.j=e)}
function pj(a,b){if("log_event"===a.endpoint){var c=kj(a),d=new Map;d.set(c,[a.payload]);b&&(aj=new b);return new Jf(function(e){aj&&aj.isReady()?qj(d,e,{bypassNetworkless:!0},!0):e()})}}
function rj(a,b){if("log_event"===a.endpoint){var c=kj(a,!0),d=new Map;d.set(c,[a.payload]);b&&(aj=new b);return new Jf(function(e){aj&&aj.isReady()?sj(d,e,{bypassNetworkless:!0},!0):e()})}}
function kj(a,b){var c="";if(a.za)c="visitorOnlyApprovedKey";else if(a.cttAuthInfo){if(void 0===b?0:b){b=a.cttAuthInfo.token;c=a.cttAuthInfo;var d=new Xg;c.videoId?d.setVideoId(c.videoId):c.playlistId&&Zc(d,2,Yg,c.playlistId);ij[b]=d}else b=a.cttAuthInfo,c={},b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId),hj[a.cttAuthInfo.token]=c;c=a.cttAuthInfo.token}return c}
function nj(a,b,c){a=void 0===a?{}:a;c=void 0===c?!1:c;new Jf(function(d){c?(Nh(dj.i),Nh(dj.h),dj.h=0):(Nh(cj.i),Nh(cj.h),cj.h=0);if(aj&&aj.isReady())if(void 0!==b)if(c){var e=new Map,f=gj.get(b)||[];e.set(b,f);sj(e,d,a);gj.delete(b)}else e=new Map,f=fj.get(b)||[],e.set(b,f),qj(e,d,a),fj.delete(b);else c?(sj(gj,d,a),gj.clear()):(qj(fj,d,a),fj.clear());else oj(c),d()})}
function oj(a){a=void 0===a?!1:a;if(M("web_gel_timeout_cap")&&(!a&&!cj.h||a&&!dj.h)){var b=Mh(function(){nj({writeThenSend:!0},void 0,a)},6E4);
a?dj.h=b:cj.h=b}Nh(a?dj.i:cj.i);b=D("LOGGING_BATCH_TIMEOUT",rh("web_gel_debounce_ms",1E4));M("shorten_initial_gel_batch_timeout")&&ej&&(b=Zi);b=Mh(function(){nj({writeThenSend:!0},void 0,a)},b);
a?dj.i=b:cj.i=b}
function qj(a,b,c,d){var e=aj;c=void 0===c?{}:c;var f=Math.round(O()),g=a.size;a=r(a);for(var h=a.next();!h.done;h=a.next()){var k=r(h.value);h=k.next().value;var l=k=k.next().value;k=tb({context:tj(e.config_||uj())});k.events=l;(l=hj[h])&&vj(k,h,l);delete hj[h];h="visitorOnlyApprovedKey"===h;wj(k,f,h);xj(c);M("send_beacon_before_gel")&&window.navigator&&window.navigator.sendBeacon&&!c.writeThenSend&&Ni();yj(e,"log_event",k,zj(c,h,function(){g--;g||b()},function(){g--;
g||b()},d));
ej=!1}}
function sj(a,b,c,d){var e=aj;c=void 0===c?{}:c;var f=Math.round(O()),g=a.size;a=r(a);for(var h=a.next();!h.done;h=a.next()){var k=r(h.value);h=k.next().value;var l=k=k.next().value;k=new Zg;var m=Aj(e.config_||uj());H(k,1,m);for(m=0;m<l.length;m++)ed(k,3,Vg,l[m]);(l=ij[h])&&Bj(k,h,l);delete ij[h];h="visitorOnlyApprovedKey"===h;Cj(k,f,h);xj(c);a:{Pc=!0;try{var q=JSON.stringify(k.toJSON(),fd);break a}finally{Pc=!1}q=void 0}k=q;h=zj(c,h,function(){g--;g||b()},function(){g--;
g||b()},d);
h.headers={"Content-Type":"application/json+protobuf"};h.postBodyFormat="JSPB";h.postBody=k;yj(e,"log_event","",h);ej=!1}}
function xj(a){M("always_send_and_write")&&(a.writeThenSend=!1)}
function zj(a,b,c,d,e){return{retry:!0,onSuccess:c,onError:d,Fb:a,za:b,po:!!e,headers:{},postBodyFormat:"",postBody:""}}
function wj(a,b,c){a.requestTimeMs=String(b);M("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=D("EVENT_ID",void 0))&&(c=Dj(),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function Cj(a,b,c){G(a,2,b);if(!c&&(b=D("EVENT_ID",void 0))){c=Dj();var d=new Wg;G(d,1,b);G(d,2,c);H(a,5,d)}}
function Dj(){var a=D("BATCH_CLIENT_COUNTER",void 0)||0;a||(a=Math.floor(Math.random()*$i/2));a++;a>$i&&(a=1);ph("BATCH_CLIENT_COUNTER",a);return a}
function vj(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function Bj(a,b,c){if(Xc(c,1===$c(c,Yg)?1:-1))var d=1;else if(c.getPlaylistId())d=2;else return;H(a,4,c);a=ad(a,Dg,1)||new Dg;c=ad(a,Bg,3)||new Bg;var e=new Ag;e.setToken(b);G(e,1,d);ed(c,12,Ag,e);H(a,3,c)}
;var Ej=y.ytLoggingGelSequenceIdObj_||{};A("ytLoggingGelSequenceIdObj_",Ej,void 0);
function Fj(a,b,c,d){d=void 0===d?{}:d;if(M("lr_drop_other_and_business_payloads")){if(vh[a]||uh[a])return}else if(M("lr_drop_other_payloads")&&vh[a])return;var e={},f=Math.round(d.timestamp||O());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;a=ai();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};M("log_sequence_info_on_gel_web")&&d.W&&(a=e.context,b=d.W,b={index:Gj(b),groupKey:b},a.sequence=b,d.yb&&delete Ej[d.W]);(d.sc?pj:jj)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,
za:d.za},c)}
function Gj(a){Ej[a]=a in Ej?Ej[a]+1:0;return Ej[a]}
;function Hj(a){var b=this;this.h=void 0;a.addEventListener("beforeinstallprompt",function(c){c.preventDefault();b.h=c})}
function Ij(){if(!y.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return y.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":y.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":y.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":y.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
function Jj(){var a=Ij();a=Object.keys(Le).indexOf(a);return-1===a?null:a}
;function Kj(a,b,c,d,e){Vd.set(""+a,b,{Sa:c,path:"/",domain:void 0===d?"youtube.com":d,secure:void 0===e?!1:e})}
function Lj(a){return Vd.get(""+a,void 0)}
function Mj(){if(!Vd.isEnabled())return!1;if(!Vd.isEmpty())return!0;Vd.set("TESTCOOKIESENABLED","1",{Sa:60});if("1"!==Vd.get("TESTCOOKIESENABLED"))return!1;Vd.remove("TESTCOOKIESENABLED");return!0}
;var Nj=C("ytglobal.prefsUserPrefsPrefs_")||{};A("ytglobal.prefsUserPrefsPrefs_",Nj,void 0);function Oj(){this.h=D("ALT_PREF_COOKIE_NAME","PREF");this.i=D("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=Lj(this.h);if(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(Nj[d]=c.toString())}}}
Oj.prototype.get=function(a,b){Pj(a);Qj(a);a=void 0!==Nj[a]?Nj[a].toString():null;return null!=a?a:b?b:""};
Oj.prototype.set=function(a,b){Pj(a);Qj(a);if(null==b)throw Error("ExpectedNotNull");Nj[a]=b.toString()};
function Rj(a){return!!((Sj("f"+(Math.floor(a/31)+1))||0)&1<<a%31)}
Oj.prototype.remove=function(a){Pj(a);Qj(a);delete Nj[a]};
Oj.prototype.clear=function(){for(var a in Nj)delete Nj[a]};
function Qj(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function Pj(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function Sj(a){a=void 0!==Nj[a]?Nj[a].toString():null;return null!=a&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
Ka(Oj);var Tj={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},Uj={CONN_DEFAULT:0,CONN_UNKNOWN:1,CONN_NONE:2,CONN_WIFI:3,CONN_CELLULAR_2G:4,CONN_CELLULAR_3G:5,CONN_CELLULAR_4G:6,CONN_CELLULAR_UNKNOWN:7,CONN_DISCO:8,CONN_CELLULAR_5G:9,CONN_WIFI_METERED:10,CONN_CELLULAR_5G_SA:11,
CONN_CELLULAR_5G_NSA:12,CONN_INVALID:31},Vj={EFFECTIVE_CONNECTION_TYPE_UNKNOWN:0,EFFECTIVE_CONNECTION_TYPE_OFFLINE:1,EFFECTIVE_CONNECTION_TYPE_SLOW_2G:2,EFFECTIVE_CONNECTION_TYPE_2G:3,EFFECTIVE_CONNECTION_TYPE_3G:4,EFFECTIVE_CONNECTION_TYPE_4G:5},Wj={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};function Xj(){var a=y.navigator;return a?a.connection:void 0}
function Yj(){var a=Xj();if(a){var b=Tj[a.type||"unknown"]||"CONN_UNKNOWN";a=Tj[a.effectiveType||"unknown"]||"CONN_UNKNOWN";"CONN_CELLULAR_UNKNOWN"===b&&"CONN_UNKNOWN"!==a&&(b=a);if("CONN_UNKNOWN"!==b)return b;if("CONN_UNKNOWN"!==a)return a}}
function Zj(){var a=Xj();if(null!==a&&void 0!==a&&a.effectiveType)return Wj.hasOwnProperty(a.effectiveType)?Wj[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN"}
;function ak(){return"INNERTUBE_API_KEY"in jh&&"INNERTUBE_API_VERSION"in jh}
function uj(){return{innertubeApiKey:D("INNERTUBE_API_KEY",void 0),innertubeApiVersion:D("INNERTUBE_API_VERSION",void 0),hb:D("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),ib:D("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),ac:D("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:D("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0),Cb:D("INNERTUBE_CONTEXT_HL",void 0),Bb:D("INNERTUBE_CONTEXT_GL",void 0),cc:D("INNERTUBE_HOST_OVERRIDE",void 0)||"",ec:!!D("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),dc:!!D("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:D("SERIALIZED_CLIENT_CONFIG_DATA",void 0)}}
function tj(a){var b={client:{hl:a.Cb,gl:a.Bb,clientName:a.ib,clientVersion:a.innertubeContextClientVersion,configInfo:a.hb}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=y.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=sh();""!==c&&(b.client.experimentsToken=c);c=th();0<c.length&&(b.request={internalExperimentFlags:c});bk(a,void 0,b);ck(a,void 0,b);dk(void 0,b);ek(a,void 0,b);fk(void 0,b);D("DELEGATED_SESSION_ID")&&!M("pageid_as_header_web")&&(b.user=
{onBehalfOfUser:D("DELEGATED_SESSION_ID")});a=Object;c=a.assign;for(var d=b.client,e={},f=r(Object.entries(ki(D("DEVICE","")))),g=f.next();!g.done;g=f.next()){var h=r(g.value);g=h.next().value;h=h.next().value;"cbrand"===g?e.deviceMake=h:"cmodel"===g?e.deviceModel=h:"cbr"===g?e.browserName=h:"cbrver"===g?e.browserVersion=h:"cos"===g?e.osName=h:"cosver"===g?e.osVersion=h:"cplatform"===g&&(e.platform=h)}b.client=c.call(a,d,e);return b}
function Aj(a){var b=new Dg,c=new wg;G(c,1,a.Cb);G(c,2,a.Bb);G(c,16,a.ac);G(c,17,a.innertubeContextClientVersion);if(a.hb){var d=a.hb,e=new tg;d.coldConfigData&&G(e,1,d.coldConfigData);d.appInstallData&&G(e,6,d.appInstallData);d.coldHashData&&G(e,3,d.coldHashData);d.hotHashData&&G(e,5,d.hotHashData);H(c,62,e)}(d=y.devicePixelRatio)&&1!=d&&G(c,65,d);d=sh();""!==d&&G(c,54,d);d=th();if(0<d.length){e=new yg;for(var f=0;f<d.length;f++){var g=new rg;G(g,1,d[f].key);g.setValue(d[f].value);ed(e,15,rg,g)}H(b,
5,e)}bk(a,c);ck(a,c);dk(c);ek(a,c);fk(c);D("DELEGATED_SESSION_ID")&&!M("pageid_as_header_web")&&(a=new Bg,G(a,3,D("DELEGATED_SESSION_ID")));a=r(Object.entries(ki(D("DEVICE",""))));for(d=a.next();!d.done;d=a.next())e=r(d.value),d=e.next().value,e=e.next().value,"cbrand"===d?G(c,12,e):"cmodel"===d?G(c,13,e):"cbr"===d?G(c,87,e):"cbrver"===d?G(c,88,e):"cos"===d?G(c,18,e):"cosver"===d?G(c,19,e):"cplatform"===d&&G(c,42,e);H(b,1,c);return b}
function bk(a,b,c){a=a.ib;if("WEB"===a||"MWEB"===a||1===a||2===a)if(b){c=ad(b,ug,96)||new ug;var d=Jj();null!==d&&G(c,3,d);H(b,96,c)}else c&&(c.client.mainAppWebInfo=null!=(d=c.client.mainAppWebInfo)?d:{},c.client.mainAppWebInfo.webDisplayMode=Ij())}
function ck(a,b,c){a=a.ib;if(("WEB_REMIX"===a||76===a)&&!M("music_web_display_mode_killswitch"))if(b){var d;c=null!=(d=ad(b,vg,70))?d:new vg;d=Jj();null!==d&&G(c,10,d);H(b,70,c)}else if(c){var e;c.client.Eb=null!=(e=c.client.Eb)?e:{};c.client.Eb.webDisplayMode=Ij()}}
function dk(a,b){var c;if(M("web_log_memory_total_kbytes")&&(null==(c=y.navigator)?0:c.deviceMemory)){var d;c=null==(d=y.navigator)?void 0:d.deviceMemory;a?G(a,95,1E6*c):b&&(b.client.memoryTotalKbytes=""+1E6*c)}}
function ek(a,b,c){if(a.appInstallData)if(b){var d;c=null!=(d=ad(b,tg,62))?d:new tg;G(c,6,a.appInstallData);H(b,62,c)}else c&&(c.client.configInfo=c.client.configInfo||{},c.client.configInfo.appInstallData=a.appInstallData)}
function fk(a,b){var c=Yj();c&&(a?G(a,61,Uj[c]):b&&(b.client.connectionType=c));M("web_log_effective_connection_type")&&(c=Zj())&&(a?G(a,94,Vj[c]):b&&(b.client.effectiveConnectionType=c))}
function gk(a,b,c){c=void 0===c?{}:c;var d={"X-Goog-Visitor-Id":c.visitorData||D("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;(b=c.no||D("AUTHORIZATION"))||(a?b="Bearer "+C("gapi.auth.getToken")().mo:b=Zd([]));b&&(d.Authorization=b,d["X-Goog-AuthUser"]=D("SESSION_INDEX",0),M("pageid_as_header_web")&&(d["X-Goog-PageId"]=D("DELEGATED_SESSION_ID")));return d}
;function hk(a){a=Object.assign({},a);delete a.Authorization;var b=Zd();if(b){var c=new ff;c.update(D("INNERTUBE_API_KEY",void 0));c.update(b);a.hash=Kc(c.digest(),3)}return a}
;function ik(a){var b=new kg;(b=b.isAvailable()?a?new qg(b,a):b:null)||(a=new lg(a||"UserDataSharedStore"),b=a.isAvailable()?a:null);this.h=(a=b)?new gg(a):null;this.i=document.domain||window.location.hostname}
ik.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape(Cf(b))}catch(f){return}else e=escape(b);Kj(a,e,c,this.i)};
ik.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=Lj(a))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
ik.prototype.remove=function(a){this.h&&this.h.remove(a);var b=this.i;Vd.remove(""+a,"/",void 0===b?"youtube.com":b)};var jk;function kk(){jk||(jk=new ik("yt.innertube"));return jk}
function lk(a,b,c,d){if(d)return null;d=kk().get("nextId",!0)||1;var e=kk().get("requests",!0)||{};e[d]={method:a,request:b,authState:hk(c),requestTime:Math.round(O())};kk().set("nextId",d+1,86400,!0);kk().set("requests",e,86400,!0);return d}
function mk(a){var b=kk().get("requests",!0)||{};delete b[a];kk().set("requests",b,86400,!0)}
function nk(a){var b=kk().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(O())-d.requestTime)){var e=d.authState,f=hk(gk(!1));rb(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(O())),yj(a,d.method,e,{}));delete b[c]}}kk().set("requests",b,86400,!0)}}
;var ok=function(){var a;return function(){a||(a=new ik("ytidb"));return a}}();
function pk(){var a;return null===(a=ok())||void 0===a?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var qk=[],rk,sk=!1;function tk(){var a={};for(rk=new uk(void 0===a.handleError?vk:a.handleError,void 0===a.logEvent?P:a.logEvent);0<qk.length;)switch(a=qk.shift(),a.type){case "ERROR":rk.handleError(a.payload);break;case "EVENT":rk.logEvent(a.eventType,a.payload)}}
function wk(a){sk||(rk?rk.handleError(a):(qk.push({type:"ERROR",payload:a}),10<qk.length&&qk.shift()))}
function xk(a,b){sk||(rk?rk.logEvent(a,b):(qk.push({type:"EVENT",eventType:a,payload:b}),10<qk.length&&qk.shift()))}
;function yk(a){var b=Ea.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(ia(b))}
u(yk,Error);function zk(){try{return Ak(),!0}catch(a){return!1}}
function Ak(){if(void 0!==D("DATASYNC_ID",void 0))return D("DATASYNC_ID",void 0);throw new yk("Datasync ID not set","unknown");}
;function Bk(a){if(0<=a.indexOf(":"))throw Error("Database name cannot contain ':'");}
function Ck(a){return a.substr(0,a.indexOf(":"))||a}
;var Dk={},Ek=(Dk.AUTH_INVALID="No user identifier specified.",Dk.EXPLICIT_ABORT="Transaction was explicitly aborted.",Dk.IDB_NOT_SUPPORTED="IndexedDB is not supported.",Dk.MISSING_INDEX="Index not created.",Dk.MISSING_OBJECT_STORES="Object stores not created.",Dk.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",Dk.DB_REOPENED_BY_MISSING_OBJECT_STORES="Database is reopened because expected object stores were not created.",Dk.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",
Dk.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",Dk.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",Dk.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",Dk.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",Dk),Fk={},Gk=(Fk.AUTH_INVALID="ERROR",Fk.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",Fk.EXPLICIT_ABORT="IGNORED",Fk.IDB_NOT_SUPPORTED="ERROR",Fk.MISSING_INDEX=
"WARNING",Fk.MISSING_OBJECT_STORES="ERROR",Fk.DB_DELETED_BY_MISSING_OBJECT_STORES="WARNING",Fk.DB_REOPENED_BY_MISSING_OBJECT_STORES="WARNING",Fk.QUOTA_EXCEEDED="WARNING",Fk.QUOTA_MAYBE_EXCEEDED="WARNING",Fk.UNKNOWN_ABORT="WARNING",Fk.INCOMPATIBLE_DB_VERSION="WARNING",Fk),Hk={},Ik=(Hk.AUTH_INVALID=!1,Hk.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,Hk.EXPLICIT_ABORT=!1,Hk.IDB_NOT_SUPPORTED=!1,Hk.MISSING_INDEX=!1,Hk.MISSING_OBJECT_STORES=!1,Hk.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,Hk.DB_REOPENED_BY_MISSING_OBJECT_STORES=
!1,Hk.QUOTA_EXCEEDED=!1,Hk.QUOTA_MAYBE_EXCEEDED=!0,Hk.UNKNOWN_ABORT=!0,Hk.INCOMPATIBLE_DB_VERSION=!1,Hk);function Q(a,b,c,d,e){b=void 0===b?{}:b;c=void 0===c?Ek[a]:c;d=void 0===d?Gk[a]:d;e=void 0===e?Ik[a]:e;yk.call(this,c,Object.assign({name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,Q.prototype)}
u(Q,yk);function Jk(a,b){Q.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},Ek.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,Jk.prototype)}
u(Jk,Q);function Kk(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,Kk.prototype)}
u(Kk,Error);var Lk=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function Mk(a,b,c,d){b=Ck(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof Q)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if("QuotaExceededError"===e.name)return new Q("QUOTA_EXCEEDED",a);if(Hc&&"UnknownError"===e.name)return new Q("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof Kk)return new Q("MISSING_INDEX",Object.assign(Object.assign({},a),{objectStore:e.objectStore,index:e.index}));if("InvalidStateError"===e.name&&Lk.some(function(f){return e.message.includes(f)}))return new Q("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if("AbortError"===e.name)return new Q("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign(Object.assign({},a),{name:"IdbError",Gb:e.name})];e.level="WARNING";return e}
function Nk(a,b,c){var d=pk();return new Q("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:null===d||void 0===d?void 0:d.hasSucceededOnce}})}
;function Ok(a){if(!a)throw Error();throw a;}
function Pk(a){return a}
function Qk(a){this.h=a}
function Rk(a){function b(e){if("PENDING"===d.state.status){d.state={status:"REJECTED",reason:e};e=r(d.onRejected);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if("PENDING"===d.state.status){d.state={status:"FULFILLED",value:e};e=r(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.h=[];this.onRejected=[];a=a.h;try{a(c,b)}catch(e){b(e)}}
Rk.all=function(a){return new Rk(new Qk(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={ra:0};f.ra<a.length;f={ra:f.ra},++f.ra)Sk(Rk.resolve(a[f.ra]).then(function(g){return function(h){d[g.ra]=h;e--;0===e&&b(d)}}(f)),function(g){c(g)})}))};
Rk.resolve=function(a){return new Rk(new Qk(function(b,c){a instanceof Rk?a.then(b,c):b(a)}))};
Rk.reject=function(a){return new Rk(new Qk(function(b,c){c(a)}))};
Rk.prototype.then=function(a,b){var c=this,d=null!==a&&void 0!==a?a:Pk,e=null!==b&&void 0!==b?b:Ok;return new Rk(new Qk(function(f,g){"PENDING"===c.state.status?(c.h.push(function(){Tk(c,c,d,f,g)}),c.onRejected.push(function(){Uk(c,c,e,f,g)})):"FULFILLED"===c.state.status?Tk(c,c,d,f,g):"REJECTED"===c.state.status&&Uk(c,c,e,f,g)}))};
function Sk(a,b){a.then(void 0,b)}
function Tk(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof Rk?Vk(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Uk(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof Rk?Vk(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Vk(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof Rk?Vk(a,b,f,d,e):d(f)},function(f){e(f)})}
;function Wk(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function Xk(a){return new Promise(function(b,c){Wk(a,b,c)})}
function Yk(a){return new Rk(new Qk(function(b,c){Wk(a,b,c)}))}
;function Zk(a,b){return new Rk(new Qk(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;function $k(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(O());this.i=!1}
n=$k.prototype;n.add=function(a,b,c){return al(this,[a],{mode:"readwrite",O:!0},function(d){return d.objectStore(a).add(b,c)})};
n.clear=function(a){return al(this,[a],{mode:"readwrite",O:!0},function(b){return b.objectStore(a).clear()})};
n.close=function(){var a;this.h.close();(null===(a=this.options)||void 0===a?0:a.closed)&&this.options.closed()};
n.count=function(a,b){return al(this,[a],{mode:"readonly",O:!0},function(c){return c.objectStore(a).count(b)})};
function bl(a,b,c){a=a.h.createObjectStore(b,c);return new cl(a)}
n.delete=function(a,b){return al(this,[a],{mode:"readwrite",O:!0},function(c){return c.objectStore(a).delete(b)})};
n.get=function(a,b){return al(this,[a],{mode:"readonly",O:!0},function(c){return c.objectStore(a).get(b)})};
function dl(a,b){return al(a,["LogsRequestsStore"],{mode:"readwrite",O:!0},function(c){c=c.objectStore("LogsRequestsStore");return Yk(c.h.put(b,void 0))})}
n.objectStoreNames=function(){return Array.from(this.h.objectStoreNames)};
function al(a,b,c,d){var e,f,g,h,k,l,m,q,w,t,z,B;return x(function(I){switch(I.h){case 1:var L={mode:"readonly",O:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};"string"===typeof c?L.mode=c:Object.assign(L,c);e=L;a.transactionCount++;f=e.O?3:1;g=0;case 2:if(h){I.s(3);break}g++;k=Math.round(O());ta(I,4);l=a.h.transaction(b,e.mode);L=new el(l);L=fl(L,d);return v(I,L,6);case 6:return m=I.i,q=Math.round(O()),gl(a,k,q,g,void 0,b.join(),e),I.return(m);case 4:w=va(I);t=Math.round(O());z=Mk(w,a.h.name,b.join(),a.h.version);
if((B=z instanceof Q&&!z.h)||g>=f)gl(a,k,t,g,z,b.join(),e),h=z;I.s(2);break;case 3:return I.return(Promise.reject(h))}})}
function gl(a,b,c,d,e,f,g){b=c-b;e?(e instanceof Q&&("QUOTA_EXCEEDED"===e.type||"QUOTA_MAYBE_EXCEEDED"===e.type)&&xk("QUOTA_EXCEEDED",{dbName:Ck(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof Q&&"UNKNOWN_ABORT"===e.type&&(c-=a.j,0>c&&c>=Math.pow(2,31)&&(c=0),xk("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.i=!0),hl(a,!1,d,f,b,g.tag),wk(e)):hl(a,!0,d,f,b,g.tag)}
function hl(a,b,c,d,e,f){xk("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c,tag:void 0===f?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
n.getName=function(){return this.h.name};
function cl(a){this.h=a}
n=cl.prototype;n.add=function(a,b){return Yk(this.h.add(a,b))};
n.autoIncrement=function(){return this.h.autoIncrement};
n.clear=function(){return Yk(this.h.clear()).then(function(){})};
n.count=function(a){return Yk(this.h.count(a))};
function il(a,b){return jl(a,{query:b},function(c){return c.delete().then(function(){return c.continue()})}).then(function(){})}
n.delete=function(a){return a instanceof IDBKeyRange?il(this,a):Yk(this.h.delete(a))};
n.get=function(a){return Yk(this.h.get(a))};
n.index=function(a){try{return new kl(this.h.index(a))}catch(b){if(b instanceof Error&&"NotFoundError"===b.name)throw new Kk(a,this.h.name);throw b;}};
n.getName=function(){return this.h.name};
n.keyPath=function(){return this.h.keyPath};
function jl(a,b,c){a=a.h.openCursor(b.query,b.direction);return ll(a).then(function(d){return Zk(d,c)})}
function el(a){var b=this;this.h=a;this.j=new Map;this.i=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.i){e=Q;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(null===k)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function fl(a,b){var c=new Promise(function(d,e){try{Sk(b(a).then(function(f){d(f)}),e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return r(d).next().value})}
el.prototype.abort=function(){this.h.abort();this.i=!0;throw new Q("EXPLICIT_ABORT");};
el.prototype.objectStore=function(a){a=this.h.objectStore(a);var b=this.j.get(a);b||(b=new cl(a),this.j.set(a,b));return b};
function kl(a){this.h=a}
n=kl.prototype;n.count=function(a){return Yk(this.h.count(a))};
n.delete=function(a){return ml(this,{query:a},function(b){return b.delete().then(function(){return b.continue()})})};
n.get=function(a){return Yk(this.h.get(a))};
n.getKey=function(a){return Yk(this.h.getKey(a))};
n.keyPath=function(){return this.h.keyPath};
n.unique=function(){return this.h.unique};
function ml(a,b,c){a=a.h.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return ll(a).then(function(d){return Zk(d,c)})}
function nl(a,b){this.request=a;this.cursor=b}
function ll(a){return Yk(a).then(function(b){return b?new nl(a,b):null})}
n=nl.prototype;n.advance=function(a){this.cursor.advance(a);return ll(this.request)};
n.continue=function(a){this.cursor.continue(a);return ll(this.request)};
n.delete=function(){return Yk(this.cursor.delete()).then(function(){})};
n.getKey=function(){return this.cursor.key};
n.getValue=function(){return this.cursor.value};
n.update=function(a){return Yk(this.cursor.update(a))};function ol(a,b,c){return new Promise(function(d,e){function f(){w||(w=new $k(g.result,{closed:q}));return w}
var g=void 0!==b?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.blocked,k=c.blocking,l=c.Dc,m=c.upgrade,q=c.closed,w;g.addEventListener("upgradeneeded",function(t){try{if(null===t.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(null===g.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");t.dataLoss&&"none"!==t.dataLoss&&xk("IDB_DATA_CORRUPTED",{reason:t.dataLossMessage||"unknown reason",dbName:Ck(a)});var z=f(),B=new el(g.transaction);
m&&m(z,function(I){return t.oldVersion<I&&t.newVersion>=I},B);
B.done.catch(function(I){e(I)})}catch(I){e(I)}});
g.addEventListener("success",function(){var t=g.result;k&&t.addEventListener("versionchange",function(){k(f())});
t.addEventListener("close",function(){xk("IDB_UNEXPECTEDLY_CLOSED",{dbName:Ck(a),dbVersion:t.version});l&&l()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function pl(a,b,c){c=void 0===c?{}:c;return ol(a,b,c)}
function ql(a,b){b=void 0===b?{}:b;var c,d,e,f;return x(function(g){if(1==g.h)return ta(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.blocked)&&c.addEventListener("blocked",function(){e()}),v(g,Xk(c),4);
if(2!=g.h)return ua(g,0);f=va(g);throw Mk(f,a,"",-1);})}
;function rl(a){return new Promise(function(b){Sh(function(){b()},a)})}
function sl(a,b){this.name=a;this.options=b;this.l=!0;this.m=this.o=0;this.i=500}
sl.prototype.j=function(a,b,c){c=void 0===c?{}:c;return pl(a,b,c)};
sl.prototype.delete=function(a){a=void 0===a?{}:a;return ql(this.name,a)};
function tl(a,b){return new Q("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function ul(a,b){if(!b)throw Nk("openWithToken",Ck(a.name));return a.open()}
sl.prototype.open=function(){function a(){var f,g,h,k,l,m,q,w,t,z;return x(function(B){switch(B.h){case 1:return h=null!==(f=Error().stack)&&void 0!==f?f:"",ta(B,2),v(B,c.j(c.name,c.options.version,e),4);case 4:k=B.i;for(var I=c.options,L=[],N=r(Object.keys(I.Ba)),R=N.next();!R.done;R=N.next()){R=R.value;var W=I.Ba[R],od=void 0===W.mc?Number.MAX_VALUE:W.mc;!(k.h.version>=W.Za)||k.h.version>=od||k.h.objectStoreNames.contains(R)||L.push(R)}l=L;if(0===l.length){B.s(5);break}m=Object.keys(c.options.Ba);
q=k.objectStoreNames();if(c.m<rh("ytidb_reopen_db_retries",0))return c.m++,k.close(),wk(new Q("DB_REOPENED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:m,foundObjectStores:q})),B.return(a());if(!(c.o<rh("ytidb_remake_db_retries",1))){B.s(6);break}c.o++;if(!M("ytidb_remake_db_enable_backoff_delay")){B.s(7);break}return v(B,rl(c.i),8);case 8:c.i*=2;case 7:return v(B,c.delete(),9);case 9:return wk(new Q("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:m,foundObjectStores:q})),
B.return(a());case 6:throw new Jk(q,m);case 5:return B.return(k);case 2:w=va(B);if(w instanceof DOMException?"VersionError"!==w.name:"DOMError"in self&&w instanceof DOMError?"VersionError"!==w.name:!(w instanceof Object&&"message"in w)||"An attempt was made to open a database using a lower version than the existing version."!==w.message){B.s(10);break}return v(B,c.j(c.name,void 0,Object.assign(Object.assign({},e),{upgrade:void 0})),11);case 11:t=B.i;z=t.h.version;if(void 0!==c.options.version&&z>
c.options.version+1)throw t.close(),c.l=!1,tl(c,z);return B.return(t);case 10:throw b(),w instanceof Error&&!M("ytidb_async_stack_killswitch")&&(w.stack=w.stack+"\n"+h.substring(h.indexOf("\n")+1)),Mk(w,c.name,"",null!==(g=c.options.version)&&void 0!==g?g:-1);}})}
function b(){c.h===d&&(c.h=void 0)}
var c=this;if(!this.l)throw tl(this);if(this.h)return this.h;var d,e={blocking:function(f){f.close()},
closed:b,Dc:b,upgrade:this.options.upgrade};return this.h=d=a()};var vl=new sl("YtIdbMeta",{Ba:{databases:{Za:1}},upgrade:function(a,b){b(1)&&bl(a,"databases",{keyPath:"actualName"})}});
function wl(a,b){var c;return x(function(d){if(1==d.h)return v(d,ul(vl,b),2);c=d.i;return d.return(al(c,["databases"],{O:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return Yk(f.h.put(a,void 0)).then(function(){})})}))})}
function xl(a,b){var c;return x(function(d){if(1==d.h)return a?v(d,ul(vl,b),2):d.return();c=d.i;return d.return(c.delete("databases",a))})}
function yl(a,b){var c,d;return x(function(e){return 1==e.h?(c=[],v(e,ul(vl,b),2)):3!=e.h?(d=e.i,v(e,al(d,["databases"],{O:!0,mode:"readonly"},function(f){c.length=0;return jl(f.objectStore("databases"),{},function(g){a(g.getValue())&&c.push(g.getValue());return g.continue()})}),3)):e.return(c)})}
function zl(a){return yl(function(b){return"LogsDatabaseV2"===b.publicName&&void 0!==b.userIdentifier},a)}
function Al(a,b){return yl(function(c){return void 0!==c.userIdentifier&&!a.includes(c.userIdentifier)},b)}
;var Bl,Cl=new function(){}(new function(){});
function Dl(){var a,b,c;return x(function(d){switch(d.h){case 1:a=pk();if(null===a||void 0===a?0:a.hasSucceededOnce)return d.return(!0);var e;if(e=Gi)e=/WebKit\/([0-9]+)/.exec(Wb()),e=!!(e&&600<=parseInt(e[1],10));e&&(e=/WebKit\/([0-9]+)/.exec(Wb()),e=!(e&&602<=parseInt(e[1],10)));if(e||sc)return d.return(!1);try{if(b=self,!(b.indexedDB&&b.IDBIndex&&b.IDBKeyRange&&b.IDBObjectStore))return d.return(!1)}catch(f){return d.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return d.return(!1);
ta(d,2);c={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return v(d,wl(c,Cl),4);case 4:return v(d,xl("yt-idb-test-do-not-use",Cl),5);case 5:return d.return(!0);case 2:return va(d),d.return(!1)}})}
function El(){if(void 0!==Bl)return Bl;sk=!0;return Bl=Dl().then(function(a){sk=!1;var b,c;null!==(b=ok())&&void 0!==b&&b.h&&(b=pk(),b={hasSucceededOnce:(null===b||void 0===b?void 0:b.hasSucceededOnce)||a},null===(c=ok())||void 0===c?void 0:c.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0));return a})}
function Fl(){return C("ytglobal.idbToken_")||void 0}
function Gl(){var a=Fl();return a?Promise.resolve(a):El().then(function(b){(b=b?Cl:void 0)&&A("ytglobal.idbToken_",b,void 0);return b})}
;var Hl=0;function Il(a){Hl||(Hl=Wh.M(function(){var b,c,d,e,f;return x(function(g){switch(g.h){case 1:return v(g,Gl(),2);case 2:b=g.i;if(!b)return g.return();c=!0;ta(g,3);return v(g,Al(a,b),5);case 5:d=g.i;if(!d.length){c=!1;g.s(6);break}e=d[0];return v(g,ql(e.actualName),7);case 7:return v(g,xl(e.actualName,b),6);case 6:ua(g,4);break;case 3:f=va(g),wk(f),c=!1;case 4:Wh.U(Hl),Hl=0,c&&Il(a),g.h=0}})}))}
new id;function Jl(a){if(!zk())throw a=new Q("AUTH_INVALID",{dbName:a}),wk(a),a;var b=Ak();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function Kl(a,b,c,d){var e,f,g,h,k,l;return x(function(m){switch(m.h){case 1:return f=null!==(e=Error().stack)&&void 0!==e?e:"",v(m,Gl(),2);case 2:g=m.i;if(!g)throw h=Nk("openDbImpl",a,b),M("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),wk(h),h;Bk(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:Jl(a);ta(m,3);return v(m,wl(k,g),5);case 5:return v(m,pl(k.actualName,b,d),6);case 6:return m.return(m.i);case 3:return l=va(m),ta(m,7),v(m,xl(k.actualName,
g),9);case 9:ua(m,8);break;case 7:va(m);case 8:throw l;}})}
function Ll(a,b,c){c=void 0===c?{}:c;return Kl(a,b,!1,c)}
function Ml(a,b,c){c=void 0===c?{}:c;return Kl(a,b,!0,c)}
function Nl(a,b){b=void 0===b?{}:b;var c,d;return x(function(e){if(1==e.h)return v(e,Gl(),2);if(3!=e.h){c=e.i;if(!c)return e.return();Bk(a);d=Jl(a);return v(e,ql(d.actualName,b),3)}return v(e,xl(d.actualName,c),0)})}
function Ol(a,b,c){a=a.map(function(d){return x(function(e){return 1==e.h?v(e,ql(d.actualName,b),2):v(e,xl(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function Pl(){var a=void 0===a?{}:a;var b,c;return x(function(d){if(1==d.h)return v(d,Gl(),2);if(3!=d.h){b=d.i;if(!b)return d.return();Bk("LogsDatabaseV2");return v(d,zl(b),3)}c=d.i;return v(d,Ol(c,a,b),0)})}
function Ql(a,b){b=void 0===b?{}:b;var c;return x(function(d){if(1==d.h)return v(d,Gl(),2);if(3!=d.h){c=d.i;if(!c)return d.return();Bk(a);return v(d,ql(a,b),3)}return v(d,xl(a,c),0)})}
;function Rl(a){var b,c,d,e,f,g,h,k;this.h=!1;this.potentialEsfErrorCounter=this.i=0;this.handleError=function(){};
this.va=function(){};
this.now=Date.now;this.Aa=!1;this.Ob=null!==(b=a.Ob)&&void 0!==b?b:100;this.Lb=null!==(c=a.Lb)&&void 0!==c?c:1;this.Jb=null!==(d=a.Jb)&&void 0!==d?d:2592E6;this.Hb=null!==(e=a.Hb)&&void 0!==e?e:12E4;this.Kb=null!==(f=a.Kb)&&void 0!==f?f:5E3;this.v=null!==(g=a.v)&&void 0!==g?g:void 0;this.Oa=!!a.Oa;this.Na=null!==(h=a.Na)&&void 0!==h?h:.1;this.Ua=null!==(k=a.Ua)&&void 0!==k?k:10;a.handleError&&(this.handleError=a.handleError);a.va&&(this.va=a.va);a.Aa&&(this.Aa=a.Aa);this.C=a.C;this.V=a.V;this.J=a.J;
this.I=a.I;this.ea=a.ea;this.mb=a.mb;this.lb=a.lb;this.v&&(!this.C||this.C("networkless_logging"))&&Sl(this)}
function Sl(a){return x(function(b){if(1==b.h)return!a.v||a.Aa?b.return():a.Oa&&Math.random()<=a.Na?v(b,a.J.Ub(a.v),2):b.s(2);Tl(a);a.I.G()&&a.Ea();a.I.ba(a.mb,a.Ea.bind(a));a.I.ba(a.lb,a.rb.bind(a));a.h=!0;b.h=0})}
n=Rl.prototype;n.writeThenSend=function(a,b){var c=this;b=void 0===b?{}:b;if(this.v&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.J.set(d,this.v).then(function(e){d.id=e;c.I.G()&&Ul(c,d)}).catch(function(e){Ul(c,d);
Vl(c,e)})}else this.ea(a,b)};
n.sendThenWrite=function(a,b,c){var d=this;b=void 0===b?{}:b;if(this.v&&this.h){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.C&&this.C("nwl_skip_retry")&&(e.skipRetry=c);if(this.I.G()||this.C&&this.C("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return x(function(k){if(1==k.h)return v(k,d.J.set(e,d.v).catch(function(l){Vl(d,l)}),2);
f(g,h);k.h=0})}}this.ea(a,b,e.skipRetry)}else this.J.set(e,this.v).catch(function(g){d.ea(a,b,e.skipRetry);
Vl(d,g)})}else this.ea(a,b,this.C&&this.C("nwl_skip_retry")&&c)};
n.sendAndWrite=function(a,b){var c=this;b=void 0===b?{}:b;if(this.v&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){void 0!==d.id?c.J.ta(d.id,c.v):e=!0;c.I.ca&&c.C&&c.C("vss_network_hint")&&c.I.ca(!0);f(g,h)};
this.ea(d.url,d.options);this.J.set(d,this.v).then(function(g){d.id=g;e&&c.J.ta(d.id,c.v)}).catch(function(g){Vl(c,g)})}else this.ea(a,b)};
n.Ea=function(){var a=this;if(!this.v)throw Nk("throttleSend");this.i||(this.i=this.V.M(function(){var b;return x(function(c){if(1==c.h)return v(c,a.J.Ab("NEW",a.v),2);if(3!=c.h)return b=c.i,b?v(c,Ul(a,b),3):(a.rb(),c.return());a.i&&(a.i=0,a.Ea());c.h=0})},this.Ob))};
n.rb=function(){this.V.U(this.i);this.i=0};
function Ul(a,b){var c,d;return x(function(e){switch(e.h){case 1:if(!a.v)throw c=Nk("immediateSend"),c;if(void 0===b.id){e.s(2);break}return v(e,a.J.fc(b.id,a.v),3);case 3:(d=e.i)?b=d:a.va(Error("The request cannot be found in the database."));case 2:if(Wl(a,b,a.Jb)){e.s(4);break}a.va(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===b.id){e.s(5);break}return v(e,a.J.ta(b.id,a.v),5);case 5:return e.return();case 4:b.skipRetry||(b=Xl(a,b));if(!b){e.s(0);break}if(!b.skipRetry||
void 0===b.id){e.s(8);break}return v(e,a.J.ta(b.id,a.v),8);case 8:a.ea(b.url,b.options,!!b.skipRetry),e.h=0}})}
function Xl(a,b){if(!a.v)throw Nk("updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g;return x(function(h){switch(h.h){case 1:g=Yl(f);if(!(a.C&&a.C("nwl_consider_error_code")&&g||a.C&&!a.C("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.Ua)){h.s(2);break}if(!a.I.fa){h.s(3);break}return v(h,a.I.fa(),3);case 3:if(a.I.G()){h.s(2);break}c(e,f);if(!a.C||!a.C("nwl_consider_error_code")||void 0===(null===b||void 0===b?void 0:b.id)){h.s(6);break}return v(h,a.J.nb(b.id,a.v,!1),6);case 6:return h.return();case 2:if(a.C&&a.C("nwl_consider_error_code")&&
!g&&a.potentialEsfErrorCounter>a.Ua)return h.return();a.potentialEsfErrorCounter++;if(void 0===(null===b||void 0===b?void 0:b.id)){h.s(8);break}return b.sendCount<a.Lb?v(h,a.J.nb(b.id,a.v),12):v(h,a.J.ta(b.id,a.v),8);case 12:a.V.M(function(){a.I.G()&&a.Ea()},a.Kb);
case 8:c(e,f),h.h=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){return x(function(g){if(1==g.h)return void 0===(null===b||void 0===b?void 0:b.id)?g.s(2):v(g,a.J.ta(b.id,a.v),2);a.I.ca&&a.C&&a.C("vss_network_hint")&&a.I.ca(!0);d(e,f);g.h=0})};
return b}
function Wl(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function Tl(a){if(!a.v)throw Nk("retryQueuedRequests");a.J.Ab("QUEUED",a.v).then(function(b){b&&!Wl(a,b,a.Hb)?a.V.M(function(){return x(function(c){if(1==c.h)return void 0===b.id?c.s(2):v(c,a.J.nb(b.id,a.v),2);Tl(a);c.h=0})}):a.I.G()&&a.Ea()})}
function Vl(a,b){a.Pb&&!a.I.G()?a.Pb(b):a.handleError(b)}
function Yl(a){var b;return(a=null===(b=null===a||void 0===a?void 0:a.error)||void 0===b?void 0:b.code)&&400<=a&&599>=a?!1:!0}
;function Zl(a,b){this.version=a;this.args=b}
;function $l(a,b){this.topic=a;this.h=b}
$l.prototype.toString=function(){return this.topic};var am=C("ytPubsub2Pubsub2Instance")||new K;K.prototype.subscribe=K.prototype.subscribe;K.prototype.unsubscribeByKey=K.prototype.ya;K.prototype.publish=K.prototype.ma;K.prototype.clear=K.prototype.clear;A("ytPubsub2Pubsub2Instance",am,void 0);var bm=C("ytPubsub2Pubsub2SubscribedKeys")||{};A("ytPubsub2Pubsub2SubscribedKeys",bm,void 0);var cm=C("ytPubsub2Pubsub2TopicToKeys")||{};A("ytPubsub2Pubsub2TopicToKeys",cm,void 0);var dm=C("ytPubsub2Pubsub2IsAsync")||{};A("ytPubsub2Pubsub2IsAsync",dm,void 0);
A("ytPubsub2Pubsub2SkipSubKey",null,void 0);function em(a,b){var c=fm();c&&c.publish.call(c,a.toString(),a,b)}
function gm(a){var b=hm,c=fm();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=C("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(bm[d])try{if(f&&b instanceof $l&&b!=e)try{var h=b.h,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.la){var l=new h;h.la=l.version}var m=h.la}catch(q){}if(!m||k.version!=m)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{f=Reflect.construct(h,
jb(k.args))}catch(q){throw q.message="yt.pubsub2.Data.deserialize(): "+q.message,q;}}catch(q){throw q.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+q.message,q;}a.call(window,f)}catch(q){Bh(q)}},dm[b.toString()]?C("yt.scheduler.instance")?Wh.M(g):Mh(g,0):g())});
bm[d]=!0;cm[b.toString()]||(cm[b.toString()]=[]);cm[b.toString()].push(d);return d}
function im(){var a=jm,b=gm(function(c){a.apply(void 0,arguments);km(b)});
return b}
function km(a){var b=fm();b&&("number"===typeof a&&(a=[a]),db(a,function(c){b.unsubscribeByKey(c);delete bm[c]}))}
function fm(){return C("ytPubsub2Pubsub2Instance")}
;function lm(a,b){sl.call(this,a,b);this.options=b;Bk(a)}
u(lm,sl);function mm(a,b){var c;return function(){c||(c=new lm(a,b));return c}}
lm.prototype.j=function(a,b,c){c=void 0===c?{}:c;return(this.options.ob?Ml:Ll)(a,b,Object.assign({},c))};
lm.prototype.delete=function(a){a=void 0===a?{}:a;return(this.options.ob?Ql:Nl)(this.name,a)};
function nm(a,b){return mm(a,b)}
;var om;
function pm(){if(om)return om();var a={};om=nm("LogsDatabaseV2",{Ba:(a.LogsRequestsStore={Za:2},a),ob:!1,upgrade:function(b,c,d){c(2)&&bl(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.h.indexNames.contains("newRequest")&&d.h.deleteIndex("newRequest"),d.h.createIndex("newRequestV2",["status","interface","timestamp"],{unique:!1}));c(7)&&b.h.objectStoreNames.contains("sapisid")&&b.h.deleteObjectStore("sapisid");c(9)&&b.h.objectStoreNames.contains("SWHealthLog")&&b.h.deleteObjectStore("SWHealthLog")},
version:9});return om()}
;function qm(a){return ul(pm(),a)}
function rm(a,b){var c,d,e,f;return x(function(g){if(1==g.h)return c={startTime:O(),transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},v(g,qm(b),2);if(3!=g.h)return d=g.i,e=Object.assign(Object.assign({},a),{options:JSON.parse(JSON.stringify(a.options)),interface:D("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),v(g,dl(d,e),3);f=g.i;c.Ec=O();sm(c);return g.return(f)})}
function tm(a,b){var c,d,e,f,g,h,k;return x(function(l){if(1==l.h)return c={startTime:O(),transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},v(l,qm(b),2);if(3!=l.h)return d=l.i,e=D("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,O()],h=IDBKeyRange.bound(f,g),k=void 0,v(l,al(d,["LogsRequestsStore"],{mode:"readwrite",O:!0},function(m){return ml(m.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:"prev"},function(q){q.getValue()&&(k=q.getValue(),"NEW"===a&&(k.status="QUEUED",
q.update(k)))})}),3);
c.Ec=O();sm(c);return l.return(k)})}
function um(a,b){var c;return x(function(d){if(1==d.h)return v(d,qm(b),2);c=d.i;return d.return(al(c,["LogsRequestsStore"],{mode:"readwrite",O:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",Yk(f.h.put(g,void 0)).then(function(){return g})})}))})}
function vm(a,b,c){c=void 0===c?!0:c;var d;return x(function(e){if(1==e.h)return v(e,qm(b),2);d=e.i;return e.return(al(d,["LogsRequestsStore"],{mode:"readwrite",O:!0},function(f){var g=f.objectStore("LogsRequestsStore");return g.get(a).then(function(h){return h?(h.status="NEW",c&&(h.sendCount+=1),Yk(g.h.put(h,void 0)).then(function(){return h})):Rk.resolve(void 0)})}))})}
function wm(a,b){var c;return x(function(d){if(1==d.h)return v(d,qm(b),2);c=d.i;return d.return(c.delete("LogsRequestsStore",a))})}
function xm(a){var b,c;return x(function(d){if(1==d.h)return v(d,qm(a),2);b=d.i;c=O()-2592E6;return v(d,al(b,["LogsRequestsStore"],{mode:"readwrite",O:!0},function(e){return jl(e.objectStore("LogsRequestsStore"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function ym(){return x(function(a){return v(a,Pl(),0)})}
function sm(a){M("nwl_csi_killswitch")||.01>=Math.random()&&em("nwl_transaction_latency_payload",a)}
;var zm={},Am=nm("ServiceWorkerLogsDatabase",{Ba:(zm.SWHealthLog={Za:1},zm),ob:!0,upgrade:function(a,b){b(1)&&bl(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}).h.createIndex("swHealthNewRequest",["interface","timestamp"],{unique:!1})},
version:1});function Bm(a){return ul(Am(),a)}
function Cm(a){var b,c;return x(function(d){if(1==d.h)return v(d,Bm(a),2);b=d.i;c=O()-2592E6;return v(d,al(b,["SWHealthLog"],{mode:"readwrite",O:!0},function(e){return jl(e.objectStore("SWHealthLog"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function Dm(a){var b;return x(function(c){if(1==c.h)return v(c,Bm(a),2);b=c.i;return v(c,b.clear("SWHealthLog"),0)})}
;function Em(){this.h=new Map;this.i=!1}
function Fm(){if(!Em.h){var a=C("yt.networkRequestMonitor.instance")||new Em;A("yt.networkRequestMonitor.instance",a,void 0);Em.h=a}return Em.h}
Em.prototype.requestComplete=function(a,b){b&&(this.i=!0);a=this.removeParams(a);this.h.get(a)||this.h.set(a,b)};
Em.prototype.isEndpointCFR=function(a){a=this.removeParams(a);return(a=this.h.get(a))?!1:!1===a&&this.i?!0:null};
Em.prototype.removeParams=function(a){return a.split("?")[0]};
Em.prototype.removeParams=Em.prototype.removeParams;Em.prototype.isEndpointCFR=Em.prototype.isEndpointCFR;Em.prototype.requestComplete=Em.prototype.requestComplete;Em.getInstance=Fm;var Gm;function Hm(){Gm||(Gm=new ik("yt.offline"));return Gm}
function Im(a){if(M("offline_error_handling")){var b=Hm().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);Hm().set("errors",b,2592E3,!0)}}
function Jm(){if(M("offline_error_handling")){var a=Hm().get("errors",!0);if(a){for(var b in a)if(a[b]){var c=new yk(b,"sent via offline_errors");c.name=a[b].name;c.stack=a[b].stack;c.level=a[b].level;Bh(c)}Hm().set("errors",{},2592E3,!0)}}}
;var Km=rh("network_polling_interval",3E4);function S(){Fe.call(this);this.L=0;this.S=this.m=!1;this.l=this.fb();M("use_shared_nsm")?(Ie.h||(Ie.h=new Ie(Wh)),this.j=Ie.h):(Lm(this),Mm(this))}
u(S,Fe);function Nm(){if(!S.h){var a=C("yt.networkStatusManager.instance")||new S;A("yt.networkStatusManager.instance",a,void 0);S.h=a}return S.h}
n=S.prototype;n.G=function(){var a;return M("use_shared_nsm")&&this.j?null===(a=this.j)||void 0===a?void 0:a.G():this.l};
n.ca=function(a){var b;M("use_shared_nsm")&&this.j?null===(b=this.j)||void 0===b?void 0:b.j=a:a!==this.l&&(this.l=a)};
n.hc=function(a){!M("use_shared_nsm")&&(this.m=!0,void 0===a?0:a)&&(this.L||Om(this))};
n.fb=function(){var a=window.navigator.onLine;return void 0===a?!0:a};
n.Xb=function(){this.S=!0};
n.ba=function(a,b){return M("use_shared_nsm")&&this.j?this.j.ba(a,b):Fe.prototype.ba.call(this,a,b)};
function Mm(a){window.addEventListener("online",function(){return x(function(b){if(1==b.h)return v(b,a.fa(),2);a.S&&Jm();b.h=0})})}
function Lm(a){window.addEventListener("offline",function(){return x(function(b){return v(b,a.fa(),0)})})}
function Om(a){a.L=Qh(function(){return x(function(b){if(1==b.h)return a.l?a.fb()||!a.m?b.s(3):v(b,a.fa(),3):v(b,a.fa(),3);Om(a);b.h=0})},Km)}
n.fa=function(a){var b=this;if(M("use_shared_nsm")&&this.j){var c=Je(this.j,a);c.then(function(d){M("use_cfr_monitor")&&Fm().requestComplete("generate_204",d)});
return c}return this.u?this.u:this.u=new Promise(function(d){var e,f,g;return x(function(h){switch(h.h){case 1:return e=window.AbortController?new window.AbortController:void 0,f=null===e||void 0===e?void 0:e.signal,g=!1,ta(h,2,3),e&&(b.A=Wh.M(function(){e.abort()},a||2E4)),v(h,fetch("/generate_204",{method:"HEAD",
signal:f}),5);case 5:g=!0;case 3:wa(h);M("use_cfr_monitor")&&Fm().requestComplete("generate_204",g);b.u=void 0;b.A&&Wh.U(b.A);g!==b.l&&(b.l=g,b.l&&b.m?Ge(b,"ytnetworkstatus-online"):b.m&&Ge(b,"ytnetworkstatus-offline"));d(g);xa(h);break;case 2:va(h),g=!1,h.s(3)}})})};
S.prototype.sendNetworkCheckRequest=S.prototype.fa;S.prototype.listen=S.prototype.ba;S.prototype.enableErrorFlushing=S.prototype.Xb;S.prototype.getWindowStatus=S.prototype.fb;S.prototype.monitorNetworkStatusChange=S.prototype.hc;S.prototype.networkStatusHint=S.prototype.ca;S.prototype.isNetworkAvailable=S.prototype.G;S.getInstance=Nm;function Pm(a){a=void 0===a?{}:a;Fe.call(this);var b=this;this.l=this.L=0;this.m="ytnetworkstatus-offline";this.u="ytnetworkstatus-online";M("use_shared_nsm")&&(this.m="networkstatus-offline",this.u="networkstatus-online");this.j=Nm();var c=C("yt.networkStatusManager.instance.monitorNetworkStatusChange").bind(this.j);c&&c(a.xb);a.Ra&&!M("use_shared_nsm")&&(c=C("yt.networkStatusManager.instance.enableErrorFlushing").bind(this.j))&&c();if(c=C("yt.networkStatusManager.instance.listen").bind(this.j))a.Wa?
(this.Wa=a.Wa,c(this.u,function(){Qm(b,"publicytnetworkstatus-online");M("use_shared_nsm")&&a.Ra&&Jm()}),c(this.m,function(){Qm(b,"publicytnetworkstatus-offline")})):(c(this.u,function(){Ge(b,"publicytnetworkstatus-online");
M("use_shared_nsm")&&a.Ra&&Jm()}),c(this.m,function(){Ge(b,"publicytnetworkstatus-offline")}))}
u(Pm,Fe);Pm.prototype.G=function(){var a=C("yt.networkStatusManager.instance.isNetworkAvailable");return a?a.bind(this.j)():!0};
Pm.prototype.ca=function(a){var b=C("yt.networkStatusManager.instance.networkStatusHint").bind(this.j);b&&b(a)};
Pm.prototype.fa=function(a){var b=this,c;return x(function(d){c=C("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.j);return M("skip_network_check_if_cfr")&&Fm().isEndpointCFR("generate_204")?d.return(new Promise(function(e){var f;b.ca((null===(f=window.navigator)||void 0===f?void 0:f.onLine)||!0);e(b.G())})):c?d.return(c(a)):d.return(!0)})};
function Qm(a,b){a.Wa?a.l?(Wh.U(a.L),a.L=Wh.M(function(){a.A!==b&&(Ge(a,b),a.A=b,a.l=O())},a.Wa-(O()-a.l))):(Ge(a,b),a.A=b,a.l=O()):Ge(a,b)}
;var Rm;function Sm(){Rl.call(this,{J:{Ub:xm,ta:wm,Ab:tm,fc:um,nb:vm,set:rm},I:Tm(),handleError:Bh,va:Ch,ea:Um,now:O,Pb:Im,V:Vh(),mb:"publicytnetworkstatus-online",lb:"publicytnetworkstatus-offline",Oa:!0,Na:.1,Ua:rh("potential_esf_error_limit",10),C:M,Aa:!zk()});this.j=new id;this.Oa&&Math.random()<=this.Na&&this.v&&Cm(this.v);M("networkless_immediately_drop_sw_health_store")&&Vm(this);M("networkless_immediately_drop_all_requests")&&ym();Ql("LogsDatabaseV2")}
u(Sm,Rl);function Wm(){var a=C("yt.networklessRequestController.instance");a||(a=new Sm,A("yt.networklessRequestController.instance",a,void 0),M("networkless_logging")&&Gl().then(function(b){return x(function(c){if(1==c.h)return a.v=b,v(c,Sl(a),2);a.j.resolve();c.h=0})}));
return a}
Sm.prototype.writeThenSend=function(a,b){b||(b={});zk()||(this.h=!1);Rl.prototype.writeThenSend.call(this,a,b)};
Sm.prototype.sendThenWrite=function(a,b,c){b||(b={});zk()||(this.h=!1);Rl.prototype.sendThenWrite.call(this,a,b,c)};
Sm.prototype.sendAndWrite=function(a,b){b||(b={});zk()||(this.h=!1);Rl.prototype.sendAndWrite.call(this,a,b)};
Sm.prototype.awaitInitialization=function(){return this.j.promise};
function Vm(a){var b;x(function(c){if(!a.v)throw b=Nk("clearSWHealthLogsDb"),b;return c.return(Dm(a.v).catch(function(d){a.handleError(d)}))})}
function Um(a,b,c){M("use_cfr_monitor")&&Xm(a,b);var d;if(null===(d=b.postParams)||void 0===d?0:d.requestTimeMs)b.postParams.requestTimeMs=Math.round(O());c&&0===Object.keys(b).length?Ki(a):yi(a,b)}
function Tm(){Rm||(Rm=new Pm({Ra:!0,xb:!0}));return Rm}
function Xm(a,b){var c=b.onError?b.onError:function(){};
b.onError=function(e,f){Fm().requestComplete(a,!1);c(e,f)};
var d=b.onSuccess?b.onSuccess:function(){};
b.onSuccess=function(e,f){Fm().requestComplete(a,!0);d(e,f)}}
;var Ym=!1,Zm=0,$m=0,an,bn=y.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:Ym,potentialEsfErrorCounter:$m};A("ytNetworklessLoggingInitializationOptions",bn,void 0);
function cn(){var a;x(function(b){switch(b.h){case 1:return v(b,Gl(),2);case 2:a=b.i;if(!a||!zk()&&!M("nwl_init_require_datasync_id_killswitch")){b.s(0);break}Ym=!0;bn.isNwlInitialized=Ym;return v(b,Ql("LogsDatabaseV2"),4);case 4:if(!(.1>=Math.random())){b.s(5);break}return v(b,xm(a),6);case 6:return v(b,Cm(a),5);case 5:dn();en().G()&&fn();en().ba("publicytnetworkstatus-online",fn);en().ba("publicytnetworkstatus-offline",gn);if(!M("networkless_immediately_drop_sw_health_store")){b.s(8);break}return v(b,
hn(),8);case 8:if(M("networkless_immediately_drop_all_requests"))return v(b,ym(),0);b.s(0)}})}
function jn(a,b){function c(d){var e=en().G();if(!kn()||!d||e&&M("vss_networkless_bypass_write"))ln(a,b);else{var f={url:a,options:b,timestamp:O(),status:"NEW",sendCount:0};rm(f,d).then(function(g){f.id=g;en().G()&&mn(f)}).catch(function(g){mn(f);
en().G()?Bh(g):Im(g)})}}
b=void 0===b?{}:b;M("skip_is_supported_killswitch")?Gl().then(function(d){c(d)}):c(Fl())}
function nn(a,b){function c(d){if(kn()&&d){var e={url:a,options:b,timestamp:O(),status:"NEW",sendCount:0},f=!1,g=b.onSuccess?b.onSuccess:function(){};
e.options.onSuccess=function(k,l){M("use_cfr_monitor")&&Fm().requestComplete(e.url,!0);void 0!==e.id?wm(e.id,d):f=!0;M("vss_network_hint")&&en().ca(!0);g(k,l)};
if(M("use_cfr_monitor")){var h=b.onError?b.onError:function(){};
e.options.onError=function(k,l){Fm().requestComplete(e.url,!1);h(k,l)}}ln(e.url,e.options);
rm(e,d).then(function(k){e.id=k;f&&wm(e.id,d)}).catch(function(k){en().G()?Bh(k):Im(k)})}else ln(a,b)}
b=void 0===b?{}:b;M("skip_is_supported_killswitch")?Gl().then(function(d){c(d)}):c(Fl())}
function fn(){var a=Fl();if(!a)throw Nk("throttleSend");Zm||(Zm=Wh.M(function(){var b;return x(function(c){if(1==c.h)return v(c,tm("NEW",a),2);if(3!=c.h)return b=c.i,b?v(c,mn(b),3):(gn(),c.return());Zm&&(Zm=0,fn());c.h=0})},100))}
function gn(){Wh.U(Zm);Zm=0}
function mn(a){var b,c,d;return x(function(e){switch(e.h){case 1:b=Fl();if(!b)throw c=Nk("immediateSend"),c;if(void 0===a.id){e.s(2);break}return v(e,um(a.id,b),3);case 3:(d=e.i)?a=d:Ch(Error("The request cannot be found in the database."));case 2:if(on(a,2592E6)){e.s(4);break}Ch(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===a.id){e.s(5);break}return v(e,wm(a.id,b),5);case 5:return e.return();case 4:a.skipRetry||(a=pn(a));var f=a,g,h;if(null===(h=null===(g=null===
f||void 0===f?void 0:f.options)||void 0===g?void 0:g.postParams)||void 0===h?0:h.requestTimeMs)f.options.postParams.requestTimeMs=Math.round(O());a=f;if(!a){e.s(0);break}if(!a.skipRetry||void 0===a.id){e.s(8);break}return v(e,wm(a.id,b),8);case 8:ln(a.url,a.options,!!a.skipRetry),e.h=0}})}
function pn(a){var b=Fl();if(!b)throw Nk("updateRequestHandlers");var c=a.options.onError?a.options.onError:function(){};
a.options.onError=function(e,f){var g;return x(function(h){switch(h.h){case 1:M("use_cfr_monitor")&&Fm().requestComplete(a.url,!1);g=Yl(f);if(!(M("nwl_consider_error_code")&&g||!M("nwl_consider_error_code")&&qn()<=rh("potential_esf_error_limit",10))){h.s(2);break}if(M("skip_checking_network_on_cfr_failure")&&(!M("skip_checking_network_on_cfr_failure")||Fm().isEndpointCFR(a.url))){h.s(3);break}return v(h,en().fa(),3);case 3:if(en().G()){h.s(2);break}c(e,f);if(!M("nwl_consider_error_code")||void 0===
(null===a||void 0===a?void 0:a.id)){h.s(6);break}return v(h,vm(a.id,b,!1),6);case 6:return h.return();case 2:if(M("nwl_consider_error_code")&&!g&&qn()>rh("potential_esf_error_limit",10))return h.return();C("ytNetworklessLoggingInitializationOptions")&&bn.potentialEsfErrorCounter++;$m++;if(void 0===(null===a||void 0===a?void 0:a.id)){h.s(8);break}return 1>a.sendCount?v(h,vm(a.id,b),12):v(h,wm(a.id,b),8);case 12:Wh.M(function(){en().G()&&fn()},5E3);
case 8:c(e,f),h.h=0}})};
var d=a.options.onSuccess?a.options.onSuccess:function(){};
a.options.onSuccess=function(e,f){return x(function(g){if(1==g.h)return M("use_cfr_monitor")&&Fm().requestComplete(a.url,!0),void 0===(null===a||void 0===a?void 0:a.id)?g.s(2):v(g,wm(a.id,b),2);M("vss_network_hint")&&en().ca(!0);d(e,f);g.h=0})};
return a}
function on(a,b){a=a.timestamp;return O()-a>=b?!1:!0}
function dn(){var a=Fl();if(!a)throw Nk("retryQueuedRequests");tm("QUEUED",a).then(function(b){b&&!on(b,12E4)?Wh.M(function(){return x(function(c){if(1==c.h)return void 0===b.id?c.s(2):v(c,vm(b.id,a),2);dn();c.h=0})}):en().G()&&fn()})}
function hn(){var a,b;return x(function(c){a=Fl();if(!a)throw b=Nk("clearSWHealthLogsDb"),b;return c.return(Dm(a).catch(function(d){Bh(d)}))})}
function en(){if(M("use_new_nwl"))return Tm();an||(an=new Pm({Ra:!0,xb:!0}));return an}
function ln(a,b,c){c&&0===Object.keys(b).length?Ki(a):yi(a,b)}
function kn(){return C("ytNetworklessLoggingInitializationOptions")?bn.isNwlInitialized:Ym}
function qn(){return C("ytNetworklessLoggingInitializationOptions")?bn.potentialEsfErrorCounter:$m}
;function rn(a){var b=this;this.config_=null;a?this.config_=a:ak()&&(this.config_=uj());Qh(function(){nk(b)},5E3)}
rn.prototype.isReady=function(){!this.config_&&ak()&&(this.config_=uj());return!!this.config_};
function yj(a,b,c,d){function e(z){z=void 0===z?!1:z;var B;if(d.retry&&"www.youtube-nocookie.com"!=h&&(z||M("skip_ls_gel_retry")||"application/json"!==g.headers["Content-Type"]||(B=lk(b,c,l,k)),B)){var I=g.onSuccess,L=g.onFetchSuccess;g.onSuccess=function(N,R){mk(B);I(N,R)};
c.onFetchSuccess=function(N,R){mk(B);L(N,R)}}try{z&&d.retry&&!d.Fb.bypassNetworkless?(g.method="POST",d.Fb.writeThenSend?M("use_new_nwl")?Wm().writeThenSend(t,g):jn(t,g):M("use_new_nwl")?Wm().sendAndWrite(t,g):nn(t,g)):(g.method="POST",g.postParams||(g.postParams={}),yi(t,g))}catch(N){if("InvalidAccessError"==N.name)B&&(mk(B),B=0),Ch(Error("An extension is blocking network request."));
else throw N;}B&&Qh(function(){nk(a)},5E3)}
!D("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&Ch(new yk("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new yk("innertube xhrclient not ready",b,c,d);Bh(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(z,B){if(d.onSuccess)d.onSuccess(B)},
onFetchSuccess:function(z){if(d.onSuccess)d.onSuccess(z)},
onError:function(z,B){if(d.onError)d.onError(B)},
onFetchError:function(z){if(d.onError)d.onError(z)},
timeout:d.timeout,withCredentials:!0};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.cc)&&(h=f);var k=a.config_.ec||!1,l=gk(k,h,d);Object.assign(g.headers,l);(f=g.headers.Authorization)&&!h&&(g.headers["x-origin"]=window.location.origin);var m="/youtubei/"+a.config_.innertubeApiVersion+"/"+b,q={alt:"json"},w=a.config_.dc&&f;w=w&&f.startsWith("Bearer");w||(q.key=a.config_.innertubeApiKey);var t=mi(""+h+m,q||{},!0);M("use_new_nwl")&&Wm().h||!M("use_new_nwl")&&
kn()?El().then(function(z){e(z)}):e(!1)}
;function P(a,b,c){c=void 0===c?{}:c;var d=rn;D("ytLoggingEventsDefaultDisabled",!1)&&rn==rn&&(d=null);Fj(a,b,d,c)}
;var sn=[{kb:function(a){return"Cannot read property '"+a.key+"'"},
Ta:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{kb:function(a){return"Cannot call '"+a.key+"'"},
Ta:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{kb:function(a){return a.key+" is not defined"},
Ta:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var un={ka:[],ha:[{na:tn,weight:500}]};function tn(a){if("JavaException"===a.name)return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function vn(){this.ha=[];this.ka=[]}
var wn;function xn(){if(!wn){var a=wn=new vn;a.ka.length=0;a.ha.length=0;un.ka&&a.ka.push.apply(a.ka,un.ka);un.ha&&a.ha.push.apply(a.ha,un.ha)}return wn}
;var yn=new K;function zn(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=An(b);if(Infinity===e)break;var f=e>>3;switch(e&7){case 0:e=An(b);if(2===f)return e;break;case 1:if(2===f)return;d+=8;break;case 2:e=An(b);if(2===f)return a.substr(d,e);d+=e;break;case 5:if(2===f)return;d+=4;break;default:return}}while(d<c)}
function An(a){var b=a(),c=b&127;if(128>b)return c;b=a();c|=(b&127)<<7;if(128>b)return c;b=a();c|=(b&127)<<14;if(128>b)return c;b=a();return 128>b?c|(b&127)<<21:Infinity}
;function Bn(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=Cn(d,a[d],b,c),500<e));d++);d=e}else if("object"===typeof a)for(e in a){if(a[e]){var f=a[e];var g=b;var h=c;g="string"!==typeof f||"clickTrackingParams"!==e&&"trackingParams"!==e?0:(f=zn(atob(f.replace(/-/g,"+").replace(/_/g,"/"))))?Cn(e+".ve",f,g,h):0;d+=g;d+=Cn(e,a[e],b,c);if(500<d)break}}else c[b]=Dn(a),d+=c[b].length;else c[b]=Dn(a),d+=c[b].length;return d}
function Cn(a,b,c,d){c+="."+a;a=Dn(b);d[c]=a;return c.length+a.length}
function Dn(a){try{return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;var En=new Set,Fn=0,Gn=0,Hn=0,In=[],Jn=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function vk(a){Kn(a)}
function T(a){Kn(a,"WARNING")}
function Kn(a,b,c,d,e,f){f=void 0===f?{}:f;f.name=c||D("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||D("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0);c=f||{};b=void 0===b?"ERROR":b;b=void 0===b?"ERROR":b;if(a&&(a.hasOwnProperty("level")&&a.level&&(b=a.level),M("console_log_js_exceptions")&&(d=[],d.push("Name: "+a.name),d.push("Message: "+a.message),a.hasOwnProperty("params")&&d.push("Error Params: "+JSON.stringify(a.params)),a.hasOwnProperty("args")&&d.push("Error args: "+JSON.stringify(a.args)),d.push("File name: "+
a.fileName),d.push("Stacktrace: "+a.stack),window.console.log(d.join("\n"),a)),!(5<=Fn))){d=In;var g=de(a);e=g.message||"Unknown Error";f=g.name||"UnknownError";var h=g.stack||a.i||"Not available";if(h.startsWith(f+": "+e)){var k=h.split("\n");k.shift();h=k.join("\n")}k=g.lineNumber||"Not available";g=g.fileName||"Not available";var l=0;if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var m=0;m<a.args.length&&!(l=Bn(a.args[m],"params."+m,c,l),500<=l);m++);else if(a.hasOwnProperty("params")&&
a.params){var q=a.params;if("object"===typeof a.params)for(m in q){if(q[m]){var w="params."+m,t=Dn(q[m]);c[w]=t;l+=w.length+t.length;if(500<l)break}}else c.params=Dn(q)}if(d.length)for(m=0;m<d.length&&!(l=Bn(d[m],"params.context."+m,c,l),500<=l);m++);navigator.vendor&&!c.hasOwnProperty("vendor")&&(c["device.vendor"]=navigator.vendor);m={message:e,name:f,lineNumber:k,fileName:g,stack:h,params:c,sampleWeight:1};c=Number(a.columnNumber);isNaN(c)||(m.lineNumber=m.lineNumber+":"+c);if("IGNORED"===a.level)a=
0;else a:{a=xn();c=r(a.ka);for(d=c.next();!d.done;d=c.next())if(d=d.value,m.message&&m.message.match(d.xo)){a=d.weight;break a}a=r(a.ha);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.na(m)){a=c.weight;break a}a=1}m.sampleWeight=a;a=r(sn);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.Ta[m.name])for(e=r(c.Ta[m.name]),d=e.next();!d.done;d=e.next())if(f=d.value,d=m.message.match(f.regexp)){m.params["params.error.original"]=d[0];e=f.groups;f={};for(k=0;k<e.length;k++)f[e[k]]=d[k+1],m.params["params.error."+
e[k]]=d[k+1];m.message=c.kb(f);break}m.params||(m.params={});a=xn();m.params["params.errorServiceSignature"]="msg="+a.ka.length+"&cb="+a.ha.length;m.params["params.serviceWorker"]="false";y.document&&y.document.querySelectorAll&&(m.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));Ab("sample").constructor!==yb&&(m.params["params.fconst"]="true");window.yterr&&"function"===typeof window.yterr&&window.yterr(m);if(0!==m.sampleWeight&&!En.has(m.message)){"ERROR"===
b?(yn.ma("handleError",m),M("record_app_crashed_web")&&0===Hn&&1===m.sampleWeight&&(Hn++,a={appCrashType:"APP_CRASH_TYPE_BREAKPAD"},M("report_client_error_with_app_crash_ks")||(a.systemHealth={crashData:{clientError:{logMessage:{message:m.message}}}}),P("appCrashed",a)),Gn++):"WARNING"===b&&yn.ma("handleWarning",m);if(M("kevlar_gel_error_routing")){a=b;b:{c=r(Jn);for(d=c.next();!d.done;d=c.next())if(Hi(d.value.toLowerCase())){c=!0;break b}c=!1}if(c)c=void 0;else{d={stackTrace:m.stack};m.fileName&&
(d.filename=m.fileName);c=m.lineNumber&&m.lineNumber.split?m.lineNumber.split(":"):[];0!==c.length&&(1!==c.length||isNaN(Number(c[0]))?2!==c.length||isNaN(Number(c[0]))||isNaN(Number(c[1]))||(d.lineNumber=Number(c[0]),d.columnNumber=Number(c[1])):d.lineNumber=Number(c[0]));c={level:"ERROR_LEVEL_UNKNOWN",message:m.message,errorClassName:m.name,sampleWeight:m.sampleWeight};"ERROR"===a?c.level="ERROR_LEVEL_ERROR":"WARNING"===a&&(c.level="ERROR_LEVEL_WARNNING");d={isObfuscated:!0,browserStackInfo:d};
e={pageUrl:window.location.href,kvPairs:[]};D("FEXP_EXPERIMENTS")&&(e.experimentIds=D("FEXP_EXPERIMENTS"));f=D("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS",void 0);k=jh.EXPERIMENT_FLAGS;if((!k||!k.web_disable_gel_stp_ecatcher_killswitch)&&f)for(g=r(Object.keys(f)),k=g.next();!k.done;k=g.next())k=k.value,e.kvPairs.push({key:k,value:String(f[k])});if(f=m.params)for(g=r(Object.keys(f)),k=g.next();!k.done;k=g.next())k=k.value,e.kvPairs.push({key:"client."+k,value:String(f[k])});f=D("SERVER_NAME",void 0);
k=D("SERVER_VERSION",void 0);f&&k&&(e.kvPairs.push({key:"server.name",value:f}),e.kvPairs.push({key:"server.version",value:k}));c={errorMetadata:e,stackTrace:d,logMessage:c}}c&&(P("clientError",c),("ERROR"===a||M("errors_flush_gel_always_killswitch"))&&nj())}if(!M("suppress_error_204_logging")){a=m.params||{};b={urlParams:{a:"logerror",t:"jserror",type:m.name,msg:m.message.substr(0,250),line:m.lineNumber,level:b,"client.name":a.name},postParams:{url:D("PAGE_NAME",window.location.href),file:m.fileName},
method:"POST"};a.version&&(b["client.version"]=a.version);if(b.postParams){m.stack&&(b.postParams.stack=m.stack);c=r(Object.keys(a));for(d=c.next();!d.done;d=c.next())d=d.value,b.postParams["client."+d]=a[d];if(a=D("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS",void 0))for(c=r(Object.keys(a)),d=c.next();!d.done;d=c.next())d=d.value,b.postParams[d]=a[d];a=D("SERVER_NAME",void 0);c=D("SERVER_VERSION",void 0);a&&c&&(b.postParams["server.name"]=a,b.postParams["server.version"]=c)}yi(D("ECATCHER_REPORT_HOST",
"")+"/error_204",b)}try{En.add(m.message)}catch(z){}Fn++}}}
function Ln(a){var b=Ea.apply(1,arguments),c=a;c.args||(c.args=[]);c.args.push.apply(c.args,ia(b))}
;function Mn(){this.register=new Map}
function Nn(a){a=r(a.register.values());for(var b=a.next();!b.done;b=a.next())b.value.Ao("ABORTED")}
Mn.prototype.clear=function(){Nn(this);this.register.clear()};
var On=new Mn;var Pn=Date.now().toString();
function Qn(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;16>a;a++){b=Date.now();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(256*Math.random())}if(Pn)for(a=1,b=0;b<Pn.length;b++)d[a%16]=d[a%16]^d[(a-1)%16]/4^Pn.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var Rn,Sn=y.ytLoggingDocDocumentNonce_;Sn||(Sn=Qn(),Wa("ytLoggingDocDocumentNonce_",Sn));Rn=Sn;var Tn={og:0,rd:1,zd:2,Pj:3,qg:4,Kn:5,Fk:6,em:7,Gl:8,0:"DEFAULT",1:"CHAT",2:"CONVERSATIONS",3:"MINIPLAYER",4:"DIALOG",5:"VOZ",6:"MUSIC_WATCH_TABS",7:"SHARE",8:"PUSH_NOTIFICATIONS"};function Un(a){this.h=a}
function Vn(a){return new Un({trackingParams:a})}
Un.prototype.getAsJson=function(){var a={};void 0!==this.h.trackingParams?a.trackingParams=this.h.trackingParams:(a.veType=this.h.veType,void 0!==this.h.veCounter&&(a.veCounter=this.h.veCounter),void 0!==this.h.elementIndex&&(a.elementIndex=this.h.elementIndex));void 0!==this.h.dataElement&&(a.dataElement=this.h.dataElement.getAsJson());void 0!==this.h.youtubeData&&(a.youtubeData=this.h.youtubeData);return a};
Un.prototype.getAsJspb=function(){var a=new Fg;void 0!==this.h.trackingParams?G(a,1,this.h.trackingParams):(void 0!==this.h.veType&&G(a,2,this.h.veType),void 0!==this.h.veCounter&&G(a,6,this.h.veCounter),void 0!==this.h.elementIndex&&G(a,3,this.h.elementIndex));if(void 0!==this.h.dataElement){var b=this.h.dataElement.getAsJspb();H(a,7,b)}return a};
Un.prototype.toString=function(){return JSON.stringify(this.getAsJson())};
Un.prototype.isClientVe=function(){return!this.h.trackingParams&&!!this.h.veType};function Wn(a){a=void 0===a?0:a;return 0==a?"client-screen-nonce":"client-screen-nonce."+a}
function Xn(a){a=void 0===a?0:a;return 0==a?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function Yn(a){return D(Xn(void 0===a?0:a),void 0)}
A("yt_logging_screen.getRootVeType",Yn,void 0);function Zn(a){return(a=Yn(void 0===a?0:a))?new Un({veType:a,youtubeData:void 0}):null}
function $n(){var a=D("csn-to-ctt-auth-info");a||(a={},ph("csn-to-ctt-auth-info",a));return a}
function ao(a){a=void 0===a?0:a;var b=D(Wn(a));if(!b&&!D("USE_CSN_FALLBACK",!0))return null;b||!M("use_undefined_csn_any_layer")&&0!=a||(b="UNDEFINED_CSN");return b?b:null}
A("yt_logging_screen.getCurrentCsn",ao,void 0);function bo(a,b,c){var d=$n();(c=ao(c))&&delete d[c];b&&(d[a]=b)}
function co(a){return $n()[a]}
A("yt_logging_screen.getCttAuthInfo",co,void 0);function eo(a,b,c,d){c=void 0===c?0:c;if(a!==D(Wn(c))||b!==D(Xn(c)))bo(a,d,c),ph(Wn(c),a),ph(Xn(c),b),b=function(){setTimeout(function(){if(a){var e={clientDocumentNonce:Rn,clientScreenNonce:a};M("use_default_heartbeat_client")?P("foregroundHeartbeatScreenAssociated",e):Fj("foregroundHeartbeatScreenAssociated",e,rn)}},0)},"requestAnimationFrame"in window?window.requestAnimationFrame(b):b()}
A("yt_logging_screen.setCurrentScreen",eo,void 0);var fo=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};A("yt.msgs_",fo,void 0);function go(a){eh(fo,arguments)}
;var ho={qd:3611,Fc:27686,Gc:85013,Hc:23462,Jc:42016,Kc:62407,Lc:26926,Ic:43781,Mc:51236,Nc:79148,Oc:50160,Pc:77504,cd:87907,dd:18630,ed:54445,fd:80935,gd:105675,hd:37521,jd:47786,kd:98349,ld:123695,md:6827,nd:29434,od:7282,pd:124448,td:32276,sd:76278,ud:93911,vd:106531,wd:27259,xd:27262,yd:27263,Ad:21759,Bd:27107,Cd:62936,Dd:49568,Ed:38408,Fd:80637,Gd:68727,Hd:68728,Id:80353,Jd:80356,Kd:74610,Ld:45707,Md:83962,Nd:83970,Od:46713,Pd:89711,Qd:74612,Rd:93265,Sd:74611,Td:131380,Vd:128979,Wd:139311,Xd:128978,
Ud:131391,Yd:105350,ae:139312,be:134800,Zd:131392,de:113533,ee:93252,ge:99357,ie:94521,je:114252,ke:113532,le:94522,he:94583,me:88E3,ne:139580,oe:93253,pe:93254,qe:94387,re:94388,se:93255,te:97424,ce:72502,ue:110111,we:76019,ye:117092,ze:117093,xe:89431,Ae:110466,Be:77240,Ce:60508,De:137401,Ee:137402,Fe:137046,Ge:73393,He:113534,Ie:92098,Je:131381,Ke:84517,Le:83759,Me:80357,Ne:86113,Oe:72598,Pe:72733,Qe:107349,Re:124275,Se:118203,Te:133275,Ue:133274,Ve:133272,We:133273,Xe:133276,Ye:143247,Ze:143248,
af:143249,bf:143250,cf:143251,ef:117431,df:133797,ff:128572,gf:133405,hf:117429,jf:117430,kf:117432,lf:120080,mf:117259,nf:121692,pf:132972,qf:133051,rf:133658,sf:132971,tf:97615,vf:143359,uf:143356,xf:143361,wf:143358,zf:143360,yf:143357,Af:142303,Bf:143353,Cf:143354,Df:143355,Ef:31402,Gf:133624,Hf:133623,If:133622,Ff:133621,Jf:84774,Kf:95117,Lf:98930,Mf:98931,Nf:98932,Of:43347,Pf:129889,Qf:45474,Rf:100352,Sf:84758,Tf:98443,Uf:117985,Vf:74613,Wf:74614,Xf:64502,Yf:136032,Zf:74615,ag:74616,cg:122224,
dg:74617,eg:77820,fg:74618,gg:93278,hg:93274,ig:93275,jg:93276,kg:22110,lg:29433,mg:133798,ng:132295,pg:120541,rg:82047,sg:113550,tg:75836,ug:75837,vg:42352,wg:84512,xg:76065,yg:75989,zg:16623,Ag:32594,Bg:27240,Cg:32633,Dg:74858,Fg:3945,Eg:16989,Gg:45520,Hg:25488,Ig:25492,Jg:25494,Kg:55760,Lg:14057,Mg:18451,Ng:57204,Og:57203,Pg:17897,Qg:57205,Rg:18198,Sg:17898,Tg:17909,Ug:43980,Vg:46220,Wg:11721,Xg:49954,Yg:96369,Zg:3854,ah:56251,bh:25624,th:16906,uh:99999,vh:68172,wh:27068,xh:47973,yh:72773,zh:26970,
Ah:26971,Bh:96805,Ch:17752,Dh:73233,Eh:109512,Fh:22256,Gh:14115,Hh:22696,Ih:89278,Jh:89277,Kh:109513,Lh:43278,Mh:43459,Nh:43464,Oh:89279,Ph:43717,Qh:55764,Rh:22255,Sh:89281,Th:40963,Uh:43277,Vh:43442,Wh:91824,Xh:120137,Yh:96367,Zh:36850,ai:72694,bi:37414,ci:36851,fi:124863,di:121343,gi:73491,hi:54473,ii:43375,ji:46674,ki:143815,li:139095,mi:32473,ni:72901,oi:72906,ri:50947,si:50612,ti:50613,vi:50942,wi:84938,xi:84943,yi:84939,zi:84941,Ai:84944,Bi:84940,Ci:84942,Di:35585,Ei:51926,Fi:79983,Gi:63238,
Hi:18921,Ii:63241,Ji:57893,Ki:41182,Li:135732,Mi:33424,Ni:22207,Oi:42993,Pi:36229,Qi:22206,Ri:22205,Si:18993,Ti:19001,Ui:18990,Vi:18991,Wi:18997,Xi:18725,Yi:19003,Zi:36874,aj:44763,bj:33427,cj:67793,dj:22182,ej:37091,fj:34650,gj:50617,hj:47261,ij:22287,jj:25144,kj:97917,lj:62397,mj:125598,nj:137935,oj:36961,pj:108035,qj:27426,rj:27857,sj:27846,tj:27854,uj:69692,vj:61411,wj:39299,xj:38696,yj:62520,zj:36382,Aj:108701,Bj:50663,Cj:36387,Dj:14908,Ej:37533,Fj:105443,Gj:61635,Hj:62274,Ij:133818,Jj:65702,
Kj:65703,Lj:65701,Mj:76256,Nj:37671,Oj:49953,Qj:36216,Rj:28237,Sj:39553,Tj:29222,Uj:26107,Vj:38050,Wj:26108,Yj:120745,Xj:26109,Zj:26110,ak:66881,bk:28236,ck:14586,dk:57929,ek:74723,fk:44098,gk:44099,jk:23528,kk:61699,hk:134104,ik:134103,lk:59149,mk:101951,nk:97346,pk:118051,qk:95102,rk:64882,sk:119505,tk:63595,uk:63349,vk:95101,wk:75240,xk:27039,yk:68823,zk:21537,Ak:83464,Bk:75707,Ck:83113,Dk:101952,Ek:101953,Gk:79610,Hk:125755,Ik:24402,Jk:24400,Kk:32925,Lk:57173,Mk:122502,Nk:138480,Ok:64423,Pk:64424,
Qk:33986,Rk:100828,Sk:129089,Tk:21409,Xk:135155,Yk:135156,Zk:135157,al:135158,bl:135159,dl:135160,fl:135161,il:135162,jl:135163,kl:135164,ll:135165,ml:135166,Uk:11070,Vk:11074,Wk:17880,nl:14001,pl:30709,ql:30707,rl:30711,sl:30710,ul:30708,ol:26984,vl:63648,wl:63649,xl:51879,yl:111059,zl:5754,Al:20445,Cl:130975,Bl:130976,Dl:110386,El:113746,Fl:66557,Hl:17310,Il:28631,Jl:21589,Kl:68012,Ll:60480,Ml:138664,Nl:141121,Ol:31571,Pl:141978,Ql:76980,Rl:41577,Sl:45469,Tl:38669,Ul:13768,Vl:13777,Wl:141842,Xl:62985,
Yl:4724,Zl:59369,am:43927,bm:43928,cm:12924,dm:100355,gm:56219,hm:27669,im:10337,fm:47896,jm:122629,lm:139723,km:139722,mm:121258,nm:107598,om:127991,pm:96639,qm:107536,rm:130169,sm:96661,tm:96658,um:116646,vm:121122,wm:96660,xm:127738,ym:127083,zm:104443,Am:96659,Bm:106442,Cm:134840,Dm:63667,Em:63668,Fm:63669,Gm:130686,Hm:78314,Im:55761,Jm:127098,Km:134841,Lm:96368,Mm:67374,Nm:48992,Om:49956,Pm:31961,Qm:26388,Rm:23811,Sm:5E4,Tm:126250,Um:96370,Vm:47355,Wm:47356,Xm:37935,Ym:45521,Zm:21760,an:83769,
bn:49977,cn:49974,dn:93497,en:93498,fn:34325,gn:140759,hn:115803,jn:123707,kn:100081,ln:35309,mn:68314,nn:25602,pn:100339,qn:143516,rn:59018,sn:18248,tn:50625,un:9729,vn:37168,wn:37169,xn:21667,yn:16749,zn:18635,An:39305,Bn:18046,Cn:53969,Dn:8213,En:93926,Fn:102852,Gn:110099,Hn:22678,In:69076,Jn:137575,Ln:139224,Mn:100856,Nn:17736,On:3832,Pn:55759,Qn:64031,Wn:93044,Xn:93045,Yn:34388,Zn:17657,ao:17655,bo:39579,co:39578,eo:77448,fo:8196,ho:11357,jo:69877,ko:8197,lo:82039};function io(){var a=sb(jo),b;return Qf(new Jf(function(c,d){a.onSuccess=function(e){si(e)?c(new ko(e)):d(new lo("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new lo("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new lo("Request timed out","net.timeout",e))};
b=yi("//googleads.g.doubleclick.net/pagead/id",a)}),function(c){c instanceof Rf&&b.abort();
return Of(c)})}
function lo(a,b,c){Za.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
u(lo,Za);function ko(a){this.xhr=a}
;function mo(){this.i=0;this.h=null}
mo.prototype.then=function(a,b,c){return 1===this.i&&a?(a=a.call(c,this.h),If(a)?a:no(a)):2===this.i&&b?(a=b.call(c,this.h),If(a)?a:oo(a)):this};
mo.prototype.getValue=function(){return this.h};
mo.prototype.$goog_Thenable=!0;function oo(a){var b=new mo;a=void 0===a?null:a;b.i=2;b.h=void 0===a?null:a;return b}
function no(a){var b=new mo;a=void 0===a?null:a;b.i=1;b.h=void 0===a?null:a;return b}
;function po(){if(Xd())return!0;var a=D("INNERTUBE_CLIENT_NAME");return!a||"WEB"!==a&&"MWEB"!==a||Gi&&Hi("applewebkit")&&!Hi("version")&&(!Hi("safari")||Hi("gsa/"))||vc&&Hi("version/")?!0:(a=Lj("CONSENT"))?a.startsWith("YES+"):!0}
;function qo(a){Za.call(this,a.message||a.description||a.name);this.isMissing=a instanceof ro;this.isTimeout=a instanceof lo&&"net.timeout"==a.errorCode;this.isCanceled=a instanceof Rf}
u(qo,Za);qo.prototype.name="BiscottiError";function ro(){Za.call(this,"Biscotti ID is missing from server")}
u(ro,Za);ro.prototype.name="BiscottiMissingError";var jo={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},so=null;function ci(){if(M("disable_biscotti_fetch_entirely_for_all_web_clients"))return Of(Error("Biscotti id fetching has been disabled entirely."));if(!po())return Of(Error("User has not consented - not fetching biscotti id."));if("1"==qb())return Of(Error("Biscotti ID is not available in private embed mode"));so||(so=Qf(io().then(to),function(a){return uo(2,a)}));
return so}
function to(a){a=a.xhr.responseText;if(0!=a.lastIndexOf(")]}'",0))throw new ro;a=JSON.parse(a.substr(4));if(1<(a.type||1))throw new ro;a=a.id;di(a);so=no(a);vo(18E5,2);return a}
function uo(a,b){b=new qo(b);di("");so=oo(b);0<a&&vo(12E4,a-1);throw b;}
function vo(a,b){Mh(function(){Qf(io().then(to,function(c){return uo(b,c)}),Ja)},a)}
function wo(){try{var a=C("yt.ads.biscotti.getId_");return a?a():ci()}catch(b){return Of(b)}}
;function xo(a){if("1"!=qb()){a&&bi();try{wo().then(function(){},function(){}),Mh(xo,18E5)}catch(b){Bh(b)}}}
;function yo(){this.Cc=!0}
function zo(a){var b={},c=Zd([]);c&&(b.Authorization=c,c=a=null===a||void 0===a?void 0:a.sessionIndex,void 0===c&&(c=Number(D("SESSION_INDEX",0)),c=isNaN(c)?0:c),b["X-Goog-AuthUser"]=c,"INNERTUBE_HOST_OVERRIDE"in jh||(b["X-Origin"]=window.location.origin),void 0===a&&"DELEGATED_SESSION_ID"in jh&&(b["X-Goog-PageId"]=D("DELEGATED_SESSION_ID")));return b}
;var Ao={identityType:"UNAUTHENTICATED_IDENTITY_TYPE_UNKNOWN"};var Bo=new Map([["dark","USER_INTERFACE_THEME_DARK"],["light","USER_INTERFACE_THEME_LIGHT"]]),Co=["/fashion","/feed/fashion_destination","/channel/UCrpQ4p1Ql_hG8rKXIKM1MOQ"];function Do(){var a=void 0===a?window.location.href:a;if(M("kevlar_disable_theme_param"))return null;var b=hc(a.match(gc)[5]||null);if(Eo(b))return"USER_INTERFACE_THEME_DARK";try{var c=li(a).theme;return Bo.get(c)||null}catch(d){}return null}
function Eo(a){var b=Co.map(function(c){return c.toLowerCase()});
return!M("disable_dark_fashion_destination_launch")&&b.some(function(c){return a.toLowerCase().startsWith(c)})?!0:!1}
;function Fo(){this.h={};if(this.i=Mj()){var a=Lj("CONSISTENCY");a&&Go(this,{encryptedTokenJarContents:a})}}
Fo.prototype.handleResponse=function(a,b){var c,d,e;b=(null===(d=null===(c=b.aa.context)||void 0===c?void 0:c.request)||void 0===d?void 0:d.consistencyTokenJars)||[];(a=null===(e=a.responseContext)||void 0===e?void 0:e.consistencyTokenJar)&&this.replace(b,a)};
Fo.prototype.replace=function(a,b){a=r(a);for(var c=a.next();!c.done;c=a.next())delete this.h[c.value.encryptedTokenJarContents];Go(this,b)};
function Go(a,b){if(b.encryptedTokenJarContents&&(a.h[b.encryptedTokenJarContents]=b,"string"===typeof b.expirationSeconds)){var c=Number(b.expirationSeconds);setTimeout(function(){delete a.h[b.encryptedTokenJarContents]},1E3*c);
a.i&&Kj("CONSISTENCY",b.encryptedTokenJarContents,c,void 0,!0)}}
;var Ho=window.location.hostname.split(".").slice(-2).join(".");function Io(){var a=D("LOCATION_PLAYABILITY_TOKEN");"TVHTML5"===D("INNERTUBE_CLIENT_NAME")&&(this.h=Jo(this))&&(a=this.h.get("yt-location-playability-token"));a&&(this.locationPlayabilityToken=a,this.i=void 0)}
var Ko;Io.getInstance=function(){Ko=C("yt.clientLocationService.instance");Ko||(Ko=new Io,A("yt.clientLocationService.instance",Ko,void 0));return Ko};
Io.prototype.setLocationOnInnerTubeContext=function(a){a.client||(a.client={});this.i?(a.client.locationInfo||(a.client.locationInfo={}),a.client.locationInfo.latitudeE7=1E7*this.i.coords.latitude,a.client.locationInfo.longitudeE7=1E7*this.i.coords.longitude,a.client.locationInfo.horizontalAccuracyMeters=this.i.coords.accuracy,a.client.locationInfo.forceLocationPlayabilityTokenRefresh=!0):this.locationPlayabilityToken&&(a.client.locationPlayabilityToken=this.locationPlayabilityToken)};
Io.prototype.handleResponse=function(a){var b;a=null===(b=a.responseContext)||void 0===b?void 0:b.locationPlayabilityToken;void 0!==a&&(this.locationPlayabilityToken=a,this.i=void 0,"TVHTML5"===D("INNERTUBE_CLIENT_NAME")?(this.h=Jo(this))&&this.h.set("yt-location-playability-token",a,15552E3):Kj("YT_CL",JSON.stringify({vo:a}),15552E3,Ho,!0))};
function Jo(a){return void 0===a.h?new ik("yt-client-location"):a.h}
Io.prototype.getCurrentPositionFromGeolocation=function(){var a=this;if(!(navigator&&navigator.geolocation&&navigator.geolocation.getCurrentPosition)||!M("web_enable_browser_geolocation_api")&&!M("enable_handoff_location_2fa_on_mweb"))return Promise.reject(Error("Geolocation unsupported"));var b=!1,c=1E4;M("enable_handoff_location_2fa_on_mweb")&&(b=!0,c=15E3);return new Promise(function(d,e){navigator.geolocation.getCurrentPosition(function(f){a.i=f;d(f)},function(f){e(f)},{enableHighAccuracy:b,
maximumAge:0,timeout:c})})};
Io.prototype.createUnpluggedLocationInfo=function(a){var b={};a=a.coords;if(null===a||void 0===a?0:a.latitude)b.latitudeE7=Math.floor(1E7*a.latitude);if(null===a||void 0===a?0:a.longitude)b.longitudeE7=Math.floor(1E7*a.longitude);if(null===a||void 0===a?0:a.accuracy)b.locationRadiusMeters=Math.round(a.accuracy);return b};function Lo(a,b){var c,d;if((null===(c=a.signalServiceEndpoint)||void 0===c?0:c.signal)&&b.Da){var e=b.Da[a.signalServiceEndpoint.signal];if(e)return e()}if((null===(d=a.continuationCommand)||void 0===d?0:d.request)&&b.Vb&&(e=b.Vb[a.continuationCommand.request]))return e();for(var f in a)if(b.tb[f]&&(a=b.tb[f]))return a()}
;function Mo(a){return function(){return new a}}
;var No={},Oo=(No.WEB_UNPLUGGED="^unplugged/",No.WEB_UNPLUGGED_ONBOARDING="^unplugged/",No.WEB_UNPLUGGED_OPS="^unplugged/",No.WEB_UNPLUGGED_PUBLIC="^unplugged/",No.WEB_CREATOR="^creator/",No.WEB_KIDS="^kids/",No.WEB_EXPERIMENTS="^experiments/",No.WEB_MUSIC="^music/",No.WEB_REMIX="^music/",No.WEB_MUSIC_EMBEDDED_PLAYER="^music/",No.WEB_MUSIC_EMBEDDED_PLAYER="^main_app/|^sfv/",No);
function Po(a){var b=void 0===b?"UNKNOWN_INTERFACE":b;if(1===a.length)return a[0];var c=Oo[b];if(c){var d=new RegExp(c),e=r(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,d.exec(c))return c}var f=[];Object.entries(Oo).forEach(function(g){var h=r(g);g=h.next().value;h=h.next().value;b!==g&&f.push(h)});
d=new RegExp(f.join("|"));a.sort(function(g,h){return g.length-h.length});
e=r(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,!d.exec(c))return c;return a[0]}
;function Qo(a,b){return{method:void 0===b?"POST":b,mode:ni(a)?"same-origin":"cors",credentials:ni(a)?"same-origin":"include"}}
;function Ro(){}
Ro.prototype.o=function(a,b,c){b=void 0===b?{}:b;c=void 0===c?Ao:c;var d;var e=a.clickTrackingParams,f=this.l,g=!1;g=void 0===g?!1:g;f=void 0===f?!1:f;var h=D("INNERTUBE_CONTEXT");if(h){h=tb(h);M("web_no_tracking_params_in_shell_killswitch")||delete h.clickTracking;var k,l;h.client||(h.client={});var m=h.client;"MWEB"===m.clientName&&(m.clientFormFactor=D("IS_TABLET")?"LARGE_FORM_FACTOR":"SMALL_FORM_FACTOR");m.screenWidthPoints=window.innerWidth;m.screenHeightPoints=window.innerHeight;m.screenPixelDensity=
Math.round(window.devicePixelRatio||1);m.screenDensityFloat=window.devicePixelRatio||1;m.utcOffsetMinutes=-Math.floor((new Date).getTimezoneOffset());var q=void 0===q?!1:q;Oj.getInstance();var w="USER_INTERFACE_THEME_LIGHT";Rj(165)?w="USER_INTERFACE_THEME_DARK":Rj(174)?w="USER_INTERFACE_THEME_LIGHT":!M("kevlar_legacy_browsers")&&window.matchMedia&&window.matchMedia("(prefers-color-scheme)").matches&&window.matchMedia("(prefers-color-scheme: dark)").matches&&(w="USER_INTERFACE_THEME_DARK");q=q?w:Do()||
w;m.userInterfaceTheme=q;if(!g){if(q=Yj())m.connectionType=q;M("web_log_effective_connection_type")&&(q=Zj())&&(h.client.effectiveConnectionType=q)}M("web_log_memory_total_kbytes")&&(null===(k=y.navigator)||void 0===k?0:k.deviceMemory)&&(k=null===(l=y.navigator)||void 0===l?void 0:l.deviceMemory,h.client.memoryTotalKbytes=""+1E6*k);l=li(y.location.href);!M("web_populate_internal_geo_killswitch")&&l.internalcountrycode&&(m.internalGeo=l.internalcountrycode);"MWEB"===m.clientName||"WEB"===m.clientName?
(m.mainAppWebInfo={graftUrl:y.location.href},M("kevlar_woffle")&&Hj.h&&(m.mainAppWebInfo.pwaInstallabilityStatus=Hj.h.h?"PWA_INSTALLABILITY_STATUS_CAN_BE_INSTALLED":"PWA_INSTALLABILITY_STATUS_UNKNOWN"),m.mainAppWebInfo.webDisplayMode=Ij(),m.mainAppWebInfo.isWebNativeShareAvailable=navigator&&void 0!==navigator.share):"TVHTML5"===m.clientName&&(!M("web_lr_app_quality_killswitch")&&(l=D("LIVING_ROOM_APP_QUALITY"))&&(m.tvAppInfo=Object.assign(m.tvAppInfo||{},{appQuality:l})),l=D("LIVING_ROOM_CERTIFICATION_SCOPE"))&&
(m.tvAppInfo=Object.assign(m.tvAppInfo||{},{certificationScope:l}));if(!M("web_populate_time_zone_itc_killswitch")){b:{if("undefined"!==typeof Intl)try{var t=(new Intl.DateTimeFormat).resolvedOptions().timeZone;break b}catch(da){}t=void 0}t&&(m.timeZone=t)}(t=sh())?m.experimentsToken=t:delete m.experimentsToken;t=th();Fo.h||(Fo.h=new Fo);m=Fo.h.h;l=[];k=0;for(var z in m)l[k++]=m[z];h.request=Object.assign(Object.assign({},h.request),{internalExperimentFlags:t,consistencyTokenJars:l});!M("web_prequest_context_killswitch")&&
(z=D("INNERTUBE_CONTEXT_PREQUEST_CONTEXT"))&&(h.request.externalPrequestContext=z);t=Oj.getInstance();z=Rj(58);t=t.get("gsml","");h.user=Object.assign({},h.user);z&&(h.user.enableSafetyMode=z);t&&(h.user.lockedSafetyMode=!0);M("warm_op_csn_cleanup")?f&&(g=ao())&&(h.clientScreenNonce=g):!g&&(g=ao())&&(h.clientScreenNonce=g);e&&(h.clickTracking={clickTrackingParams:e});if(e=C("yt.mdx.remote.remoteClient_"))h.remoteClient=e;M("web_enable_client_location_service")&&Io.getInstance().setLocationOnInnerTubeContext(h);
try{var B=oi(void 0),I=B.bid;delete B.bid;h.adSignalsInfo={params:[],bid:I};for(var L=r(Object.entries(B)),N=L.next();!N.done;N=L.next()){var R=r(N.value),W=R.next().value,od=R.next().value;B=W;I=od;null===(d=h.adSignalsInfo.params)||void 0===d?void 0:d.push({key:B,value:""+I})}}catch(da){Kn(da)}d=h}else Kn(Error("Error: No InnerTubeContext shell provided in ytconfig.")),d={};d={context:d};if(L=this.h(a)){this.i(d,L,b);var ca,U;b="/youtubei/v1/"+Po(this.j());(a=null===(U=null===(ca=a.commandMetadata)||
void 0===ca?void 0:ca.webCommandMetadata)||void 0===U?void 0:U.apiUrl)&&(b=a);ca=b;(U=D("INNERTUBE_HOST_OVERRIDE"))&&(ca=String(U)+String(jc(ca)));U={};U.key=D("INNERTUBE_API_KEY");M("json_condensed_response")&&(U.prettyPrint="false");ca=mi(ca,U||{},!1);ca={input:ca,wa:Qo(ca),aa:d,config:Object.assign({},void 0)};ca.config.Ka?ca.config.Ka.identity=c:ca.config.Ka={identity:c};return ca}Kn(new yk("Error: Failed to create Request from Command.",a))};
fa.Object.defineProperties(Ro.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!1}}});function So(){}
u(So,Ro);So.prototype.o=function(){return{input:"/getDatasyncIdsEndpoint",wa:Qo("/getDatasyncIdsEndpoint","GET"),aa:{}}};
So.prototype.j=function(){return[]};
So.prototype.h=function(){};
So.prototype.i=function(){};var To={},Uo=(To.GET_DATASYNC_IDS=Mo(So),To);function Vo(a){var b=Ea.apply(1,arguments);if(!Wo(a)||b.some(function(e){return!Wo(e)}))throw Error("Only objects may be merged.");
var c=a;b=r(b);for(var d=b.next();!d.done;d=b.next())Xo(c,d.value);return c}
function Xo(a,b){for(var c in b)if(Wo(b[c])){if(c in a&&!Wo(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});Xo(a[c],b[c])}else if(Yo(b[c])){if(c in a&&!Yo(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);Zo(a[c],b[c])}else a[c]=b[c];return a}
function Zo(a,b){b=r(b);for(var c=b.next();!c.done;c=b.next())c=c.value,Wo(c)?a.push(Xo({},c)):Yo(c)?a.push(Zo([],c)):a.push(c);return a}
function Wo(a){return"object"===typeof a&&!Array.isArray(a)}
function Yo(a){return"object"===typeof a&&Array.isArray(a)}
;function $o(a,b){Zl.call(this,1,arguments);this.timer=b}
u($o,Zl);var ap=new $l("aft-recorded",$o);var bp=window;function cp(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
var V=bp.performance||bp.mozPerformance||bp.msPerformance||bp.webkitPerformance||new cp;var dp=!1,ep={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",
'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",'script[name="mobile_blazer_watch_mod"]':"mbwj"},
fp=Ta(V.clearResourceTimings||V.webkitClearResourceTimings||V.mozClearResourceTimings||V.msClearResourceTimings||V.oClearResourceTimings||Ja,V);function gp(a){var b=hp(a);if(b.aft)return b.aft;a=D((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=a.length,d=0;d<c;d++){var e=b[a[d]];if(e)return e}return NaN}
function ip(){var a;if(M("csi_use_performance_navigation_timing")){var b,c,d,e=null===(d=null===(c=null===(b=null===(a=null===V||void 0===V?void 0:V.getEntriesByType)||void 0===a?void 0:a.call(V,"navigation"))||void 0===b?void 0:b[0])||void 0===c?void 0:c.toJSON)||void 0===d?void 0:d.call(c);e?(e.requestStart=jp(e.requestStart),e.responseEnd=jp(e.responseEnd),e.redirectStart=jp(e.redirectStart),e.redirectEnd=jp(e.redirectEnd),e.domainLookupEnd=jp(e.domainLookupEnd),e.connectStart=jp(e.connectStart),
e.connectEnd=jp(e.connectEnd),e.responseStart=jp(e.responseStart),e.secureConnectionStart=jp(e.secureConnectionStart),e.domainLookupStart=jp(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=V.timing}else a=V.timing;return a}
function kp(){return M("csi_use_time_origin")&&V.timeOrigin?Math.floor(V.timeOrigin):V.timing.navigationStart}
function jp(a){return Math.round(kp()+a)}
function lp(a){A("ytglobal.timing"+(a||"")+"ready_",!0,void 0)}
function mp(a){return C("ytcsi."+(a||"")+"data_")||np(a)}
function op(a){a=mp(a);a.info||(a.info={});return a.info}
function hp(a){a=mp(a);a.tick||(a.tick={});return a.tick}
function pp(a){a=mp(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function qp(a){a=pp(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
function rp(a){var b=mp(a).nonce;b||(b=Qn(),mp(a).nonce=b);return b}
function np(a){var b={tick:{},info:{}};A("ytcsi."+(a||"")+"data_",b,void 0);return b}
function sp(a){var b=hp(a||""),c=gp(a);c&&!dp&&(em(ap,new $o(Math.round(c-b._start),a)),dp=!0)}
function tp(a,b){for(var c=r(Object.keys(b)),d=c.next();!d.done;d=c.next())if(d=d.value,!Object.keys(a).includes(d)||"object"===typeof b[d]&&!tp(a[d],b[d]))return!1;return!0}
;function up(){if(V.getEntriesByType){var a=V.getEntriesByType("paint");if(a=hb(a,function(b){return"first-paint"===b.name}))return jp(a.startTime)}a=V.timing;
return a.ic?Math.max(0,a.ic):0}
;function vp(){var a=C("ytcsi.debug");a||(a=[],A("ytcsi.debug",a,void 0),A("ytcsi.reference",{},void 0));return a}
function wp(a){a=a||"";var b=xp();if(b[a])return b[a];var c=vp(),d={timerName:a,info:{},tick:{},span:{}};c.push(d);return b[a]=d}
function xp(){var a=C("ytcsi.reference");if(a)return a;vp();return C("ytcsi.reference")}
;var yp=y.ytLoggingGelSequenceIdObj_||{};A("ytLoggingGelSequenceIdObj_",yp,void 0);function zp(a,b,c){c=void 0===c?{}:c;var d=Math.round(c.timestamp||O());G(a,1,d<Number.MAX_SAFE_INTEGER?d:0);var e=ai();d=new Ug;G(d,1,c.timestamp||!isFinite(e)?-1:e);if(M("log_sequence_info_on_gel_web")&&c.W){e=c.W;var f=Gj(e),g=new Tg;G(g,2,f);G(g,1,e);H(d,3,g);c.yb&&delete yp[c.W]}H(a,33,d);(c.sc?rj:mj)({endpoint:"log_event",payload:a,cttAuthInfo:c.cttAuthInfo,za:c.za},b)}
;function Ap(a,b){b=void 0===b?{}:b;var c=!1;D("ytLoggingEventsDefaultDisabled",!1)&&rn===rn&&(c=!0);zp(a,c?null:rn,b)}
;function Bp(a,b,c){var d=new Vg;cd(d,72,a);c?zp(d,c,b):Ap(d,b)}
function Cp(a,b,c){var d=new Vg;cd(d,73,a);c?zp(d,c,b):Ap(d,b)}
function Dp(a,b,c){var d=new Vg;cd(d,78,a);c?zp(d,c,b):Ap(d,b)}
function Ep(a,b,c){var d=new Vg;cd(d,208,a);c?zp(d,c,b):Ap(d,b)}
function Fp(a,b,c){var d=new Vg;cd(d,156,a);c?zp(d,c,b):Ap(d,b)}
function Gp(a,b,c){var d=new Vg;cd(d,215,a);c?zp(d,c,b):Ap(d,b)}
;var Hp=y.ytLoggingLatencyUsageStats_||{};A("ytLoggingLatencyUsageStats_",Hp,void 0);function Ip(){this.h=0}
function Jp(){Ip.h||(Ip.h=new Ip);return Ip.h}
Ip.prototype.tick=function(a,b,c,d){Kp(this,"tick_"+a+"_"+b)||(c={timestamp:c,cttAuthInfo:d},M("web_csi_via_jspb")?(d=new Sg,G(d,1,a),G(d,2,b),a=new Vg,cd(a,5,d),Ap(a,c)):P("latencyActionTicked",{tickName:a,clientActionNonce:b},c))};
Ip.prototype.info=function(a,b,c){var d=Object.keys(a).join("");Kp(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,P("latencyActionInfo",a,{cttAuthInfo:c}))};
Ip.prototype.span=function(a,b,c){var d=Object.keys(a).join("");Kp(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,P("latencyActionSpan",a,{cttAuthInfo:c}))};
function Kp(a,b){Hp[b]=Hp[b]||{count:0};var c=Hp[b];c.count++;c.time=O();a.h||(a.h=Qh(function(){var d=O(),e;for(e in Hp)Hp[e]&&6E4<d-Hp[e].time&&delete Hp[e];a&&(a.h=0)},5E3));
return 5<c.count?(6===c.count&&1>1E5*Math.random()&&(c=new yk("CSI data exceeded logging limit with key",b.split("_")),0<=b.indexOf("plev")||T(c)),!0):!1}
;var X={},Lp=(X.auto_search="LATENCY_ACTION_AUTO_SEARCH",X.ad_to_ad="LATENCY_ACTION_AD_TO_AD",X.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",X["analytics.explore"]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE",X.app_startup="LATENCY_ACTION_APP_STARTUP",X["artist.analytics"]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS",X["artist.events"]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS",X["artist.presskit"]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE",X.browse="LATENCY_ACTION_BROWSE",X.cast_splash="LATENCY_ACTION_CAST_SPLASH",
X.channels="LATENCY_ACTION_CHANNELS",X.creator_channel_dashboard="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD",X["channel.analytics"]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS",X["channel.comments"]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS",X["channel.content"]="LATENCY_ACTION_CREATOR_POST_LIST",X["channel.copyright"]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT",X["channel.editing"]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING",X["channel.monetization"]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION",X["channel.music"]=
"LATENCY_ACTION_CREATOR_CHANNEL_MUSIC",X["channel.playlists"]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS",X["channel.translations"]="LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS",X["channel.videos"]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS",X["channel.live_streaming"]="LATENCY_ACTION_CREATOR_LIVE_STREAMING",X.chips="LATENCY_ACTION_CHIPS",X["dialog.copyright_strikes"]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES",X["dialog.uploads"]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS",X.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",
X.embed="LATENCY_ACTION_EMBED",X.entity_key_serialization_perf="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",X.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",X.explore="LATENCY_ACTION_EXPLORE",X.home="LATENCY_ACTION_HOME",X.library="LATENCY_ACTION_LIBRARY",X.live="LATENCY_ACTION_LIVE",X.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",X.onboarding="LATENCY_ACTION_ONBOARDING",X.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",X.parent_tools_collection=
"LATENCY_ACTION_PARENT_TOOLS_COLLECTION",X.parent_tools_dashboard="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",X.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",X["post.comments"]="LATENCY_ACTION_CREATOR_POST_COMMENTS",X["post.edit"]="LATENCY_ACTION_CREATOR_POST_EDIT",X.prebuffer="LATENCY_ACTION_PREBUFFER",X.prefetch="LATENCY_ACTION_PREFETCH",X.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",X.profile_switcher="LATENCY_ACTION_LOGIN",X.reel_watch="LATENCY_ACTION_REEL_WATCH",X.results="LATENCY_ACTION_RESULTS",
X.search_ui="LATENCY_ACTION_SEARCH_UI",X.search_suggest="LATENCY_ACTION_SUGGEST",X.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",X.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",X.seek="LATENCY_ACTION_PLAYER_SEEK",X.settings="LATENCY_ACTION_SETTINGS",X.tenx="LATENCY_ACTION_TENX",X.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",X.watch="LATENCY_ACTION_WATCH",X.watch_it_again="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",X["watch,watch7"]="LATENCY_ACTION_WATCH",X["watch,watch7_html5"]="LATENCY_ACTION_WATCH",
X["watch,watch7ad"]="LATENCY_ACTION_WATCH",X["watch,watch7ad_html5"]="LATENCY_ACTION_WATCH",X.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",X.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",X["video.analytics"]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS",X["video.comments"]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS",X["video.edit"]="LATENCY_ACTION_CREATOR_VIDEO_EDIT",X["video.editor"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR",X["video.editor_async"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC",X["video.live_settings"]=
"LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS",X["video.live_streaming"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING",X["video.monetization"]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION",X["video.translations"]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS",X.voice_assistant="LATENCY_ACTION_VOICE_ASSISTANT",X.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",X.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",X),Y={},Mp=(Y.ad_allowed="adTypesAllowed",Y.yt_abt="adBreakType",
Y.ad_cpn="adClientPlaybackNonce",Y.ad_docid="adVideoId",Y.yt_ad_an="adNetworks",Y.ad_at="adType",Y.aida="appInstallDataAgeMs",Y.browse_id="browseId",Y.p="httpProtocol",Y.t="transportProtocol",Y.cs="commandSource",Y.cpn="clientPlaybackNonce",Y.ccs="creatorInfo.creatorCanaryState",Y.ctop="creatorInfo.topEntityType",Y.csn="clientScreenNonce",Y.docid="videoId",Y.GetHome_rid="requestIds",Y.GetSearch_rid="requestIds",Y.GetPlayer_rid="requestIds",Y.GetWatchNext_rid="requestIds",Y.GetBrowse_rid="requestIds",
Y.GetLibrary_rid="requestIds",Y.is_continuation="isContinuation",Y.is_nav="isNavigation",Y.b_p="kabukiInfo.browseParams",Y.is_prefetch="kabukiInfo.isPrefetch",Y.is_secondary_nav="kabukiInfo.isSecondaryNav",Y.nav_type="kabukiInfo.navigationType",Y.prev_browse_id="kabukiInfo.prevBrowseId",Y.query_source="kabukiInfo.querySource",Y.voz_type="kabukiInfo.vozType",Y.yt_lt="loadType",Y.mver="creatorInfo.measurementVersion",Y.yt_ad="isMonetized",Y.nr="webInfo.navigationReason",Y.nrsu="navigationRequestedSameUrl",
Y.ncnp="webInfo.nonPreloadedNodeCount",Y.pnt="performanceNavigationTiming",Y.prt="playbackRequiresTap",Y.plt="playerInfo.playbackType",Y.pis="playerInfo.playerInitializedState",Y.paused="playerInfo.isPausedOnLoad",Y.yt_pt="playerType",Y.fmt="playerInfo.itag",Y.yt_pl="watchInfo.isPlaylist",Y.yt_pre="playerInfo.preloadType",Y.yt_ad_pr="prerollAllowed",Y.pa="previousAction",Y.yt_red="isRedSubscriber",Y.rce="mwebInfo.responseContentEncoding",Y.rc="resourceInfo.resourceCache",Y.scrh="screenHeight",Y.scrw=
"screenWidth",Y.st="serverTimeMs",Y.ssdm="shellStartupDurationMs",Y.br_trs="tvInfo.bedrockTriggerState",Y.kebqat="kabukiInfo.earlyBrowseRequestInfo.abandonmentType",Y.kebqa="kabukiInfo.earlyBrowseRequestInfo.adopted",Y.label="tvInfo.label",Y.is_mdx="tvInfo.isMdx",Y.preloaded="tvInfo.isPreloaded",Y.aac_type="tvInfo.authAccessCredentialType",Y.upg_player_vis="playerInfo.visibilityState",Y.query="unpluggedInfo.query",Y.upg_chip_ids_string="unpluggedInfo.upgChipIdsString",Y.yt_vst="videoStreamType",Y.vph=
"viewportHeight",Y.vpw="viewportWidth",Y.yt_vis="isVisible",Y.rcl="mwebInfo.responseContentLength",Y.GetSettings_rid="requestIds",Y.GetTrending_rid="requestIds",Y.GetMusicSearchSuggestions_rid="requestIds",Y.REQUEST_ID="requestIds",Y),Np="isContinuation isNavigation kabukiInfo.earlyBrowseRequestInfo.adopted kabukiInfo.isPrefetch kabukiInfo.isSecondaryNav isMonetized navigationRequestedSameUrl performanceNavigationTiming playerInfo.isPausedOnLoad prerollAllowed isRedSubscriber tvInfo.isMdx tvInfo.isPreloaded isVisible watchInfo.isPlaylist playbackRequiresTap".split(" "),
Op={},Pp=(Op.ccs="CANARY_STATE_",Op.mver="MEASUREMENT_VERSION_",Op.pis="PLAYER_INITIALIZED_STATE_",Op.yt_pt="LATENCY_PLAYER_",Op.pa="LATENCY_ACTION_",Op.ctop="TOP_ENTITY_TYPE_",Op.yt_vst="VIDEO_STREAM_TYPE_",Op),Qp="all_vc ap aq c cbr cbrand cbrver cmodel cos cosver cplatform ctheme cver ei l_an l_mm plid srt yt_fss yt_li vpst vpni2 vpil2 icrc icrt pa GetAccountOverview_rid GetHistory_rid cmt d_vpct d_vpnfi d_vpni nsru pc pfa pfeh pftr pnc prerender psc rc start tcrt tcrc ssr vpr vps yt_abt yt_fn yt_fs yt_pft yt_pre yt_pt yt_pvis ytu_pvis yt_ref yt_sts tds".split(" ");
function Rp(a,b,c){c=pp(c);if(c.gelInfos)c.gelInfos[a]=!0;else{var d={};c.gelInfos=(d[a]=!0,d)}if(a.match("_rid")){var e=a.split("_rid")[0];a="REQUEST_ID"}if(a in Mp){c=Mp[a];0<=cb(Np,c)&&(b=!!b);a in Pp&&"string"===typeof b&&(b=Pp[a]+b.toUpperCase());a=b;b=c.split(".");for(var f=d={},g=0;g<b.length-1;g++){var h=b[g];f[h]={};f=f[h]}f[b[b.length-1]]="requestIds"===c?[{id:a,endpoint:e}]:a;return Vo({},d)}0<=cb(Qp,a)||T(new yk("Unknown label logged with GEL CSI",a))}
function Sp(a){var b={actionType:Lp[D((a||"")+"TIMING_ACTION",void 0)]||"LATENCY_ACTION_UNKNOWN",previousAction:Lp[D("PREVIOUS_ACTION",void 0)]||"LATENCY_ACTION_UNKNOWN"},c=ao();c&&(b.clientScreenNonce=c);c=rp(a);a=mp(a).cttAuthInfo;Jp().info(b,c,a)}
;function Tp(){var a=["ol"];wp("").info.actionType="embed";a&&ph("TIMING_AFT_KEYS",a);ph("TIMING_ACTION","embed");a=D("TIMING_INFO",{});for(var b in a)a.hasOwnProperty(b)&&Up(b,a[b]);Up("is_nav",1);(b=ao())&&Up("csn",b);b=op();a=D("CLIENT_PROTOCOL");var c=D("CLIENT_TRANSPORT");a&&Up("p",a);c&&Up("t",c);Up("yt_vis",Vp());Up("yt_lt","cold");a=ip();if(c=kp())Z("srt",a.responseStart),1!==b.prerender&&(Up("yt_sts","n",void 0),Z("_start",c,void 0));b=up();0<b&&Z("fpt",b);b=ip();b.isPerformanceNavigationTiming&&
Up("pnt",1,void 0);Z("nreqs",b.requestStart,void 0);Z("nress",b.responseStart,void 0);Z("nrese",b.responseEnd,void 0);0<b.redirectEnd-b.redirectStart&&(Z("nrs",b.redirectStart,void 0),Z("nre",b.redirectEnd,void 0));0<b.domainLookupEnd-b.domainLookupStart&&(Z("ndnss",b.domainLookupStart,void 0),Z("ndnse",b.domainLookupEnd,void 0));0<b.connectEnd-b.connectStart&&(Z("ntcps",b.connectStart,void 0),Z("ntcpe",b.connectEnd,void 0));b.secureConnectionStart>=kp()&&0<b.connectEnd-b.secureConnectionStart&&(Z("nstcps",
b.secureConnectionStart,void 0),Z("ntcpe",b.connectEnd,void 0));V&&V.getEntriesByType&&Wp();b=[];if(document.querySelector&&V&&V.getEntriesByName)for(var d in ep)ep.hasOwnProperty(d)&&(a=ep[d],Xp(d,a)&&b.push(a));for(d=0;d<b.length;d++)Up("rc",b[d]);Sp();d=op();b=qp();if("cold"===d.yt_lt||"cold"===b.loadType){a=hp();c=pp();c=c.gelTicks?c.gelTicks:c.gelTicks={};for(var e in a)e in c||Z(e,a[e]);e={};a=!1;c=r(Object.keys(d));for(var f=c.next();!f.done;f=c.next())f=f.value,(f=Rp(f,d[f]))&&!tp(qp(void 0),
f)&&(Vo(b,f),Vo(e,f),a=!0);a&&Yp(e)}lp();e=D("TIMING_ACTION",void 0);C("ytglobal.timingready_")&&e&&"_start"in hp(void 0)&&gp()&&sp()}
function Up(a,b,c){null!==b&&(op(c)[a]=b,(a=Rp(a,b,c))&&Yp(a,c))}
function Yp(a,b){var c=wp(b||"");Vo(c.info,a);Vo(qp(b),a);c=rp(b);b=mp(b).cttAuthInfo;Jp().info(a,c,b)}
function Z(a,b,c){if(!b&&"_"!==a[0]){var d=a;V.mark&&(0==d.lastIndexOf("mark_",0)||(d="mark_"+d),c&&(d+=" ("+c+")"),V.mark(d))}wp(c||"").tick[a]=b||O();d=pp(c);d.gelTicks&&(d.gelTicks[a]=!0);d=hp(c);var e=b||O();d[a]=e;e=rp(c);var f=mp(c).cttAuthInfo;if("_start"===a){var g=Jp();Kp(g,"baseline_"+e)||(b={timestamp:b,cttAuthInfo:f},M("web_csi_via_jspb")?(f=new Rg,G(f,1,e),e=new Vg,cd(e,6,f),Ap(e,b)):P("latencyActionBaselined",{clientActionNonce:e},b))}else Jp().tick(a,e,b,f);sp(c);return d[a]}
function Zp(){var a=rp(void 0);requestAnimationFrame(function(){setTimeout(function(){a===rp(void 0)&&Z("ol",void 0,void 0)},0)})}
function Vp(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=xh+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function Xp(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;"SCRIPT"===d?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):"LINK"===d&&(c=a.href);dc()&&a.setAttribute("nonce",dc());return c?(a=V.getEntriesByName(c))&&a[0]&&(a=a[0],c=kp(),Z("rsf_"+b,c+Math.round(a.fetchStart)),Z("rse_"+b,c+Math.round(a.responseEnd)),void 0!==a.transferSize&&0===a.transferSize)?!0:!1:!1}
function Wp(){var a=window.location.protocol,b=V.getEntriesByType("resource");b=eb(b,function(c){return 0===c.name.indexOf(a+"//fonts.gstatic.com/s/")});
(b=gb(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&0<b.startTime&&0<b.responseEnd&&(Z("wffs",jp(b.startTime)),Z("wffe",jp(b.responseEnd)))}
var $p=window;$p.ytcsi&&($p.ytcsi.info=Up,$p.ytcsi.tick=Z);function aq(a,b,c,d){this.l=a;this.I=b;this.j=c;this.o=d;this.i=void 0;this.h=new Map;a.Da||(a.Da={});a.Da=Object.assign(Object.assign({},Uo),a.Da)}
function bq(a,b,c,d){if(void 0!==aq.h){if(d=aq.h,a=[a!==d.l,b!==d.I,c!==d.j,!1,!1,void 0!==d.i],a.some(function(e){return e}))throw new yk("InnerTubeTransportService is already initialized",a);
}else aq.h=new aq(a,b,c,d)}
function cq(){var a=aq.h,b={signalServiceEndpoint:{signal:"GET_DATASYNC_IDS"}};var c=void 0===c?Ao:c;var d=Lo(b,a.l);if(!d)return Of(new yk("Error: No request builder found for command.",b));var e=d.o(b,void 0,c);return e?new Jf(function(f){var g,h,k;return x(function(l){if(1==l.h)return h="cors"===(null===(g=e.wa)||void 0===g?void 0:g.mode)?"cors":void 0,v(l,dq(a,e.config,h),2);k=l.i;f(eq(a,e,k));l.h=0})}):Of(new yk("Error: Failed to build request for command.",b))}
function eq(a,b,c){var d,e,f,g,h,k,l,m,q,w,t,z,B,I,L,N,R;return x(function(W){switch(W.h){case 1:W.s(2);break;case 3:if((l=W.i)&&!l.isExpired())return W.return(Promise.resolve(l.h()));case 2:if((m=null===(d=b.config)||void 0===d?void 0:d.Bo)&&a.h.has(m)&&M("web_memoize_inflight_requests"))return W.return(a.h.get(m));if(null===(e=null===b||void 0===b?void 0:b.aa)||void 0===e?0:e.context)for(q=r([]),w=q.next();!w.done;w=q.next())t=w.value,t.zo(b.aa.context);if(null===(f=a.i)||void 0===f?0:f.l(b.input,
b.aa))return W.return(a.i.j(b.input,b.aa));z=JSON.stringify(b.aa);b.wa=Object.assign(Object.assign({},b.wa),{headers:c});B=Object.assign({},b.wa);"POST"===b.wa.method&&(B=Object.assign(Object.assign({},B),{body:z}));(null===(g=b.config)||void 0===g?0:g.nc)&&Z(b.config.nc);I=a.I.fetch(b.input,B,b.config);m&&a.h.set(m,I);return v(W,I,4);case 4:L=W.i;m&&a.h.has(m)&&a.h.delete(m);(null===(h=b.config)||void 0===h?0:h.oc)&&Z(b.config.oc);if(L||null===(k=a.i)||void 0===k||!k.h(b.input,b.aa)){W.s(5);break}return v(W,
a.i.i(b.input,b.aa),6);case 6:L=W.i;case 5:if(L&&a.o)for(N=r(a.o),w=N.next();!w.done;w=N.next())R=w.value,R.handleResponse(L,b);return W.return(L)}})}
function dq(a,b,c){return x(function(d){if(a.j.Cc){var e=d.return,f,g=null===(f=null===b||void 0===b?void 0:b.Ka)||void 0===f?void 0:f.sessionIndex;f=zo({sessionIndex:g});f=Object.assign(Object.assign({},fq(c)),f);d=e.call(d,f)}else d=d.return(gq(b,c));return d})}
function gq(a,b){var c,d,e;return x(function(f){if(1==f.h){d=null===(c=null===a||void 0===a?void 0:a.Ka)||void 0===c?void 0:c.sessionIndex;var g=zo({sessionIndex:d});if(!(g instanceof Jf)){var h=new Jf(Ja);Kf(h,2,g);g=h}return v(f,g,2)}e=f.i;return f.return(Promise.resolve(Object.assign(Object.assign({},fq(b)),e)))})}
function fq(a){var b={"Content-Type":"application/json"},c=D("VISITOR_DATA");c&&(b["X-Goog-Visitor-Id"]=c);"cors"!==a&&((a=D("INNERTUBE_CONTEXT_CLIENT_NAME"))&&(b["X-Youtube-Client-Name"]=a),(a=D("INNERTUBE_CONTEXT_CLIENT_VERSION"))&&(b["X-Youtube-Client-Version"]=a),(a=D("CHROME_CONNECTED_HEADER"))&&(b["X-Youtube-Chrome-Connected"]=a),M("forward_domain_admin_state_on_embeds")&&(a=D("DOMAIN_ADMIN_STATE"))&&(b["X-Youtube-Domain-Admin-State"]=a));return b}
;var hq=["share/get_web_player_share_panel"],iq=["feedback"],jq=["notification/modify_channel_preference"],kq=["browse/edit_playlist"],lq=["subscription/subscribe"],mq=["subscription/unsubscribe"];function nq(){}
u(nq,Ro);nq.prototype.j=function(){return lq};
nq.prototype.h=function(a){return a.subscribeEndpoint};
nq.prototype.i=function(a,b,c){c=void 0===c?{}:c;b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params);c.botguardResponse&&(a.botguardResponse=c.botguardResponse);c.feature&&(a.clientFeature=c.feature)};
fa.Object.defineProperties(nq.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function oq(){}
u(oq,Ro);oq.prototype.j=function(){return mq};
oq.prototype.h=function(a){return a.unsubscribeEndpoint};
oq.prototype.i=function(a,b){b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params)};
fa.Object.defineProperties(oq.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function pq(){}
u(pq,Ro);pq.prototype.j=function(){return iq};
pq.prototype.h=function(a){return a.feedbackEndpoint};
pq.prototype.i=function(a,b,c){a.feedbackTokens=[];b.feedbackToken&&a.feedbackTokens.push(b.feedbackToken);if(b=b.cpn||c.cpn)a.feedbackContext={cpn:b};a.isFeedbackTokenUnencrypted=!!c.is_feedback_token_unencrypted;a.shouldMerge=!1;c.extra_feedback_tokens&&(a.shouldMerge=!0,a.feedbackTokens=a.feedbackTokens.concat(c.extra_feedback_tokens))};
fa.Object.defineProperties(pq.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function qq(){}
u(qq,Ro);qq.prototype.j=function(){return jq};
qq.prototype.h=function(a){return a.modifyChannelNotificationPreferenceEndpoint};
qq.prototype.i=function(a,b){b.params&&(a.params=b.params);b.secondaryParams&&(a.secondaryParams=b.secondaryParams)};function rq(){}
u(rq,Ro);rq.prototype.j=function(){return kq};
rq.prototype.h=function(a){return a.playlistEditEndpoint};
rq.prototype.i=function(a,b){b.actions&&(a.actions=b.actions);b.params&&(a.params=b.params);b.playlistId&&(a.playlistId=b.playlistId)};function sq(){}
u(sq,Ro);sq.prototype.j=function(){return hq};
sq.prototype.h=function(a){return a.webPlayerShareEntityServiceEndpoint};
sq.prototype.i=function(a,b,c){c=void 0===c?{}:c;b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);c.includeListId&&(a.includeListId=!0)};function tq(){}
tq.prototype.fetch=function(a,b){var c=this,d,e,f;return x(function(g){if(1==g.h){d=new window.Request(a,b);if(M("web_fetch_promise_cleanup_killswitch"))return g.return(Promise.resolve(fetch(d).then(function(h){return c.handleResponse(h)}).catch(function(h){T(h)})));
ta(g,3);return v(g,fetch(d),5)}if(3!=g.h)return e=g.i,g.return(c.handleResponse(e));f=va(g);T(f);return g.return(void 0)})};
tq.prototype.handleResponse=function(a){var b=a.text().then(function(c){return JSON.parse(c.replace(")]}'",""))});
a.redirected||a.ok||(b=b.then(function(c){T(new yk("Error: API fetch failed",a.status,a.url,c));return Object.assign(Object.assign({},c),{errorMetadata:{status:a.status}})}));
return b};var uq;function vq(a){Zl.call(this,1,arguments);this.csn=a}
u(vq,Zl);var hm=new $l("screen-created",vq),wq=[],yq=xq,zq=0;function Aq(a,b,c,d,e,f,g){function h(){T(new yk("newScreen() parent element does not have a VE - rootVe",b))}
var k=yq();f=new Un({veType:b,youtubeData:f});e={cttAuthInfo:e,W:k};if(M("il_via_jspb")){var l=new Hg;l.X(k);Ig(l,f.getAsJspb());c&&c.visualElement?(f=new Jg,c.clientScreenNonce&&G(f,2,c.clientScreenNonce),Kg(f,c.visualElement.getAsJspb()),g&&G(f,4,Gg[g]),H(l,5,f)):c&&h();d&&G(l,3,d);Fp(l,e,a)}else f={csn:k,pageVe:f.getAsJson()},c&&c.visualElement?(f.implicitGesture={parentCsn:c.clientScreenNonce,gesturedVe:c.visualElement.getAsJson()},g&&(f.implicitGesture.gestureType=g)):c&&h(),d&&(f.cloneCsn=d),
a?Fj("screenCreated",f,a,e):P("screenCreated",f,e);em(hm,new vq(k));return k}
function Bq(a,b,c,d){var e=d.filter(function(k){k.csn!==b?(k.csn=b,k=!0):k=!1;return k}),f={cttAuthInfo:co(b),
W:b};d=r(d);for(var g=d.next();!g.done;g=d.next())g=g.value.getAsJson(),(ob(g)||!g.trackingParams&&!g.veType)&&T(Error("Child VE logged with no data"));if(M("il_via_jspb")){var h=new Lg;h.X(b);Ng(h,c.getAsJspb());fb(e,function(k){k=k.getAsJspb();ed(h,3,Fg,k)});
"UNDEFINED_CSN"==b?Cq("visualElementAttached",h,f):Gp(h,f,a)}else c={csn:b,parentVe:c.getAsJson(),childVes:fb(e,function(k){return k.getAsJson()})},"UNDEFINED_CSN"==b?Cq("visualElementAttached",c,f):a?Fj("visualElementAttached",c,a,f):P("visualElementAttached",c,f)}
function xq(){for(var a=Math.random()+"",b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);255<e&&(b[c++]=e&255,e>>=8);b[c++]=e}return Kc(b,3)}
function Cq(a,b,c){wq.push({payloadName:a,payload:b,options:c});zq||(zq=im())}
function jm(a){if(wq){for(var b=r(wq),c=b.next();!c.done;c=b.next())if(c=c.value,c.payload)if(M("il_via_jspb"))switch(c.payload.X(a.csn),c.payloadName){case "screenCreated":Fp(c.payload,c.options);break;case "visualElementAttached":Gp(c.payload,c.options);break;case "visualElementShown":Bp(c.payload,c.options);break;case "visualElementHidden":Cp(c.payload,c.options);break;case "visualElementGestured":Dp(c.payload,c.options);break;case "visualElementStateChanged":Ep(c.payload,c.options);break;default:T(new yk("flushQueue unable to map payloadName to JSPB setter"))}else c.payload.csn=
a.csn,Fj(c.payloadName,c.payload,null,c.options);wq.length=0}zq=0}
;function Dq(){this.i=new Set;this.h=new Set;this.j=new Map}
Dq.prototype.clear=function(){this.i.clear();this.h.clear();this.j.clear()};
Ka(Dq);function Eq(){this.o=[];this.D=[];this.h=[];this.l=[];this.m=[];this.i=new Set;this.u=new Map}
function Fq(a,b,c){c=void 0===c?0:c;b.then(function(d){var e,f;a.i.has(c)&&a.j&&a.j();var g=ao(c),h=Zn(c);g&&h&&((null===(e=null===d||void 0===d?void 0:d.response)||void 0===e?0:e.trackingParams)&&Bq(a.client,g,h,[Vn(d.response.trackingParams)]),(null===(f=null===d||void 0===d?void 0:d.playerResponse)||void 0===f?0:f.trackingParams)&&Bq(a.client,g,h,[Vn(d.playerResponse.trackingParams)]))})}
function Gq(a,b,c,d){d=void 0===d?0:d;if(a.i.has(d))a.o.push([b,c]);else{var e=ao(d);c=c||Zn(d);e&&c&&Bq(a.client,e,c,[b])}}
Eq.prototype.clickCommand=function(a,b,c){var d=a.clickTrackingParams;c=void 0===c?0:c;if(d)if(c=ao(void 0===c?0:c)){a=this.client;var e=Vn(d);var f="INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK";d={cttAuthInfo:co(c),W:c};M("il_via_jspb")?(b=new Og,b.X(c),e=e.getAsJspb(),H(b,2,e),G(b,4,Gg[f]),"UNDEFINED_CSN"==c?Cq("visualElementGestured",b,d):Dp(b,d,a)):(f={csn:c,ve:e.getAsJson(),gestureType:f},b&&(f.clientData=b),"UNDEFINED_CSN"==c?Cq("visualElementGestured",f,d):a?Fj("visualElementGestured",f,
a,d):P("visualElementGestured",f,d));b=!0}else b=!1;else b=!1;return b};
function Hq(a,b,c){c=void 0===c?{}:c;a.i.add(c.layer||0);a.j=function(){Iq(a,b,c);var f=Zn(c.layer);if(f){for(var g=r(a.o),h=g.next();!h.done;h=g.next())h=h.value,Gq(a,h[0],h[1]||f,c.layer);f=r(a.D);for(g=f.next();!g.done;g=f.next()){var k=g.value;g=void 0;g=void 0===g?0:g;h=ao(g);var l=k[0]||Zn(g);if(h&&l){g=a.client;var m=k[1];k={cttAuthInfo:co(h),W:h};M("il_via_jspb")?(m=new Qg,m.X(h),l=l.getAsJspb(),H(m,2,l),"UNDEFINED_CSN"==h?Cq("visualElementStateChanged",m,k):Ep(m,k,g)):(l={csn:h,ve:l.getAsJson(),
clientData:m},"UNDEFINED_CSN"==h?Cq("visualElementStateChanged",l,k):g?Fj("visualElementStateChanged",l,g,k):P("visualElementStateChanged",l,k))}}}};
ao(c.layer)||a.j();if(c.wb)for(var d=r(c.wb),e=d.next();!e.done;e=d.next())Fq(a,e.value,c.layer);else Kn(Error("Delayed screen needs a data promise."))}
function Iq(a,b,c){c=void 0===c?{}:c;c.layer||(c.layer=0);var d=void 0!==c.jc?c.jc:c.layer;var e=ao(d);d=Zn(d);var f;d&&(void 0!==c.parentCsn?f={clientScreenNonce:c.parentCsn,visualElement:d}:e&&"UNDEFINED_CSN"!==e&&(f={clientScreenNonce:e,visualElement:d}));var g,h=D("EVENT_ID");"UNDEFINED_CSN"===e&&h&&(g={servletData:{serializedServletEventId:h}});try{var k=Aq(a.client,b,f,c.vb,c.cttAuthInfo,g,c.to)}catch(l){Ln(l,{Co:b,rootVe:d,parentVisualElement:void 0,qo:e,yo:f,vb:c.vb});Kn(l);return}eo(k,b,
c.layer,c.cttAuthInfo);if((b=e&&"UNDEFINED_CSN"!==e&&d)&&!(b=M("screen_manager_skip_hide_killswitch"))){a:{b=r(Object.values(Tn));for(f=b.next();!f.done;f=b.next())if(ao(f.value)==e){b=!0;break a}b=!1}b=!b}b&&(b=a.client,g=!0,h=(g=void 0===g?!1:g)?16:8,f={cttAuthInfo:co(e),W:e,yb:g},M("il_via_jspb")?(h=new Pg,h.X(e),d=d.getAsJspb(),H(h,2,d),G(h,4,g?16:8),"UNDEFINED_CSN"==e?Cq("visualElementHidden",h,f):Cp(h,f,b)):(d={csn:e,ve:d.getAsJson(),eventType:h},"UNDEFINED_CSN"==e?Cq("visualElementHidden",
d,f):b?Fj("visualElementHidden",d,b,f):P("visualElementHidden",d,f)));a.h[a.h.length-1]&&!a.h[a.h.length-1].csn&&(a.h[a.h.length-1].csn=k||"");Up("csn",k);Dq.getInstance().clear();d=Zn(c.layer);e&&"UNDEFINED_CSN"!==e&&d&&(M("web_mark_root_visible")||M("music_web_mark_root_visible"))&&(e=k,k={cttAuthInfo:co(e),W:e},M("il_via_jspb")?(b=new Pg,b.X(e),f=d.getAsJspb(),H(b,2,f),G(b,4,1),"UNDEFINED_CSN"==e?Cq("visualElementShown",b,k):Bp(b,k,void 0)):(b={csn:e,ve:d.getAsJson(),eventType:1},"UNDEFINED_CSN"==
e?Cq("visualElementShown",b,k):P("visualElementShown",b,k)));a.i.delete(c.layer||0);a.j=void 0;e=r(a.u);for(k=e.next();!k.done;k=e.next())b=r(k.value),k=b.next().value,b=b.next().value,b.has(c.layer)&&d&&Gq(a,k,d,c.layer);for(c=0;c<a.l.length;c++){e=a.l[c];try{e()}catch(l){Kn(l)}}for(c=a.l.length=0;c<a.m.length;c++){e=a.m[c];try{e()}catch(l){Kn(l)}}}
;function Jq(){var a;return x(function(b){if(1==b.h)return v(b,cq(),2);if(a=b.i)return a.errorMetadata?(Kn(Error("Datasync IDs fetch responded with "+a.errorMetadata.code+": "+a.error)),b.return(void 0)):b.return(a.ro);T(Error("Network request to get Datasync IDs failed."));return b.return(void 0)})}
;var Kq=y.caches,Lq;function Mq(a){var b=a.indexOf(":");return-1===b?{Gb:a}:{Gb:a.substring(0,b),datasyncId:a.substring(b+1)}}
function Nq(){return x(function(a){if(void 0!==Lq)return a.return(Lq);Lq=new Promise(function(b){var c;return x(function(d){switch(d.h){case 1:return ta(d,2),v(d,Kq.open("test-only"),4);case 4:return v(d,Kq.delete("test-only"),5);case 5:ua(d,3);break;case 2:if(c=va(d),c instanceof Error&&"SecurityError"===c.name)return b(!1),d.return();case 3:b("caches"in window),d.h=0}})});
return a.return(Lq)})}
function Oq(a){var b,c,d,e,f,g,h;x(function(k){if(1==k.h)return v(k,Nq(),2);if(3!=k.h){if(!k.i)return k.return(!1);b=[];return v(k,Kq.keys(),3)}c=k.i;d=r(c);for(e=d.next();!e.done;e=d.next())f=e.value,g=Mq(f),h=g.datasyncId,!h||a.includes(h)||b.push(Kq.delete(f));return k.return(Promise.all(b).then(function(l){return l.some(function(m){return m})}))})}
;function Pq(){Jq().then(function(a){if(a&&(Il(a),Oq(a),M("clear_user_partitioned_ls"))){var b=void 0===b?{}:b;"_start"in hp("cupls")&&Z("aa",void 0,"cupls");var c=xp();c.cupls&&delete c.cupls;var d={timerName:"cupls",info:{},tick:{},span:{}};vp().push(d);c.cupls=d;np("cupls");fp();mp("cupls").useGel=!0;wp("cupls").info.actionType="cupls";b.cttAuthInfo&&(mp("cupls").cttAuthInfo=b.cttAuthInfo);ph("cuplsTIMING_ACTION","cupls");b=b.startTime;Up("yt_sts","c","cupls");Z("_start",b,"cupls");Sp("cupls");
lp("cupls");Z("cuplss",void 0,"cupls");try{try{var e=!!self.localStorage}catch(q){e=!1}if(e)for(var f=Object.keys(window.localStorage),g=r(f),h=g.next();!h.done;h=g.next()){var k=h.value;var l=k.match(/(.*)::.*::.*/);var m=null!==l?l[1]:void 0;e=m;void 0===e||a.includes(e)||self.localStorage.removeItem(k)}Z("cuplsc",void 0,"cupls")}catch(q){Kn(q),Z("cuplse",void 0,"cupls")}}})}
function Qq(){var a=new Pm;Wh.M(function(){a.G()?Pq():a.i.add("publicytnetworkstatus-online",Pq,!0,void 0,void 0)})}
;function Rq(a){a&&(a.dataset?a.dataset[Sq("loaded")]="true":a.setAttribute("data-loaded","true"))}
function Tq(a,b){return a?a.dataset?a.dataset[Sq(b)]:a.getAttribute("data-"+b):null}
var Uq={};function Sq(a){return Uq[a]||(Uq[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;var Vq=/\.vflset|-vfl[a-zA-Z0-9_+=-]+/,Wq=/-[a-zA-Z]{2,3}_[a-zA-Z]{2,3}(?=(\/|$))/;function Xq(a,b,c){c=void 0===c?null:c;if(window.spf&&spf.script){c="";if(a){var d=a.indexOf("jsbin/"),e=a.lastIndexOf(".js"),f=d+6;-1<d&&-1<e&&e>f&&(c=a.substring(f,e),c=c.replace(Vq,""),c=c.replace(Wq,""),c=c.replace("debug-",""),c=c.replace("tracing-",""))}spf.script.load(a,c,b)}else Yq(a,b,c)}
function Yq(a,b,c){c=void 0===c?null:c;var d=Zq(a),e=document.getElementById(d),f=e&&Tq(e,"loaded"),g=e&&!f;f?b&&b():(b&&(f=Si(d,b),b=""+Oa(b),$q[b]=f),g||(e=ar(a,d,function(){Tq(e,"loaded")||(Rq(e),Vi(d),Mh(Va(Wi,d),0))},c)))}
function ar(a,b,c,d){d=void 0===d?null:d;var e=yd(document,"SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);rd(e,Af(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function br(a){a=Zq(a);var b=document.getElementById(a);b&&(Wi(a),b.parentNode.removeChild(b))}
function cr(a,b){a&&b&&(a=""+Oa(b),(a=$q[a])&&Ui(a))}
function Zq(a){var b=document.createElement("a");ac(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+fc(a)}
var $q={};var dr=[],er=!1;function fr(){if(!M("disable_biscotti_fetch_for_ad_blocker_detection")&&!M("disable_biscotti_fetch_entirely_for_all_web_clients")&&po()&&"1"!=qb()){var a=function(){er=!0;"google_ad_status"in window?ph("DCLKSTAT",1):ph("DCLKSTAT",2)};
try{Xq("//static.doubleclick.net/instream/ad_status.js",a)}catch(b){}dr.push(Wh.M(function(){if(!(er||"google_ad_status"in window)){try{cr("//static.doubleclick.net/instream/ad_status.js",a)}catch(b){}er=!0;ph("DCLKSTAT",3)}},5E3))}}
function gr(){var a=Number(D("DCLKSTAT",0));return isNaN(a)?0:a}
;function hr(){this.state=1;this.h=null}
n=hr.prototype;
n.initialize=function(a,b,c,d){d=void 0===d?!1:d;var e,f;if(a.program){var g=null!==(e=a.interpreterScript)&&void 0!==e?e:null,h=null!==(f=a.interpreterUrl)&&void 0!==f?f:null;if(a.interpreterSafeScript){g=a.interpreterSafeScript;Ab("From proto message. b/166824318");g=g.privateDoNotAccessOrElseSafeScriptWrappedValue||"";var k=xb();g=k?k.createScript(g):g;g=(new Cb(g)).toString()}a.interpreterSafeUrl&&(h=a.interpreterSafeUrl,Ab("From proto message. b/166824318"),h=Gb(h.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue||"").toString());
ir(this,g,h,a.program,b,c,d)}else T(Error("Cannot initialize botguard without program"))};
function ir(a,b,c,d,e,f,g){g=void 0===g?!1:g;c?(a.state=2,Xq(c,function(){var h=0<=c.indexOf("/th/");(h?window.trayride:window.botguard)?jr(a,d,!!g,h,e):(a.state=3,br(c),T(new yk("Unable to load Botguard","from "+c)))},f)):b&&(f=yd(document,"SCRIPT"),f.textContent=b,f.nonce=dc(),document.head.appendChild(f),document.head.removeChild(f),((b=b.includes("trayride"))?window.trayride:window.botguard)?jr(a,d,!!g,b,e):(a.state=4,T(Error("Unable to load Botguard from JS"))))}
n.isInitialized=function(){return!!this.h};
n.getState=function(){return this.state};
function jr(a,b,c,d,e){var f,g;a.state=5;if(M("use_bg_facade"))if(c=d?"trayride":"botguard",window[c])try{var h=new jd({program:b,globalName:c});h.zc.then(function(){a.state=6;e&&e(b)});
kr(a,h)}catch(k){k instanceof Error&&(a.state=7,T(k))}else a.state=7,T(Error("VM not loaded, cannot start"));else if(h=d?null===(f=window.trayride)||void 0===f?void 0:f.ad:null===(g=window.botguard)||void 0===g?void 0:g.bg)if(c)try{kr(a,new h(b,function(){a.state=6;e&&e(b)}))}catch(k){a.state=7,k instanceof Error&&T(k)}else{try{kr(a,new h(b)),a.state=6}catch(k){a.state=7,k instanceof Error&&T(k)}e&&e(b)}else a.state=7,T(Error("Failed to finish initializing VM"))}
n.invoke=function(a){a=void 0===a?{}:a;if(this.h){if(this.h.Nb)return this.h.Nb({ub:a});if(this.h.hot)return this.h.hot(void 0,void 0,a);if(this.h.invoke)return this.h.invoke(void 0,void 0,a);T(Error("VM has unknown interface"))}return null};
n.dispose=function(){kr(this,null);this.state=8};
function kr(a,b){$d(a.h);a.h=b}
;var lr=new hr;function mr(){return lr.isInitialized()}
function nr(a){a=void 0===a?{}:a;return lr.invoke(a)}
;function or(a){var b=this;var c=void 0===c?0:c;var d=void 0===d?Vh():d;this.l=c;this.j=d;this.i=new id;this.h=a;a={};c=r(this.h.entries());for(d=c.next();!d.done;a={xa:a.xa,Fa:a.Fa},d=c.next()){var e=r(d.value);d=e.next().value;e=e.next().value;a.Fa=d;a.xa=e;d=function(f){return function(){f.xa.jb();b.h[f.Fa].Va=!0;b.h.every(function(g){return!0===g.Va})&&b.i.resolve()}}(a);
e=Rh(d,pr(this,a.xa));this.h[a.Fa]=Object.assign(Object.assign({},a.xa),{jb:d,Qa:e})}}
function qr(a){var b=Array.from(a.h.keys()).sort(function(d,e){return pr(a,a.h[e])-pr(a,a.h[d])});
b=r(b);for(var c=b.next();!c.done;c=b.next())c=a.h[c.value],void 0===c.Qa||c.Va||(a.j.U(c.Qa),Rh(c.jb,10))}
or.prototype.cancel=function(){for(var a=r(this.h),b=a.next();!b.done;b=a.next())b=b.value,void 0===b.Qa||b.Va||this.j.U(b.Qa),b.Va=!0;this.i.resolve()};
function pr(a,b){var c;return null!==(c=b.priority)&&void 0!==c?c:a.l}
;function rr(a){this.state=a;this.plugins=[];this.m=void 0}
rr.prototype.install=function(){this.plugins.push.apply(this.plugins,ia(Ea.apply(0,arguments)))};
rr.prototype.transition=function(a,b){var c=this,d=this.D.find(function(f){return f.from===c.state&&f.B===a});
if(d){this.j&&(qr(this.j),this.j=void 0);this.state=a;d=d.action.bind(this);var e=this.plugins.filter(function(f){return f[a]}).map(function(f){return f[a]});
d(sr(this,e,this.m),b)}else throw Error("no transition specified from "+this.state+" to "+a);};
function sr(a,b,c){return function(){var d=Ea.apply(0,arguments),e=b.filter(function(k){var l;return 10===(null!==(l=null!==c&&void 0!==c?c:k.priority)&&void 0!==l?l:0)}),f=b.filter(function(k){var l;
return 10!==(null!==(l=null!==c&&void 0!==c?c:k.priority)&&void 0!==l?l:0)});
Vh();var g={};e=r(e);for(var h=e.next();!h.done;g={Ga:g.Ga},h=e.next())g.Ga=h.value,Th(function(k){return function(){k.Ga.na.apply(k.Ga,ia(d))}}(g));
f=f.map(function(k){var l;return{jb:function(){k.na.apply(k,ia(d))},
priority:null!==(l=null!==c&&void 0!==c?c:k.priority)&&void 0!==l?l:0}});
f.length&&(a.j=new or(f))}}
fa.Object.defineProperties(rr.prototype,{currentState:{configurable:!0,enumerable:!0,get:function(){return this.state}}});function tr(a){rr.call(this,void 0===a?"document_active":a);var b=this;this.m=10;this.h=new Map;this.D=[{from:"document_active",B:"document_disposed_preventable",action:this.u},{from:"document_active",B:"document_disposed",action:this.l},{from:"document_disposed_preventable",B:"document_disposed",action:this.l},{from:"document_disposed_preventable",B:"flush_logs",action:this.o},{from:"document_disposed_preventable",B:"document_active",action:this.i},{from:"document_disposed",B:"flush_logs",action:this.o},
{from:"document_disposed",B:"document_active",action:this.i},{from:"document_disposed",B:"document_disposed",action:function(){}},
{from:"flush_logs",B:"document_active",action:this.i}];window.addEventListener("pagehide",function(c){b.transition("document_disposed",c)});
window.addEventListener("beforeunload",function(c){b.transition("document_disposed_preventable",c)});
M("teardown_lifecycle_skip_unload")||window.addEventListener("unload",function(c){b.transition("document_disposed",c);b.h=new Map})}
u(tr,rr);tr.prototype.u=function(a,b){if(!this.h.get("document_disposed_preventable")&&(a(b),(null===b||void 0===b?0:b.defaultPrevented)||(null===b||void 0===b?0:b.returnValue))){b.returnValue||(b.returnValue=!0);b.defaultPrevented||b.preventDefault();this.h=new Map;this.transition("document_active");return}this.h.set("document_disposed_preventable",!0);this.h.get("document_disposed")?this.transition("flush_logs"):this.transition("document_disposed")};
tr.prototype.l=function(a,b){this.h.get("document_disposed")?this.transition("document_active"):(a(b),this.h.set("document_disposed",!0),this.transition("flush_logs"))};
tr.prototype.o=function(a,b){a(b);this.transition("document_active")};
tr.prototype.i=function(){M("teardown_lifecycle_skip_unload")&&(this.h=new Map)};function ur(a){rr.call(this,void 0===a?"document_visibility_unknown":a);var b=this;this.D=[{from:"document_visibility_unknown",B:"document_visible",action:this.i},{from:"document_visibility_unknown",B:"document_hidden",action:this.h},{from:"document_visibility_unknown",B:"document_foregrounded",action:this.o},{from:"document_visibility_unknown",B:"document_backgrounded",action:this.l},{from:"document_visible",B:"document_hidden",action:this.h},{from:"document_visible",B:"document_foregrounded",action:this.o},
{from:"document_visible",B:"document_visible",action:this.i},{from:"document_foregrounded",B:"document_visible",action:this.i},{from:"document_foregrounded",B:"document_hidden",action:this.h},{from:"document_foregrounded",B:"document_foregrounded",action:this.o},{from:"document_hidden",B:"document_visible",action:this.i},{from:"document_hidden",B:"document_backgrounded",action:this.l},{from:"document_hidden",B:"document_hidden",action:this.h},{from:"document_backgrounded",B:"document_hidden",action:this.h},
{from:"document_backgrounded",B:"document_backgrounded",action:this.l},{from:"document_backgrounded",B:"document_visible",action:this.i}];document.addEventListener("visibilitychange",function(c){"visible"===document.visibilityState?b.transition("document_visible",c):b.transition("document_hidden",c)});
M("visibility_lifecycles_dynamic_backgrounding")&&(window.addEventListener("blur",function(c){b.transition("document_backgrounded",c)}),window.addEventListener("focus",function(c){b.transition("document_foregrounded",c)}))}
u(ur,rr);ur.prototype.i=function(a,b){a(b);M("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_foregrounded")};
ur.prototype.h=function(a,b){a(b);M("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_backgrounded")};
ur.prototype.l=function(a,b){a(b)};
ur.prototype.o=function(a,b){a(b)};function vr(){this.h=new tr;this.i=new ur}
vr.prototype.install=function(){var a=Ea.apply(0,arguments);this.h.install.apply(this.h,ia(a));this.i.install.apply(this.i,ia(a))};function wr(){vr.call(this);var a={};this.install((a.document_disposed={na:this.j},a));a={};this.install((a.flush_logs={na:this.l},a))}
var xr;u(wr,vr);wr.prototype.l=function(){P("finalPayload",{csn:ao()})};
wr.prototype.j=function(){Nn(On)};function yr(){}
yr.getInstance=function(){var a=C("ytglobal.storage_");a||(a=new yr,A("ytglobal.storage_",a,void 0));return a};
yr.prototype.estimate=function(){var a,b,c;return x(function(d){c=navigator;return(null===(a=c.storage)||void 0===a?0:a.estimate)?d.return(c.storage.estimate()):(null===(b=c.webkitTemporaryStorage)||void 0===b?0:b.queryUsageAndQuota)?d.return(zr()):d.return()})};
function zr(){var a=navigator;return new Promise(function(b,c){var d;null!==(d=a.webkitTemporaryStorage)&&void 0!==d&&d.queryUsageAndQuota?a.webkitTemporaryStorage.queryUsageAndQuota(function(e,f){b({usage:e,quota:f})},function(e){c(e)}):c(Error("webkitTemporaryStorage is not supported."))})}
A("ytglobal.storageClass_",yr,void 0);function uk(a,b){var c=this;this.handleError=a;this.h=b;this.i=!1;void 0===self.document||self.addEventListener("beforeunload",function(){c.i=!0});
this.j=Math.random()<=rh("ytidb_transaction_ended_event_rate_limit",.02)}
uk.prototype.logEvent=function(a,b){switch(a){case "IDB_DATA_CORRUPTED":M("idb_data_corrupted_killswitch")||this.h("idbDataCorrupted",b);break;case "IDB_UNEXPECTEDLY_CLOSED":this.h("idbUnexpectedlyClosed",b);break;case "IS_SUPPORTED_COMPLETED":M("idb_is_supported_completed_killswitch")||this.h("idbIsSupportedCompleted",b);break;case "QUOTA_EXCEEDED":Ar(this,b);break;case "TRANSACTION_ENDED":this.j&&this.h("idbTransactionEnded",b);break;case "TRANSACTION_UNEXPECTEDLY_ABORTED":a=Object.assign(Object.assign({},
b),{hasWindowUnloaded:this.i}),this.h("idbTransactionAborted",a)}};
function Ar(a,b){yr.getInstance().estimate().then(function(c){c=Object.assign(Object.assign({},b),{isSw:void 0===self.document,isIframe:self!==self.top,deviceStorageUsageMbytes:Br(null===c||void 0===c?void 0:c.usage),deviceStorageQuotaMbytes:Br(null===c||void 0===c?void 0:c.quota)});a.h("idbQuotaExceeded",c)})}
function Br(a){return"undefined"===typeof a?"-1":String(Math.ceil(a/1048576))}
;var Cr=window;
function Dr(){var a=Cr.uaChPolyfill.state;if(0===a.type)P("clientHintsPolyfillEvent",{clientHintsSupported:!1});else{var b=navigator.userAgent,c=void 0!==a.syntheticUa&&a.syntheticUa===b,d={clientHintsSupported:!0,uaAccessedBeforePolyfill:a.didAccessUaBeforePolyfillAvailable,syntheticUaMatches:c};a.didAccessUaBeforePolyfillAvailable&&(d.uaAccessBeforePolyfillCount=a.uaAccessBeforePolyfillCount,a.firstAccessUaError&&(d.firstUaAccessStack=String(a.firstAccessUaError.stack).replace(/\n/g,""),Kn(a.firstAccessUaError)),
d.polyfillAvailabilityDelayMs=a.polyfillAvailabilityDelay);P("clientHintsPolyfillEvent",d);c||(b={syntheticUa:a.syntheticUa,ua:b},b.brand=a.data.brands.map(function(e){return'"'+e.brand+'"; v="'+e.version+'"'}),b.mobileness=a.data.mobile,a=a.data.values,a.architecture&&(b.platformArchitecture=a.architecture),a.model&&(b.model=a.model),a.platform&&(b.platformBrand=a.platform),a.platformVersion&&(b.platformVersion=a.platformVersion),a.uaFullVersion&&(b.fullVersion=a.uaFullVersion),P("clientHintsPolyfillDiagnostics",
b))}}
var Er=!1;function Fr(){var a;1===(null===(a=Cr.uaChPolyfill)||void 0===a?void 0:a.state.type)?Er||(Cr.uaChPolyfill.onReady=Fr,Er=!0):Cr.uaChPolyfill&&Dr()}
;function Gr(a,b,c){J.call(this);var d=this;c=c||D("POST_MESSAGE_ORIGIN",void 0)||window.document.location.protocol+"//"+window.document.location.hostname;this.j=b||null;this.K="*";this.l=c;this.sessionId=null;this.channel="widget";this.L=!!a;this.A=function(e){a:if(!("*"!=d.l&&e.origin!=d.l||d.j&&e.source!=d.j||"string"!==typeof e.data)){try{var f=JSON.parse(e.data)}catch(g){break a}if(!(null==f||d.L&&(d.sessionId&&d.sessionId!=f.id||d.channel&&d.channel!=f.channel))&&f)switch(f.event){case "listening":"null"!=
e.origin&&(d.l=d.K=e.origin);d.j=e.source;d.sessionId=f.id;d.i&&(d.i(),d.i=null);break;case "command":d.m&&(!d.u||0<=cb(d.u,f.func))&&d.m(f.func,f.args,e.origin)}}};
this.u=this.i=this.m=null;window.addEventListener("message",this.A)}
u(Gr,J);Gr.prototype.sendMessage=function(a,b){if(b=b||this.j){this.sessionId&&(a.id=this.sessionId);this.channel&&(a.channel=this.channel);try{var c=JSON.stringify(a);b.postMessage(c,this.K)}catch(d){Ch(d)}}};
Gr.prototype.H=function(){window.removeEventListener("message",this.A);J.prototype.H.call(this)};function Hr(){this.i=[];this.isReady=!1;this.j={};var a=this.h=new Gr(!!D("WIDGET_ID_ENFORCE")),b=this.lc.bind(this);a.m=b;a.u=null;this.h.channel="widget";if(a=D("WIDGET_ID"))this.h.sessionId=a}
n=Hr.prototype;n.lc=function(a,b,c){"addEventListener"===a&&b?(a=b[0],this.j[a]||"onReady"===a||(this.addEventListener(a,Ir(this,a)),this.j[a]=!0)):this.pb(a,b,c)};
n.pb=function(){};
function Ir(a,b){return function(c){return a.sendMessage(b,c)}}
n.addEventListener=function(){};
n.Zb=function(){this.isReady=!0;this.sendMessage("initialDelivery",this.cb());this.sendMessage("onReady");db(this.i,this.Mb,this);this.i=[]};
n.cb=function(){return null};
function Jr(a,b){a.sendMessage("infoDelivery",b)}
n.Mb=function(a){this.isReady?this.h.sendMessage(a):this.i.push(a)};
n.sendMessage=function(a,b){this.Mb({event:a,info:void 0===b?null:b})};
n.dispose=function(){this.h=null};function Kr(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function Lr(a,b,c){if("string"===typeof a)return{videoId:a,startSeconds:b,suggestedQuality:c};b=["endSeconds","startSeconds","mediaContentUrl","suggestedQuality","videoId"];c={};for(var d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}
function Mr(a,b,c,d){if(Na(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};"string"===typeof a&&16===a.length?b.list="PL"+a:b.playlist=a;return b}
;function Nr(a){Hr.call(this);this.listeners=[];this.api=a;this.addEventListener("onReady",this.onReady.bind(this));this.addEventListener("onVideoProgress",this.wc.bind(this));this.addEventListener("onVolumeChange",this.xc.bind(this));this.addEventListener("onApiChange",this.pc.bind(this));this.addEventListener("onPlaybackQualityChange",this.tc.bind(this));this.addEventListener("onPlaybackRateChange",this.uc.bind(this));this.addEventListener("onStateChange",this.vc.bind(this));this.addEventListener("onWebglSettingsChanged",
this.yc.bind(this))}
u(Nr,Hr);n=Nr.prototype;
n.pb=function(a,b,c){if(this.api.isExternalMethodAvailable(a,c)){b=b||[];if(0<b.length&&Kr(a)){var d=b;if(Na(d[0])&&!Array.isArray(d[0]))var e=d[0];else switch(e={},a){case "loadVideoById":case "cueVideoById":e=Lr(d[0],void 0!==d[1]?Number(d[1]):void 0,d[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":e=d[0];"string"===typeof e&&(e={mediaContentUrl:e,startSeconds:void 0!==d[1]?Number(d[1]):void 0,suggestedQuality:d[2]});b:{if((d=e.mediaContentUrl)&&(d=/\/([ve]|embed)\/([^#?]+)/.exec(d))&&d[2]){d=
d[2];break b}d=null}e.videoId=d;e=Lr(e);break;case "loadPlaylist":case "cuePlaylist":e=Mr(d[0],d[1],d[2],d[3])}b.length=1;b[0]=e}this.api.handleExternalCall(a,b,c);Kr(a)&&Jr(this,this.cb())}};
n.onReady=function(){var a=this.Zb.bind(this);this.h.i=a};
n.addEventListener=function(a,b){this.listeners.push({eventType:a,listener:b});this.api.addEventListener(a,b)};
n.cb=function(){if(!this.api)return null;var a=this.api.getApiInterface();ib(a,"getVideoData");for(var b={apiInterface:a},c=0,d=a.length;c<d;c++){var e=a[c];if(0===e.search("get")||0===e.search("is")){var f=0;0===e.search("get")?f=3:0===e.search("is")&&(f=2);f=e.charAt(f).toLowerCase()+e.substr(f+1);try{var g=this.api[e]();b[f]=g}catch(h){}}}b.videoData=this.api.getVideoData();b.currentTimeLastUpdated_=Date.now()/1E3;return b};
n.vc=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&(a.storyboardFormat=this.api.getStoryboardFormat());Jr(this,a)};
n.tc=function(a){Jr(this,{playbackQuality:a})};
n.uc=function(a){Jr(this,{playbackRate:a})};
n.pc=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],l=this.api.getOption(e,k);b[e][k]=l}}this.sendMessage("apiInfoDelivery",b)};
n.xc=function(){Jr(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
n.wc=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());Jr(this,a)};
n.yc=function(){var a={sphericalProperties:this.api.getSphericalProperties()};Jr(this,a)};
n.dispose=function(){Hr.prototype.dispose.call(this);for(var a=0;a<this.listeners.length;a++){var b=this.listeners[a];this.api.removeEventListener(b.eventType,b.listener)}this.listeners=[]};function Or(a){J.call(this);this.i={};this.started=!1;this.connection=a;this.connection.subscribe("command",this.Ib,this)}
u(Or,J);n=Or.prototype;n.start=function(){this.started||this.h()||(this.started=!0,this.connection.qa("RECEIVING"))};
n.qa=function(a,b){this.started&&!this.h()&&this.connection.qa(a,b)};
n.Ib=function(a,b,c){if(this.started&&!this.h()){var d=b||{};switch(a){case "addEventListener":"string"===typeof d.event&&this.addListener(d.event);break;case "removeEventListener":"string"===typeof d.event&&this.removeListener(d.event);break;default:this.api.isReady()&&this.api.isExternalMethodAvailable(a,c||null)&&(b=Pr(a,b||{}),c=this.api.handleExternalCall(a,b,c||null),(c=Qr(a,c))&&this.qa(a,c))}}};
n.addListener=function(a){if(!(a in this.i)){var b=this.qc.bind(this,a);this.i[a]=b;this.addEventListener(a,b)}};
n.qc=function(a,b){this.started&&!this.h()&&this.connection.qa(a,this.bb(a,b))};
n.bb=function(a,b){if(null!=b)return{value:b}};
n.removeListener=function(a){a in this.i&&(this.removeEventListener(a,this.i[a]),delete this.i[a])};
n.H=function(){var a=this.connection;a.h()||ag(a.i,"command",this.Ib,this);this.connection=null;for(var b in this.i)this.i.hasOwnProperty(b)&&this.removeListener(b);J.prototype.H.call(this)};function Rr(a,b){Or.call(this,b);this.api=a;this.start()}
u(Rr,Or);Rr.prototype.addEventListener=function(a,b){this.api.addEventListener(a,b)};
Rr.prototype.removeEventListener=function(a,b){this.api.removeEventListener(a,b)};
function Pr(a,b){switch(a){case "loadVideoById":return a=Lr(b),[a];case "cueVideoById":return a=Lr(b),[a];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return a=Mr(b),[a];case "cuePlaylist":return a=Mr(b),[a];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];
case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function Qr(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
Rr.prototype.bb=function(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}return Or.prototype.bb.call(this,a,b)};
Rr.prototype.H=function(){Or.prototype.H.call(this);delete this.api};function Sr(a){a=void 0===a?!1:a;J.call(this);this.i=new K(a);be(this,Va($d,this.i))}
Xa(Sr,J);Sr.prototype.subscribe=function(a,b,c){return this.h()?0:this.i.subscribe(a,b,c)};
Sr.prototype.l=function(a,b){this.h()||this.i.ma.apply(this.i,arguments)};function Tr(a,b,c){Sr.call(this);this.j=a;this.destination=b;this.id=c}
u(Tr,Sr);Tr.prototype.qa=function(a,b){this.h()||this.j.qa(this.destination,this.id,a,b)};
Tr.prototype.H=function(){this.destination=this.j=null;Sr.prototype.H.call(this)};function Ur(a,b,c){J.call(this);this.destination=a;this.origin=c;this.i=Jh(window,"message",this.j.bind(this));this.connection=new Tr(this,a,b);be(this,Va($d,this.connection))}
u(Ur,J);Ur.prototype.qa=function(a,b,c,d){this.h()||a!==this.destination||(a={id:b,command:c},d&&(a.data=d),this.destination.postMessage(Cf(a),this.origin))};
Ur.prototype.j=function(a){var b;if(b=!this.h())if(b=a.origin===this.origin)a:{b=this.destination;do{b:{var c=a.source;do{if(c===b){c=!0;break b}if(c===c.parent)break;c=c.parent}while(null!=c);c=!1}if(c){b=!0;break a}b=b.opener}while(null!=b);b=!1}if(b&&(b=a.data,"string"===typeof b)){try{b=JSON.parse(b)}catch(d){return}b.command&&(c=this.connection,c.h()||c.l("command",b.command,b.data,a.origin))}};
Ur.prototype.H=function(){Kh(this.i);this.destination=null;J.prototype.H.call(this)};function Vr(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||sb(b);this.assets=a.assets||{};this.attrs=a.attrs||sb(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
Vr.prototype.clone=function(){var a=new Vr,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];"object"==La(c)?a[b]=sb(c):a[b]=c}return a};var Wr=/cssbin\/(?:debug-)?([a-zA-Z0-9_-]+?)(?:-2x|-web|-rtl|-vfl|.css)/;function Xr(a){a=a||"";if(window.spf){var b=a.match(Wr);spf.style.load(a,b?b[1]:"",void 0)}else Yr(a)}
function Yr(a){var b=Zr(a),c=document.getElementById(b),d=c&&Tq(c,"loaded");d||c&&!d||(c=$r(a,b,function(){Tq(c,"loaded")||(Rq(c),Vi(b),Mh(Va(Wi,b),0))}))}
function $r(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=Af(a);bc(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function Zr(a){var b=yd(document,"A");Ab("This URL is never added to the DOM");ac(b,new Pb(a,Qb));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+fc(a)}
;function as(){J.call(this);this.i=[]}
u(as,J);as.prototype.H=function(){for(;this.i.length;){var a=this.i.pop();a.target.removeEventListener(a.name,a.na,void 0)}J.prototype.H.call(this)};function bs(){as.apply(this,arguments)}
u(bs,as);function cs(a,b,c,d){J.call(this);var e=this;this.L=b;this.webPlayerContextConfig=d;this.Xa=!1;this.api={};this.Ha=this.u=null;this.S=new K;this.i={};this.ga=this.Ia=this.elementId=this.Ya=this.config=null;this.Y=!1;this.l=this.A=null;this.Ja={};this.Qb=["onReady"];this.lastError=null;this.qb=NaN;this.K={};this.Rb=new bs(this);this.sa=0;this.j=this.m=a;be(this,Va($d,this.S));ds(this);es(this);be(this,Va($d,this.Rb));c?this.sa=Mh(function(){e.loadNewVideoConfig(c)},0):d&&(fs(this),gs(this))}
u(cs,J);n=cs.prototype;n.getId=function(){return this.L};
n.loadNewVideoConfig=function(a){if(!this.h()){this.sa&&(Nh(this.sa),this.sa=0);var b=a||{};b instanceof Vr||(b=new Vr(b));this.config=b;this.setConfig(a);gs(this);this.isReady()&&hs(this)}};
function fs(a){var b,c;a.webPlayerContextConfig?c=a.webPlayerContextConfig.rootElementId:c=a.config.attrs.id;a.elementId=c||a.elementId;"video-player"===a.elementId&&(a.elementId=a.L,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.L:a.config.attrs.id=a.L);(null===(b=a.j)||void 0===b?void 0:b.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
n.setConfig=function(a){var b;this.Ya=a;this.config=is(a);fs(this);this.Ia||(this.Ia=js(this,(null===(b=this.config.args)||void 0===b?void 0:b.jsapicallback)||"onYouTubePlayerReady"));this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if(null===(c=this.config)||void 0===c?0:c.attrs)a=this.config.attrs,(c=a.width)&&this.j&&(this.j.style.width=Kd(Number(c)||c)),(a=a.height)&&this.j&&(this.j.style.height=Kd(Number(a)||a))};
function hs(a){var b;a.config&&!0!==a.config.loaded&&(a.config.loaded=!0,!a.config.args||"0"!==a.config.args.autoplay&&0!==a.config.args.autoplay&&!1!==a.config.args.autoplay?a.api.loadVideoByPlayerVars(null!==(b=a.config.args)&&void 0!==b?b:null):a.api.cueVideoByPlayerVars(a.config.args))}
function ks(a){var b=!0,c=ls(a);c&&a.config&&(a=ms(a),b=Tq(c,"version")===a);return b&&!!C("yt.player.Application.create")}
function gs(a){if(!a.h()&&!a.Y){var b=ks(a);if(b&&"html5"===(ls(a)?"html5":null))a.ga="html5",a.isReady()||ns(a);else if(os(a),a.ga="html5",b&&a.l&&a.m)a.m.appendChild(a.l),ns(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.A=function(){c=!0;var d=ps(a,"player_bootstrap_method")?C("yt.player.Application.createAlternate")||C("yt.player.Application.create"):C("yt.player.Application.create");var e=a.config?is(a.config):void 0;d&&d(a.m,e,a.webPlayerContextConfig);ns(a)};
a.Y=!0;b?a.A():(Xq(ms(a),a.A),(b=qs(a))&&Xr(b),rs(a)&&!c&&A("yt.player.Application.create",null,void 0))}}}
function ls(a){var b=ud(a.elementId);!b&&a.j&&a.j.querySelector&&(b=a.j.querySelector("#"+a.elementId));return b}
function ns(a){var b;if(!a.h()){var c=ls(a),d=!1;c&&c.getApiInterface&&c.getApiInterface()&&(d=!0);d?(a.Y=!1,!ps(a,"html5_remove_not_servable_check_killswitch")&&(null===c||void 0===c?0:c.isNotServable)&&a.config&&(null===c||void 0===c?0:c.isNotServable(null===(b=a.config.args)||void 0===b?void 0:b.video_id))||ss(a)):a.qb=Mh(function(){ns(a)},50)}}
function ss(a){ds(a);a.Xa=!0;var b=ls(a);if(b){a.u=ts(a,b,"addEventListener");a.Ha=ts(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=ts(a,b,f))}}for(var g in a.i)a.i.hasOwnProperty(g)&&a.u&&a.u(g,a.i[g]);hs(a);a.Ia&&a.Ia(a.api);a.S.ma("onReady",a.api)}
function ts(a,b,c){var d=b[c];return function(){var e=Ea.apply(0,arguments);try{return a.lastError=null,d.apply(b,e)}catch(f){"sendAbandonmentPing"!==c&&(f.params=c,a.lastError=f,T(f))}}}
function ds(a){a.Xa=!1;if(a.Ha)for(var b in a.i)a.i.hasOwnProperty(b)&&a.Ha(b,a.i[b]);for(var c in a.K)a.K.hasOwnProperty(c)&&Nh(Number(c));a.K={};a.u=null;a.Ha=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.Ya};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
n.isReady=function(){return this.Xa};
function es(a){a.addEventListener("WATCH_LATER_VIDEO_ADDED",function(b){Vi("WATCH_LATER_VIDEO_ADDED",b)});
a.addEventListener("WATCH_LATER_VIDEO_REMOVED",function(b){Vi("WATCH_LATER_VIDEO_REMOVED",b)});
a.addEventListener("onAdAnnounce",function(b){Vi("a11y-announce",b)})}
n.addEventListener=function(a,b){var c=this,d=js(this,b);d&&(0<=cb(this.Qb,a)||this.i[a]||(b=us(this,a),this.u&&this.u(a,b)),this.S.subscribe(a,d),"onReady"===a&&this.isReady()&&Mh(function(){d(c.api)},0))};
n.removeEventListener=function(a,b){this.h()||(b=js(this,b))&&ag(this.S,a,b)};
function js(a,b){var c=b;if("string"===typeof b){if(a.Ja[b])return a.Ja[b];c=function(){var d=Ea.apply(0,arguments),e=C(b);if(e)try{e.apply(y,d)}catch(f){Kn(f)}};
a.Ja[b]=c}return c?c:null}
function us(a,b){var c="ytPlayer"+b+a.L;a.i[b]=c;y[c]=function(d){var e=Mh(function(){if(!a.h()){a.S.ma(b,null!==d&&void 0!==d?d:void 0);var f=a.K,g=String(e);g in f&&delete f[g]}},0);
pb(a.K,String(e))};
return c}
n.getPlayerType=function(){return this.ga||(ls(this)?"html5":null)};
n.getLastError=function(){return this.lastError};
function os(a){a.cancel();ds(a);a.ga=null;a.config&&(a.config.loaded=!1);var b=ls(a);b&&(ks(a)||!rs(a)?a.l=b:(b&&b.destroy&&b.destroy(),a.l=null));if(a.m)for(a=a.m;b=a.firstChild;)a.removeChild(b)}
n.cancel=function(){this.A&&cr(ms(this),this.A);Nh(this.qb);this.Y=!1};
n.H=function(){os(this);if(this.l&&this.config&&this.l.destroy)try{this.l.destroy()}catch(b){Kn(b)}this.Ja=null;for(var a in this.i)this.i.hasOwnProperty(a)&&(y[this.i[a]]=null);this.Ya=this.config=this.api=null;delete this.m;delete this.j;J.prototype.H.call(this)};
function rs(a){var b,c;a=null===(c=null===(b=a.config)||void 0===b?void 0:b.args)||void 0===c?void 0:c.fflags;return!!a&&-1!==a.indexOf("player_destroy_old_version=true")}
function ms(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function qs(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function ps(a,b){var c;if(a.webPlayerContextConfig)var d=a.webPlayerContextConfig.serializedExperimentFlags;else if(null===(c=a.config)||void 0===c?0:c.args)d=a.config.args.fflags;return"true"===gi(d||"","&")[b]}
function is(a){for(var b={},c=r(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]="object"===typeof e?sb(e):e}return b}
;var vs={},ws="player_uid_"+(1E9*Math.random()>>>0);function xs(a,b,c){var d="player";c=void 0===c?!0:c;d="string"===typeof d?ud(d):d;var e=ws+"_"+Oa(d),f=vs[e];if(f&&c)return ys(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new cs(d,e,a,b);vs[e]=f;Vi("player-added",f.api);be(f,function(){delete vs[f.getId()]});
return f.api}
function ys(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var zs=null,As=null,Bs=null;function Cs(){var a=zs.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
;function Ds(a,b,c){a="ST-"+fc(a).toString(36);b=b?lc(b):"";c=c||5;po()&&Kj(a,b,c)}
;function Es(a,b,c){b=void 0===b?{}:b;c=void 0===c?!1:c;var d=D("EVENT_ID");d&&(b.ei||(b.ei=d));if(b){d=a;var e=void 0===e?!0:e;var f=D("VALID_SESSION_TEMPDATA_DOMAINS",[]),g=ic(window.location.href);g&&f.push(g);g=ic(d);if(0<=cb(f,g)||!g&&0==d.lastIndexOf("/",0))if(M("autoescape_tempdata_url")&&(f=document.createElement("a"),ac(f,d),d=f.href),d&&(d=jc(d),f=d.indexOf("#"),d=0>f?d:d.substr(0,f)))if(e&&!b.csn&&(b.itct||b.ved)&&(b=Object.assign({csn:ao()},b)),h){var h=parseInt(h,10);isFinite(h)&&0<h&&
Ds(d,b,h)}else Ds(d,b)}if(c)return!1;if((window.ytspf||{}).enabled)spf.navigate(a);else{var k=void 0===k?{}:k;var l=void 0===l?"":l;var m=void 0===m?window:m;c=m.location;a=mc(a,k)+l;var q=void 0===q?Jd:q;a:{q=void 0===q?Jd:q;for(k=0;k<q.length;++k)if(l=q[k],l instanceof Hd&&l.isValid(a)){q=new nd(a,ld);break a}q=void 0}c.href=qd(q||pd)}return!0}
;A("yt.setConfig",ph,void 0);A("yt.config.set",ph,void 0);A("yt.setMsg",go,void 0);A("yt.msgs.set",go,void 0);A("yt.logging.errors.log",Kn,void 0);
A("writeEmbed",function(){var a=D("PLAYER_CONFIG",void 0);if(!a){var b=D("PLAYER_VARS",void 0);b&&(a={args:b})}xo(!0);"gvn"===a.args.ps&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=D("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);M("embeds_js_api_set_1p_cookie")&&(c=li(window.location.href),c.embedsTokenValue&&(a.args.embedsTokenValue=c.embedsTokenValue));Tp();
if((c=D("WEB_PLAYER_CONTEXT_CONFIGS",void 0))&&"WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER"in c){c=c.WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER;if(!c.serializedForcedExperimentIds){var d=li(window.location.href);d.forced_experiments&&(c.serializedForcedExperimentIds=d.forced_experiments)}zs=xs(a,c,!1)}else zs=xs(a);zs.addEventListener("onVideoDataChange",Cs);a=D("POST_MESSAGE_ID","player");D("ENABLE_JS_API")?Bs=new Nr(zs):D("ENABLE_POST_API")&&"string"===typeof a&&"string"===typeof b&&(As=new Ur(window.parent,
a,b),Bs=new Rr(zs,As.connection));fr();M("ytidb_create_logger_embed_killswitch")||tk();M("flush_gel_on_teardown")&&(a={},xr||(xr=new wr),xr.install((a.flush_logs={na:function(){nj()}},a)));
M("networkless_logging_web_embedded")&&(M("embeds_web_enable_new_nwl")?Wm():cn());M("embeds_enable_ua_ch_polyfill")&&Fr();M("ytidb_clear_embedded_player")&&Wh.M(function(){if(!uq){var e={tb:{feedbackEndpoint:Mo(pq),modifyChannelNotificationPreferenceEndpoint:Mo(qq),playlistEditEndpoint:Mo(rq),subscribeEndpoint:Mo(nq),unsubscribeEndpoint:Mo(oq),webPlayerShareEntityServiceEndpoint:Mo(sq)}},f=M("web_enable_client_location_service")?Io.getInstance():void 0,g=[];f&&g.push(f);if(void 0===h){yo.h||(yo.h=
new yo);var h=yo.h}if(void 0===k){tq.h||(tq.h=new tq);var k=tq.h}bq(e,k,h,g);uq=aq.h}Qq()})},void 0);
var Fs=Ah(function(){Zp();var a=Oj.getInstance(),b=Rj(119),c=1<window.devicePixelRatio;if(document.body&&kf(document.body,"exp-invert-logo"))if(c&&!kf(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!kf(d,"inverted-hdpi")){var e=hf(d);jf(d,e+(0<e.length?" inverted-hdpi":"inverted-hdpi"))}}else!c&&kf(document.body,"inverted-hdpi")&&lf();if(b!=c){b="f"+(Math.floor(119/31)+1);d=Sj(b)||0;d=c?d|67108864:d&-67108865;0==d?delete Nj[b]:(c=d.toString(16),
Nj[b]=c.toString());c=!0;M("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.h;d=[];for(var f in Nj)d.push(f+"="+encodeURIComponent(String(Nj[f])));Kj(b,d.join("&"),63072E3,a.i,c)}Eq.h||(Eq.h=new Eq);a=Eq.h;f=16623;var g=void 0===g?{}:g;Object.values(ho).includes(f)||(T(new yk("createClientScreen() called with a non-page VE",f)),f=83769);g.isHistoryNavigation||a.h.push({rootVe:f,key:g.key||""});a.o=[];a.D=[];g.wb?Hq(a,f,g):Iq(a,f,g)}),Gs=Ah(function(){zs&&zs.sendAbandonmentPing&&zs.sendAbandonmentPing();
D("PL_ATT")&&lr.dispose();for(var a=0,b=dr.length;a<b;a++)Wh.U(dr[a]);dr.length=0;br("//static.doubleclick.net/instream/ad_status.js");er=!1;ph("DCLKSTAT",0);ae(Bs,As);zs&&(zs.removeEventListener("onVideoDataChange",Cs),zs.destroy())});
window.addEventListener?(window.addEventListener("load",Fs),window.addEventListener("unload",Gs)):window.attachEvent&&(window.attachEvent("onload",Fs),window.attachEvent("onunload",Gs));Wa("yt.abuse.player.botguardInitialized",C("yt.abuse.player.botguardInitialized")||mr);Wa("yt.abuse.player.invokeBotguard",C("yt.abuse.player.invokeBotguard")||nr);Wa("yt.abuse.dclkstatus.checkDclkStatus",C("yt.abuse.dclkstatus.checkDclkStatus")||gr);
Wa("yt.player.exports.navigate",C("yt.player.exports.navigate")||Es);Wa("yt.util.activity.init",C("yt.util.activity.init")||Yh);Wa("yt.util.activity.getTimeSinceActive",C("yt.util.activity.getTimeSinceActive")||ai);Wa("yt.util.activity.setTimestamp",C("yt.util.activity.setTimestamp")||Zh);}).call(this);
