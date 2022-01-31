(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
'use strict';var m;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ca(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var da=ca(this);function t(a,b){if(b)a:{var c=da;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
t("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.h=f;ba(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d="jscomp_symbol_"+(1E9*Math.random()>>>0)+"_",e=0;return b});
t("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=da[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ea(aa(this))}})}return a});
function ea(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function u(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];return b?b.call(a):{next:aa(a)}}
function fa(a){if(!(a instanceof Array)){a=u(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
var ha="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},ia=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if("undefined"!=typeof Reflect&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){void 0===e&&(e=c);
e=ha(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),ja;
if("function"==typeof Object.setPrototypeOf)ja=Object.setPrototypeOf;else{var ka;a:{var la={a:!0},ma={};try{ma.__proto__=la;ka=ma.a;break a}catch(a){}ka=!1}ja=ka?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var na=ja;
function v(a,b){a.prototype=ha(b.prototype);a.prototype.constructor=a;if(na)na(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.O=b.prototype}
function oa(){this.u=!1;this.l=null;this.i=void 0;this.h=1;this.A=this.m=0;this.C=this.j=null}
function pa(a){if(a.u)throw new TypeError("Generator is already running");a.u=!0}
oa.prototype.B=function(a){this.i=a};
function qa(a,b){a.j={Xa:b,Za:!0};a.h=a.m||a.A}
oa.prototype.return=function(a){this.j={return:a};this.h=this.A};
function w(a,b,c){a.h=c;return{value:b}}
oa.prototype.o=function(a){this.h=a};
function ra(a,b,c){a.m=b;void 0!=c&&(a.A=c)}
function sa(a){a.m=0;var b=a.j.Xa;a.j=null;return b}
function ta(a){a.C=[a.j];a.m=0;a.A=0}
function ua(a){var b=a.C.splice(0)[0];(b=a.j=a.j||b)?b.Za?a.h=a.m||a.A:void 0!=b.o&&a.A<b.o?(a.h=b.o,a.j=null):a.h=a.A:a.h=0}
function va(a){this.h=new oa;this.i=a}
function wa(a,b){pa(a.h);var c=a.h.l;if(c)return xa(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return ya(a)}
function xa(a,b,c,d){try{var e=b.call(a.h.l,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.u=!1,e;var f=e.value}catch(g){return a.h.l=null,qa(a.h,g),ya(a)}a.h.l=null;d.call(a.h,f);return ya(a)}
function ya(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.u=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,qa(a.h,c)}a.h.u=!1;if(a.h.j){b=a.h.j;a.h.j=null;if(b.Za)throw b.Xa;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function za(a){this.next=function(b){pa(a.h);a.h.l?b=xa(a,a.h.l.next,b,a.h.B):(a.h.B(b),b=ya(a));return b};
this.throw=function(b){pa(a.h);a.h.l?b=xa(a,a.h.l["throw"],b,a.h.B):(qa(a.h,b),b=ya(a));return b};
this.return=function(b){return wa(a,b)};
this[Symbol.iterator]=function(){return this}}
function x(a,b){b=new za(new va(b));na&&a.prototype&&na(b,a.prototype);return b}
t("Reflect",function(a){return a?a:{}});
t("Reflect.construct",function(){return ia});
t("Reflect.setPrototypeOf",function(a){return a?a:na?function(b,c){try{return na(b,c),!0}catch(d){return!1}}:null});
function Aa(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
t("WeakMap",function(a){function b(k){this.h=(h+=Math.random()+1).toString();if(k){k=u(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return"object"===l&&null!==k||"function"===l}
function e(k){if(!Aa(k,g)){var l=new c;ba(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(n){if(n instanceof c)return n;Object.isExtensible(n)&&e(n);return l(n)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),n=new a([[k,2],[l,3]]);if(2!=n.get(k)||3!=n.get(l))return!1;n.delete(k);n.set(l,4);return!n.has(k)&&4==n.get(l)}catch(p){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!Aa(k,g))throw Error("WeakMap key fail: "+k);k[g][this.h]=l;return this};
b.prototype.get=function(k){return d(k)&&Aa(k,g)?k[g][this.h]:void 0};
b.prototype.has=function(k){return d(k)&&Aa(k,g)&&Aa(k[g],this.h)};
b.prototype.delete=function(k){return d(k)&&Aa(k,g)&&Aa(k[g],this.h)?delete k[g][this.h]:!1};
return b});
t("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h.h;return ea(function(){if(l){for(;l.head!=h.h;)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;"object"==l||"function"==l?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var n=h.data_[l];if(n&&Aa(h.data_,l))for(h=0;h<n.length;h++){var p=n[h];if(k!==k&&p.key!==p.key||k===p.key)return{id:l,list:n,index:h,entry:p}}return{id:l,list:n,index:-1,entry:void 0}}
function e(h){this.data_={};this.h=b();this.size=0;if(h){h=u(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(u([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var l=k.entries(),n=l.next();if(n.done||n.value[0]!=h||"s"!=n.value[1])return!1;n=l.next();return n.done||4!=n.value[0].x||"t"!=n.value[1]||!l.next().done?!1:!0}catch(p){return!1}}())return a;
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
function Ba(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
t("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ba(this,b,"endsWith");b+="";void 0===c&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;0<e&&0<c;)if(d[--c]!=b[--e])return!1;return 0>=e}});
t("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
t("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ba(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
t("Object.setPrototypeOf",function(a){return a||na});
var Ca="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)Aa(d,e)&&(a[e]=d[e])}return a};
t("Object.assign",function(a){return a||Ca});
t("Promise",function(a){function b(g){this.h=0;this.j=void 0;this.i=[];this.u=!1;var h=this.l();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(null==this.h){this.h=[];var h=this;this.j(function(){h.A()})}this.h.push(g)};
var e=da.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.A=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.l(l)}}}this.h=null};
c.prototype.l=function(g){this.j(function(){throw g;})};
b.prototype.l=function(){function g(l){return function(n){k||(k=!0,l.call(h,n))}}
var h=this,k=!1;return{resolve:g(this.S),reject:g(this.A)}};
b.prototype.S=function(g){if(g===this)this.A(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.fa(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.L(g):this.m(g)}};
b.prototype.L=function(g){var h=void 0;try{h=g.then}catch(k){this.A(k);return}"function"==typeof h?this.ga(h,g):this.m(g)};
b.prototype.A=function(g){this.B(2,g)};
b.prototype.m=function(g){this.B(1,g)};
b.prototype.B=function(g,h){if(0!=this.h)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.h);this.h=g;this.j=h;2===this.h&&this.T();this.C()};
b.prototype.T=function(){var g=this;e(function(){if(g.J()){var h=da.console;"undefined"!==typeof h&&h.error(g.j)}},1)};
b.prototype.J=function(){if(this.u)return!1;var g=da.CustomEvent,h=da.Event,k=da.dispatchEvent;if("undefined"===typeof k)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=da.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.j;return k(g)};
b.prototype.C=function(){if(null!=this.i){for(var g=0;g<this.i.length;++g)f.i(this.i[g]);this.i=null}};
var f=new c;b.prototype.fa=function(g){var h=this.l();g.qa(h.resolve,h.reject)};
b.prototype.ga=function(g,h){var k=this.l();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(q,r){return"function"==typeof q?function(A){try{l(q(A))}catch(B){n(B)}}:r}
var l,n,p=new b(function(q,r){l=q;n=r});
this.qa(k(g,l),k(h,n));return p};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.qa=function(g,h){function k(){switch(l.h){case 1:g(l.j);break;case 2:h(l.j);break;default:throw Error("Unexpected state: "+l.h);}}
var l=this;null==this.i?f.i(k):this.i.push(k);this.u=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=u(g),n=l.next();!n.done;n=l.next())d(n.value).qa(h,k)})};
b.all=function(g){var h=u(g),k=h.next();return k.done?d([]):new b(function(l,n){function p(A){return function(B){q[A]=B;r--;0==r&&l(q)}}
var q=[],r=0;do q.push(void 0),r++,d(k.value).qa(p(q.length-1),n),k=h.next();while(!k.done)})};
return b});
function Da(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
t("Array.prototype.entries",function(a){return a?a:function(){return Da(this,function(b,c){return[b,c]})}});
t("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)Aa(b,d)&&c.push([d,b[d]]);return c}});
t("Array.prototype.keys",function(a){return a?a:function(){return Da(this,function(b){return b})}});
t("Array.prototype.values",function(a){return a?a:function(){return Da(this,function(b,c){return c})}});
t("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
t("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
t("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==Ba(this,b,"includes").indexOf(b,c||0)}});
t("Set",function(a){function b(c){this.h=new Map;if(c){c=u(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(u([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
t("Array.from",function(a){return a?a:function(b,c,d){c=null!=c?c:function(h){return h};
var e=[],f="undefined"!=typeof Symbol&&Symbol.iterator&&b[Symbol.iterator];if("function"==typeof f){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
t("Number.isNaN",function(a){return a?a:function(b){return"number"===typeof b&&isNaN(b)}});
t("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
t("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)Aa(b,d)&&c.push(b[d]);return c}});
var y=this||self;function z(a,b,c){a=a.split(".");c=c||y;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function C(a,b){a=a.split(".");b=b||y;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b}
function Ea(){}
function Fa(a){a.Ia=void 0;a.getInstance=function(){return a.Ia?a.Ia:a.Ia=new a}}
function Ga(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function Ha(a){var b=Ga(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function Ia(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Ja(a){return Object.prototype.hasOwnProperty.call(a,La)&&a[La]||(a[La]=++Ma)}
var La="closure_uid_"+(1E9*Math.random()>>>0),Ma=0;function Na(a,b,c){return a.call.apply(a.bind,arguments)}
function Oa(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Pa(a,b,c){Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?Pa=Na:Pa=Oa;return Pa.apply(null,arguments)}
function Qa(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function Ra(a,b){z(a,b,void 0)}
function D(a,b){function c(){}
c.prototype=b.prototype;a.O=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.Bm=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function Sa(a){return a}
;function Ta(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,Ta);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));void 0!==b&&(this.pb=b)}
D(Ta,Error);Ta.prototype.name="CustomError";function Ua(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.j=!b&&/[?&]ae=1(&|$)/.test(a);this.l=!b&&/[?&]ae=2(&|$)/.test(a);if((this.h=/[?&]adurl=([^&]*)/.exec(a))&&this.h[1]){try{var c=decodeURIComponent(this.h[1])}catch(d){c=null}this.i=c}}
;function Va(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var Wa=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},E=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},Xa=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f="string"===typeof a?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},Ya=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e="string"===typeof a?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},Za=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
E(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function $a(a,b){a:{for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return 0>b?null:"string"===typeof a?a.charAt(b):a[b]}
function ab(a,b){b=Wa(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c}
function bb(a){var b=a.length;if(0<b){for(var c=Array(b),d=0;d<b;d++)c[d]=a[d];return c}return[]}
function cb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Ha(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function db(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function eb(a){var b=fb,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function gb(a){for(var b in a)return!1;return!0}
function hb(a,b){if(null!==a&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function ib(){var a=F("PLAYER_VARS",{});return null!==a&&"privembed"in a?a.privembed:!1}
function jb(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function kb(a){var b={},c;for(c in a)b[c]=a[c];return b}
function lb(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();if("undefined"!==typeof Map&&a instanceof Map)return new Map(a);if("undefined"!==typeof Set&&a instanceof Set)return new Set(a);var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=lb(a[c]);return b}
var mb="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function nb(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<mb.length;f++)c=mb[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var ob;function pb(){if(void 0===ob){var a=null,b=y.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:Sa,createScript:Sa,createScriptURL:Sa})}catch(c){y.console&&y.console.error(c.message)}ob=a}else ob=a}return ob}
;function qb(a,b){this.h=a===rb&&b||""}
qb.prototype.W=!0;qb.prototype.V=function(){return this.h};
function sb(a){return new qb(rb,a)}
var rb={};sb("");var tb={};function ub(a){this.h=tb===tb?a:"";this.W=!0}
ub.prototype.V=function(){return this.h.toString()};
ub.prototype.toString=function(){return this.h.toString()};function vb(a,b){this.h=b===wb?a:""}
m=vb.prototype;m.W=!0;m.V=function(){return this.h.toString()};
m.Ha=!0;m.Da=function(){return 1};
m.toString=function(){return this.h+""};
function xb(a){if(a instanceof vb&&a.constructor===vb)return a.h;Ga(a);return"type_error:TrustedResourceUrl"}
var wb={};function yb(a){var b=pb();a=b?b.createScriptURL(a):a;return new vb(a,wb)}
;var zb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]},Ab=/&/g,Bb=/</g,Cb=/>/g,Db=/"/g,Eb=/'/g,Fb=/\x00/g,Gb=/[\x00&<>"']/;function Hb(a,b){this.h=b===Ib?a:""}
m=Hb.prototype;m.W=!0;m.V=function(){return this.h.toString()};
m.Ha=!0;m.Da=function(){return 1};
m.toString=function(){return this.h.toString()};
function Jb(a){if(a instanceof Hb&&a.constructor===Hb)return a.h;Ga(a);return"type_error:SafeUrl"}
var Kb=RegExp('^(?:audio/(?:3gpp2|3gpp|aac|L16|midi|mp3|mp4|mpeg|oga|ogg|opus|x-m4a|x-matroska|x-wav|wav|webm)|font/\\w+|image/(?:bmp|gif|jpeg|jpg|png|tiff|webp|x-icon)|video/(?:mpeg|mp4|ogg|webm|quicktime|x-matroska))(?:;\\w+=(?:\\w+|"[\\w;,= ]+"))*$',"i"),Lb=/^data:(.*);base64,[a-z0-9+\/]+=*$/i,Mb=/^(?:(?:https?|mailto|ftp):|[^:/?#]*(?:[/?#]|$))/i,Ib={},Nb=new Hb("about:invalid#zClosurez",Ib);var Ob;a:{var Pb=y.navigator;if(Pb){var Qb=Pb.userAgent;if(Qb){Ob=Qb;break a}}Ob=""}function G(a){return-1!=Ob.indexOf(a)}
;function Rb(){return G("Firefox")||G("FxiOS")}
function Sb(){return(G("Chrome")||G("CriOS"))&&!G("Edge")}
;var Tb={};function Ub(a,b,c){this.h=c===Tb?a:"";this.i=b;this.W=this.Ha=!0}
Ub.prototype.Da=function(){return this.i};
Ub.prototype.V=function(){return this.h.toString()};
Ub.prototype.toString=function(){return this.h.toString()};
function Vb(a,b){var c=pb();a=c?c.createHTML(a):a;return new Ub(a,b,Tb)}
;function Wb(a,b){b instanceof Hb||b instanceof Hb||(b="object"==typeof b&&b.W?b.V():String(b),Mb.test(b)||(b="about:invalid#zClosurez"),b=new Hb(b,Ib));a.href=Jb(b)}
function Xb(a,b){a.rel="stylesheet";a.href=xb(b).toString();(b=Yb('style[nonce],link[rel="stylesheet"][nonce]',a.ownerDocument&&a.ownerDocument.defaultView))&&a.setAttribute("nonce",b)}
function Zb(){return Yb("script[nonce]",void 0)}
var $b=/^[\w+/_-]+[=]{0,2}$/;function Yb(a,b){b=(b||y).document;return b.querySelector?(a=b.querySelector(a))&&(a=a.nonce||a.getAttribute("nonce"))&&$b.test(a)?a:"":""}
;function ac(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var bc=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function cc(a){return a?decodeURI(a):a}
function dc(a){return cc(a.match(bc)[3]||null)}
function ec(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)ec(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function fc(a){var b=[],c;for(c in a)ec(c,a[c],b);return b.join("&")}
function gc(a,b){b=fc(b);if(b){var c=a.indexOf("#");0>c&&(c=a.length);var d=a.indexOf("?");if(0>d||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.substr(0,d),e,a.substr(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;b=a[0]+(a[1]?"?"+a[1]:"")+a[2]}else b=a;return b}
var hc=/#|$/;function I(a,b){var c=void 0;return new (c||(c=Promise))(function(d,e){function f(k){try{h(b.next(k))}catch(l){e(l)}}
function g(k){try{h(b["throw"](k))}catch(l){e(l)}}
function h(k){k.done?d(k.value):(new c(function(l){l(k.value)})).then(f,g)}
h((b=b.apply(a,void 0)).next())})}
;function ic(){return G("iPhone")&&!G("iPod")&&!G("iPad")}
;function jc(a){jc[" "](a);return a}
jc[" "]=Ea;var kc=G("Opera"),lc=G("Trident")||G("MSIE"),mc=G("Edge"),nc=G("Gecko")&&!(-1!=Ob.toLowerCase().indexOf("webkit")&&!G("Edge"))&&!(G("Trident")||G("MSIE"))&&!G("Edge"),oc=-1!=Ob.toLowerCase().indexOf("webkit")&&!G("Edge"),pc=G("Android");function qc(){var a=y.document;return a?a.documentMode:void 0}
var rc;a:{var sc="",tc=function(){var a=Ob;if(nc)return/rv:([^\);]+)(\)|;)/.exec(a);if(mc)return/Edge\/([\d\.]+)/.exec(a);if(lc)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(oc)return/WebKit\/(\S+)/.exec(a);if(kc)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
tc&&(sc=tc?tc[1]:"");if(lc){var uc=qc();if(null!=uc&&uc>parseFloat(sc)){rc=String(uc);break a}}rc=sc}var vc=rc,wc;if(y.document&&lc){var xc=qc();wc=xc?xc:parseInt(vc,10)||void 0}else wc=void 0;var yc=wc;Rb();var zc=ic()||G("iPod"),Ac=G("iPad");!G("Android")||Sb()||Rb();Sb();var Bc=G("Safari")&&!(Sb()||G("Coast")||G("Opera")||G("Edge")||G("Edg/")||G("OPR")||Rb()||G("Silk")||G("Android"))&&!(ic()||G("iPad")||G("iPod"));var Cc={},Dc=null;
function Ec(a){var b=3;Ha(a);void 0===b&&(b=0);if(!Dc){Dc={};for(var c="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),d=["+/=","+/","-_=","-_.","-_"],e=0;5>e;e++){var f=c.concat(d[e].split(""));Cc[e]=f;for(var g=0;g<f.length;g++){var h=f[g];void 0===Dc[h]&&(Dc[h]=g)}}}b=Cc[b];c=Array(Math.floor(a.length/3));d=b[64]||"";for(e=f=0;f<a.length-2;f+=3){var k=a[f],l=a[f+1];h=a[f+2];g=b[k>>2];k=b[(k&3)<<4|l>>4];l=b[(l&15)<<2|h>>6];h=b[h&63];c[e++]=""+g+k+l+h}g=0;h=d;switch(a.length-
f){case 2:g=a[f+1],h=b[(g&15)<<2]||d;case 1:a=a[f],c[e]=""+b[a>>2]+b[(a&3)<<4|g>>4]+h+d}return c.join("")}
;var Fc={Fm:{value:!0,configurable:!0}};var Gc=Object,Hc=Gc.freeze,Ic=[];Array.isArray(Ic)&&!Object.isFrozen(Ic)&&Object.defineProperties(Ic,Fc);Hc.call(Gc,Ic);var K=window;sb("csi.gstatic.com");sb("googleads.g.doubleclick.net");sb("pagead2.googlesyndication.com");sb("partner.googleadservices.com");sb("pubads.g.doubleclick.net");sb("securepubads.g.doubleclick.net");sb("tpc.googlesyndication.com");var Jc={};function Kc(){}
function Lc(a){this.h=a}
v(Lc,Kc);Lc.prototype.toString=function(){return this.h};
var Mc=new Lc("about:invalid#zTSz",Jc);function Nc(a){if(a instanceof Kc)if(a instanceof Lc)a=a.h;else throw Error("");else a=Jb(a);return a}
;/*

 Copyright 2021 The Safevalues Authors
 SPDX-License-Identifier: Apache-2.0
*/
function Oc(a,b){a.src=xb(b);var c;b=(a.ownerDocument&&a.ownerDocument.defaultView||window).document;var d=null===(c=b.querySelector)||void 0===c?void 0:c.call(b,"script[nonce]");(c=d?d.nonce||d.getAttribute("nonce")||"":"")&&a.setAttribute("nonce",c)}
;function Pc(a,b){this.x=void 0!==a?a:0;this.y=void 0!==b?b:0}
m=Pc.prototype;m.clone=function(){return new Pc(this.x,this.y)};
m.equals=function(a){return a instanceof Pc&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
m.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
m.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
m.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
m.scale=function(a,b){this.x*=a;this.y*="number"===typeof b?b:a;return this};function Qc(a,b){this.width=a;this.height=b}
m=Qc.prototype;m.clone=function(){return new Qc(this.width,this.height)};
m.aspectRatio=function(){return this.width/this.height};
m.isEmpty=function(){return!(this.width*this.height)};
m.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
m.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
m.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
m.scale=function(a,b){this.width*=a;this.height*="number"===typeof b?b:a;return this};function Rc(a){var b=document;return"string"===typeof a?b.getElementById(a):a}
function Sc(a,b){db(b,function(c,d){c&&"object"==typeof c&&c.W&&(c=c.V());"style"==d?a.style.cssText=c:"class"==d?a.className=c:"for"==d?a.htmlFor=c:Tc.hasOwnProperty(d)?a.setAttribute(Tc[d],c):0==d.lastIndexOf("aria-",0)||0==d.lastIndexOf("data-",0)?a.setAttribute(d,c):a[d]=c})}
var Tc={cellpadding:"cellPadding",cellspacing:"cellSpacing",colspan:"colSpan",frameborder:"frameBorder",height:"height",maxlength:"maxLength",nonce:"nonce",role:"role",rowspan:"rowSpan",type:"type",usemap:"useMap",valign:"vAlign",width:"width"};function Uc(a,b,c){var d=arguments,e=document,f=d[1],g=Vc(e,String(d[0]));f&&("string"===typeof f?g.className=f:Array.isArray(f)?g.className=f.join(" "):Sc(g,f));2<d.length&&Wc(e,g,d);return g}
function Wc(a,b,c){function d(h){h&&b.appendChild("string"===typeof h?a.createTextNode(h):h)}
for(var e=2;e<c.length;e++){var f=c[e];if(!Ha(f)||Ia(f)&&0<f.nodeType)d(f);else{a:{if(f&&"number"==typeof f.length){if(Ia(f)){var g="function"==typeof f.item||"string"==typeof f.item;break a}if("function"===typeof f){g="function"==typeof f.item;break a}}g=!1}E(g?bb(f):f,d)}}}
function Vc(a,b){b=String(b);"application/xhtml+xml"===a.contentType&&(b=b.toLowerCase());return a.createElement(b)}
function Xc(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;function Yc(a){var b=Zc;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a.call(void 0,b[c],c,b)}
function $c(){var a=[];Yc(function(b){a.push(b)});
return a}
var Zc={ic:"allow-forms",jc:"allow-modals",kc:"allow-orientation-lock",lc:"allow-pointer-lock",mc:"allow-popups",nc:"allow-popups-to-escape-sandbox",oc:"allow-presentation",pc:"allow-same-origin",qc:"allow-scripts",sc:"allow-top-navigation",tc:"allow-top-navigation-by-user-activation"},ad=Va(function(){return $c()});
function bd(){var a=Vc(document,"IFRAME"),b={};E(ad(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
;function cd(a){this.isValid=a}
function dd(a){return new cd(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var ed=[dd("data"),dd("http"),dd("https"),dd("mailto"),dd("ftp"),new cd(function(a){return/^[^:]*([/?#]|$)/.test(a)})];function fd(a){"number"==typeof a&&(a=Math.round(a)+"px");return a}
;var gd=(new Date).getTime();function hd(a){if(!a)return"";a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if("http"!==c&&"https"!==c&&"chrome-extension"!==c&&"moz-extension"!==c&&"file"!==c&&"android-app"!==c&&"chrome-search"!==c&&"chrome-untrusted"!==c&&"chrome"!==
c&&"app"!==c&&"devtools"!==c)throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===c&&"80"!==e||"https"===c&&"443"!==e)a=":"+e}return c+"://"+b+a}
;function id(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;n=l=0}
function b(p){for(var q=g,r=0;64>r;r+=4)q[r/4]=p[r]<<24|p[r+1]<<16|p[r+2]<<8|p[r+3];for(r=16;80>r;r++)p=q[r-3]^q[r-8]^q[r-14]^q[r-16],q[r]=(p<<1|p>>>31)&4294967295;p=e[0];var A=e[1],B=e[2],H=e[3],V=e[4];for(r=0;80>r;r++){if(40>r)if(20>r){var P=H^A&(B^H);var J=1518500249}else P=A^B^H,J=1859775393;else 60>r?(P=A&B|H&(A|B),J=2400959708):(P=A^B^H,J=3395469782);P=((p<<5|p>>>27)&4294967295)+P+V+J+q[r]&4294967295;V=H;H=B;B=(A<<30|A>>>2)&4294967295;A=p;p=P}e[0]=e[0]+p&4294967295;e[1]=e[1]+A&4294967295;e[2]=
e[2]+B&4294967295;e[3]=e[3]+H&4294967295;e[4]=e[4]+V&4294967295}
function c(p,q){if("string"===typeof p){p=unescape(encodeURIComponent(p));for(var r=[],A=0,B=p.length;A<B;++A)r.push(p.charCodeAt(A));p=r}q||(q=p.length);r=0;if(0==l)for(;r+64<q;)b(p.slice(r,r+64)),r+=64,n+=64;for(;r<q;)if(f[l++]=p[r++],n++,64==l)for(l=0,b(f);r+64<q;)b(p.slice(r,r+64)),r+=64,n+=64}
function d(){var p=[],q=8*n;56>l?c(h,56-l):c(h,64-(l-56));for(var r=63;56<=r;r--)f[r]=q&255,q>>>=8;b(f);for(r=q=0;5>r;r++)for(var A=24;0<=A;A-=8)p[q++]=e[r]>>A&255;return p}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var l,n;a();return{reset:a,update:c,digest:d,rb:function(){for(var p=d(),q="",r=0;r<p.length;r++)q+="0123456789ABCDEF".charAt(Math.floor(p[r]/16))+"0123456789ABCDEF".charAt(p[r]%16);return q}}}
;function jd(a,b,c){var d=String(y.location.href);return d&&a&&b?[b,kd(hd(d),a,c||null)].join(" "):null}
function kd(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],E(d,function(h){e.push(h)}),ld(e.join(" "));
var f=[],g=[];E(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];E(d,function(h){e.push(h)});
a=ld(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function ld(a){var b=id();b.update(a);return b.rb().toLowerCase()}
;var md={};function nd(a){this.h=a||{cookie:""}}
m=nd.prototype;m.isEnabled=function(){if(!y.navigator.cookieEnabled)return!1;if(!this.isEmpty())return!0;this.set("TESTCOOKIESENABLED","1",{Ja:60});if("1"!==this.get("TESTCOOKIESENABLED"))return!1;this.remove("TESTCOOKIESENABLED");return!0};
m.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.Km;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.Ja}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString();this.h.cookie=a+"="+b+c+g+h+d+(null!=e?";samesite="+
e:"")};
m.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=zb(d[e]);if(0==f.lastIndexOf(c,0))return f.substr(c.length);if(f==a)return""}return b};
m.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{Ja:0,path:b,domain:c});return d};
m.isEmpty=function(){return!this.h.cookie};
m.clear=function(){for(var a=(this.h.cookie||"").split(";"),b=[],c=[],d,e,f=0;f<a.length;f++)e=zb(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));for(a=b.length-1;0<=a;a--)this.remove(b[a])};
var od=new nd("undefined"==typeof document?null:document);function pd(a){return!!md.FPA_SAMESITE_PHASE2_MOD||!(void 0===a||!a)}
function qd(a){a=void 0===a?!1:a;var b=y.__SAPISID||y.__APISID||y.__3PSAPISID||y.__OVERRIDE_SID;pd(a)&&(b=b||y.__1PSAPISID);if(b)return!0;var c=new nd(document);b=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID")||c.get("SID");pd(a)&&(b=b||c.get("__Secure-1PAPISID"));return!!b}
function rd(a,b,c,d){(a=y[a])||(a=(new nd(document)).get(b));return a?jd(a,c,d):null}
function sd(a){var b=void 0===b?!1:b;var c=hd(String(y.location.href)),d=[];if(qd(b)){c=0==c.indexOf("https:")||0==c.indexOf("chrome-extension:")||0==c.indexOf("moz-extension:");var e=c?y.__SAPISID:y.__APISID;e||(e=new nd(document),e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID"));(e=e?jd(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e);c&&pd(b)&&((b=rd("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=rd("__3PSAPISID","__Secure-3PAPISID","SAPISID3PHASH",a))&&d.push(a))}return 0==
d.length?null:d.join(" ")}
;function td(){this.data_=[];this.h=-1}
td.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&0===a%1&&this.data_[a]!=b&&(this.data_[a]=b,this.h=-1)};
td.prototype.get=function(a){return!!this.data_[a]};
function ud(a){-1==a.h&&(a.h=Za(a.data_,function(b,c,d){return c?b+Math.pow(2,d):b},0));
return a.h}
;function vd(a,b){this.j=a;this.l=b;this.i=0;this.h=null}
vd.prototype.get=function(){if(0<this.i){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function wd(a,b){a.l(b);100>a.i&&(a.i++,b.next=a.h,a.h=b)}
;var xd;
function yd(){var a=y.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!G("Presto")&&(a=function(){var e=Vc(document,"IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=Pa(function(k){if(("*"==h||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!G("Trident")&&!G("MSIE")){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.Ta;c.Ta=null;e()}};
return function(e){d.next={Ta:e};d=d.next;b.port2.postMessage(0)}}return function(e){y.setTimeout(e,0)}}
;function zd(a){y.setTimeout(function(){throw a;},0)}
;function Ad(){this.i=this.h=null}
Ad.prototype.add=function(a,b){var c=Bd.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
Ad.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var Bd=new vd(function(){return new Cd},function(a){return a.reset()});
function Cd(){this.next=this.scope=this.h=null}
Cd.prototype.set=function(a,b){this.h=a;this.scope=b;this.next=null};
Cd.prototype.reset=function(){this.next=this.scope=this.h=null};function Dd(a,b){Ed||Fd();Gd||(Ed(),Gd=!0);Hd.add(a,b)}
var Ed;function Fd(){if(y.Promise&&y.Promise.resolve){var a=y.Promise.resolve(void 0);Ed=function(){a.then(Id)}}else Ed=function(){var b=Id;
"function"!==typeof y.setImmediate||y.Window&&y.Window.prototype&&!G("Edge")&&y.Window.prototype.setImmediate==y.setImmediate?(xd||(xd=yd()),xd(b)):y.setImmediate(b)}}
var Gd=!1,Hd=new Ad;function Id(){for(var a;a=Hd.remove();){try{a.h.call(a.scope)}catch(b){zd(b)}wd(Bd,a)}Gd=!1}
;function Jd(a,b){this.h=a[y.Symbol.iterator]();this.i=b;this.j=0}
Jd.prototype[Symbol.iterator]=function(){return this};
Jd.prototype.next=function(){var a=this.h.next();return{value:a.done?void 0:this.i.call(void 0,a.value,this.j++),done:a.done}};
function Kd(a,b){return new Jd(a,b)}
;function Ld(){this.blockSize=-1}
;function Md(){this.blockSize=-1;this.blockSize=64;this.h=[];this.A=[];this.m=[];this.j=[];this.j[0]=128;for(var a=1;a<this.blockSize;++a)this.j[a]=0;this.l=this.i=0;this.reset()}
D(Md,Ld);Md.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.l=this.i=0};
function Nd(a,b,c){c||(c=0);var d=a.m;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.h[0];c=a.h[1];var g=a.h[2],h=a.h[3],k=a.h[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var l=1518500249}else f=c^g^h,l=1859775393;else 60>e?(f=c&g|h&(c|g),l=2400959708):
(f=c^g^h,l=3395469782);f=(b<<5|b>>>27)+f+k+l+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+g&4294967295;a.h[3]=a.h[3]+h&4294967295;a.h[4]=a.h[4]+k&4294967295}
Md.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.A,f=this.i;d<b;){if(0==f)for(;d<=c;)Nd(this,a,d),d+=this.blockSize;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){Nd(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){Nd(this,e);f=0;break}}this.i=f;this.l+=b}};
Md.prototype.digest=function(){var a=[],b=8*this.l;56>this.i?this.update(this.j,56-this.i):this.update(this.j,this.blockSize-(this.i-56));for(var c=this.blockSize-1;56<=c;c--)this.A[c]=b&255,b/=256;Nd(this,this.A);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function Od(a){var b=C("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||y.$googDebugFname||b}catch(g){e="Not available",c=!0}b=Pd(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,Qd[c])c=Qd[c];else{c=String(c);if(!Qd[c]){var f=/function\s+([^\(]+)/m.exec(c);Qd[c]=f?f[1]:"[Anonymous]"}c=Qd[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return{message:a.message,name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:a.stack}}
function Pd(a,b){b||(b={});b[Rd(a)]=!0;var c=a.stack||"";(a=a.pb)&&!b[Rd(a)]&&(c+="\nCaused by: ",a.stack&&0==a.stack.indexOf(a.toString())||(c+="string"===typeof a?a:a.message+"\n"),c+=Pd(a,b));return c}
function Rd(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var Qd={};function Sd(a){a&&"function"==typeof a.dispose&&a.dispose()}
;function Td(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Ha(d)?Td.apply(null,d):Sd(d)}}
;function L(){this.h=this.h;this.A=this.A}
L.prototype.h=!1;L.prototype.dispose=function(){this.h||(this.h=!0,this.D())};
function Ud(a,b){a.h?b():(a.A||(a.A=[]),a.A.push(b))}
L.prototype.D=function(){if(this.A)for(;this.A.length;)this.A.shift()()};function Vd(a){return"string"==typeof a.className?a.className:a.getAttribute&&a.getAttribute("class")||""}
function Wd(a,b){"string"==typeof a.className?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function Xd(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:Vd(a).match(/\S+/g)||[],b=0<=Wa(a,b));return b}
function Yd(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):Xd(a,"inverted-hdpi")&&Wd(a,Array.prototype.filter.call(a.classList?a.classList:Vd(a).match(/\S+/g)||[],function(b){return"inverted-hdpi"!=b}).join(" "))}
;var Zd="StopIteration"in y?y.StopIteration:{message:"StopIteration",stack:""};function $d(){}
$d.prototype.P=function(){throw Zd;};
$d.prototype.M=function(){return this};function ae(a){if(a instanceof be||a instanceof ce||a instanceof de)return a;if("function"==typeof a.P)return new be(function(){return ee(a)});
if("function"==typeof a[Symbol.iterator])return new be(function(){return a[Symbol.iterator]()});
if("function"==typeof a.M)return new be(function(){return ee(a.M())});
throw Error("Not an iterator or iterable.");}
function ee(a){if(!(a instanceof $d))return a;var b=!1;return{next:function(){for(var c;!b;)try{c=a.P();break}catch(d){if(d!==Zd)throw d;b=!0}return{value:c,done:b}}}}
function be(a){this.i=a}
be.prototype.M=function(){return new ce(this.i())};
be.prototype[Symbol.iterator]=function(){return new de(this.i())};
be.prototype.h=function(){return new de(this.i())};
function ce(a){this.i=a}
v(ce,$d);ce.prototype.P=function(){var a=this.i.next();if(a.done)throw Zd;return a.value};
ce.prototype[Symbol.iterator]=function(){return new de(this.i)};
ce.prototype.h=function(){return new de(this.i)};
function de(a){be.call(this,function(){return a});
this.j=a}
v(de,be);de.prototype.next=function(){return this.j.next()};function fe(a,b){this.i={};this.h=[];this.ba=this.size=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof fe)for(c=ge(a),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
function ge(a){he(a);return a.h.concat()}
m=fe.prototype;m.has=function(a){return ie(this.i,a)};
m.equals=function(a,b){if(this===a)return!0;if(this.size!=a.size)return!1;b=b||je;he(this);for(var c,d=0;c=this.h[d];d++)if(!b(this.get(c),a.get(c)))return!1;return!0};
function je(a,b){return a===b}
m.isEmpty=function(){return 0==this.size};
m.clear=function(){this.i={};this.ba=this.size=this.h.length=0};
m.remove=function(a){return this.delete(a)};
m.delete=function(a){return ie(this.i,a)?(delete this.i[a],--this.size,this.ba++,this.h.length>2*this.size&&he(this),!0):!1};
function he(a){if(a.size!=a.h.length){for(var b=0,c=0;b<a.h.length;){var d=a.h[b];ie(a.i,d)&&(a.h[c++]=d);b++}a.h.length=c}if(a.size!=a.h.length){var e={};for(c=b=0;b<a.h.length;)d=a.h[b],ie(e,d)||(a.h[c++]=d,e[d]=1),b++;a.h.length=c}}
m.get=function(a,b){return ie(this.i,a)?this.i[a]:b};
m.set=function(a,b){ie(this.i,a)||(this.size+=1,this.h.push(a),this.ba++);this.i[a]=b};
m.forEach=function(a,b){for(var c=ge(this),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
m.clone=function(){return new fe(this)};
m.keys=function(){return ae(this.M(!0)).h()};
m.values=function(){return ae(this.M(!1)).h()};
m.entries=function(){var a=this;return Kd(this.keys(),function(b){return[b,a.get(b)]})};
m.M=function(a){he(this);var b=0,c=this.ba,d=this,e=new $d;e.P=function(){if(c!=d.ba)throw Error("The map has changed since the iterator was created");if(b>=d.h.length)throw Zd;var f=d.h[b++];return a?f:d.i[f]};
return e};
function ie(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
;function ke(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
ke.prototype.stopPropagation=function(){this.j=!0};
ke.prototype.preventDefault=function(){this.defaultPrevented=!0};var le=function(){if(!y.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{y.addEventListener("test",Ea,b),y.removeEventListener("test",Ea,b)}catch(c){}return a}();function me(a,b){ke.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
D(me,ke);var ne={2:"touch",3:"pen",4:"mouse"};
me.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;if(b=a.relatedTarget){if(nc){a:{try{jc(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:ne[a.pointerType]||"";this.state=a.state;
this.i=a;a.defaultPrevented&&me.O.preventDefault.call(this)};
me.prototype.stopPropagation=function(){me.O.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
me.prototype.preventDefault=function(){me.O.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var oe="closure_listenable_"+(1E6*Math.random()|0);var pe=0;function qe(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.va=e;this.key=++pe;this.ka=this.oa=!1}
function re(a){a.ka=!0;a.listener=null;a.proxy=null;a.src=null;a.va=null}
;function se(a){this.src=a;this.listeners={};this.h=0}
se.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=te(a,b,d,e);-1<g?(b=a[g],c||(b.oa=!1)):(b=new qe(b,this.src,f,!!d,e),b.oa=c,a.push(b));return b};
se.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=te(e,b,c,d);return-1<b?(re(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.h--),!0):!1};
function ue(a,b){var c=b.type;c in a.listeners&&ab(a.listeners[c],b)&&(re(b),0==a.listeners[c].length&&(delete a.listeners[c],a.h--))}
function te(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.ka&&f.listener==b&&f.capture==!!c&&f.va==d)return e}return-1}
;var ve="closure_lm_"+(1E6*Math.random()|0),we={},xe=0;function ye(a,b,c,d,e){if(d&&d.once)ze(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)ye(a,b[f],c,d,e);else c=Ae(c),a&&a[oe]?a.X(b,c,Ia(d)?!!d.capture:!!d,e):Be(a,b,c,!1,d,e)}
function Be(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Ia(e)?!!e.capture:!!e,h=Ce(a);h||(a[ve]=h=new se(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=De();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)le||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(Ee(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");xe++}}
function De(){function a(c){return b.call(a.src,a.listener,c)}
var b=Fe;return a}
function ze(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)ze(a,b[f],c,d,e);else c=Ae(c),a&&a[oe]?a.i.add(String(b),c,!0,Ia(d)?!!d.capture:!!d,e):Be(a,b,c,!0,d,e)}
function Ge(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Ge(a,b[f],c,d,e);else(d=Ia(d)?!!d.capture:!!d,c=Ae(c),a&&a[oe])?a.i.remove(String(b),c,d,e):a&&(a=Ce(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=te(b,c,d,e)),(c=-1<a?b[a]:null)&&He(c))}
function He(a){if("number"!==typeof a&&a&&!a.ka){var b=a.src;if(b&&b[oe])ue(b.i,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(Ee(c),d):b.addListener&&b.removeListener&&b.removeListener(d);xe--;(c=Ce(b))?(ue(c,a),0==c.h&&(c.src=null,b[ve]=null)):re(a)}}}
function Ee(a){return a in we?we[a]:we[a]="on"+a}
function Fe(a,b){if(a.ka)a=!0;else{b=new me(b,this);var c=a.listener,d=a.va||a.src;a.oa&&He(a);a=c.call(d,b)}return a}
function Ce(a){a=a[ve];return a instanceof se?a:null}
var Ie="__closure_events_fn_"+(1E9*Math.random()>>>0);function Ae(a){if("function"===typeof a)return a;a[Ie]||(a[Ie]=function(b){return a.handleEvent(b)});
return a[Ie]}
;function Je(){L.call(this);this.i=new se(this);this.L=this;this.u=null}
D(Je,L);Je.prototype[oe]=!0;Je.prototype.addEventListener=function(a,b,c,d){ye(this,a,b,c,d)};
Je.prototype.removeEventListener=function(a,b,c,d){Ge(this,a,b,c,d)};
function Ke(a,b){var c=a.u;if(c){var d=[];for(var e=1;c;c=c.u)d.push(c),++e}a=a.L;c=b.type||b;"string"===typeof b?b=new ke(b,a):b instanceof ke?b.target=b.target||a:(e=b,b=new ke(c,a),nb(b,e));e=!0;if(d)for(var f=d.length-1;!b.j&&0<=f;f--){var g=b.h=d[f];e=Le(g,c,!0,b)&&e}b.j||(g=b.h=a,e=Le(g,c,!0,b)&&e,b.j||(e=Le(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=Le(g,c,!1,b)&&e}
Je.prototype.D=function(){Je.O.D.call(this);if(this.i){var a=this.i,b=0,c;for(c in a.listeners){for(var d=a.listeners[c],e=0;e<d.length;e++)++b,re(d[e]);delete a.listeners[c];a.h--}}this.u=null};
Je.prototype.X=function(a,b,c,d){return this.i.add(String(a),b,!1,c,d)};
function Le(a,b,c,d){b=a.i.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.ka&&g.capture==c){var h=g.listener,k=g.va||g.src;g.oa&&ue(a.i,g);e=!1!==h.call(k,d)&&e}}return e&&!d.defaultPrevented}
;function Me(a){Ne();return yb(a)}
var Ne=Ea;function Oe(a){var b=[];Pe(new Qe,a,b);return b.join("")}
function Qe(){}
function Pe(a,b,c){if(null==b)c.push("null");else{if("object"==typeof b){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),Pe(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],"function"!=typeof f&&(c.push(e),Re(d,c),c.push(":"),Pe(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":Re(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var Se={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\x0B":"\\u000b"},Te=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function Re(a,b){b.push('"',a.replace(Te,function(c){var d=Se[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).substr(1),Se[c]=d);return d}),'"')}
;function Ue(a){if(!a)return!1;try{return!!a.$goog_Thenable}catch(b){return!1}}
;function Ve(a){this.h=0;this.u=void 0;this.l=this.i=this.j=null;this.A=this.m=!1;if(a!=Ea)try{var b=this;a.call(void 0,function(c){We(b,2,c)},function(c){We(b,3,c)})}catch(c){We(this,3,c)}}
function Xe(){this.next=this.context=this.onRejected=this.i=this.h=null;this.j=!1}
Xe.prototype.reset=function(){this.context=this.onRejected=this.i=this.h=null;this.j=!1};
var Ye=new vd(function(){return new Xe},function(a){a.reset()});
function Ze(a,b,c){var d=Ye.get();d.i=a;d.onRejected=b;d.context=c;return d}
function $e(a){return new Ve(function(b,c){c(a)})}
Ve.prototype.then=function(a,b,c){return af(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
Ve.prototype.$goog_Thenable=!0;function bf(a,b){return af(a,null,b,void 0)}
Ve.prototype.cancel=function(a){if(0==this.h){var b=new cf(a);Dd(function(){df(this,b)},this)}};
function df(a,b){if(0==a.h)if(a.j){var c=a.j;if(c.i){for(var d=0,e=null,f=null,g=c.i;g&&(g.j||(d++,g.h==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.h&&1==d?df(c,b):(f?(d=f,d.next==c.l&&(c.l=d),d.next=d.next.next):ef(c),ff(c,e,3,b)))}a.j=null}else We(a,3,b)}
function gf(a,b){a.i||2!=a.h&&3!=a.h||hf(a);a.l?a.l.next=b:a.i=b;a.l=b}
function af(a,b,c,d){var e=Ze(null,null,null);e.h=new Ve(function(f,g){e.i=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.onRejected=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof cf?g(h):f(k)}catch(l){g(l)}}:g});
e.h.j=a;gf(a,e);return e.h}
Ve.prototype.C=function(a){this.h=0;We(this,2,a)};
Ve.prototype.J=function(a){this.h=0;We(this,3,a)};
function We(a,b,c){if(0==a.h){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.h=1;a:{var d=c,e=a.C,f=a.J;if(d instanceof Ve){gf(d,Ze(e||Ea,f||null,a));var g=!0}else if(Ue(d))d.then(e,f,a),g=!0;else{if(Ia(d))try{var h=d.then;if("function"===typeof h){jf(d,h,e,f,a);g=!0;break a}}catch(k){f.call(a,k);g=!0;break a}g=!1}}g||(a.u=c,a.h=b,a.j=null,hf(a),3!=b||c instanceof cf||kf(a,c))}}
function jf(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function hf(a){a.m||(a.m=!0,Dd(a.B,a))}
function ef(a){var b=null;a.i&&(b=a.i,a.i=b.next,b.next=null);a.i||(a.l=null);return b}
Ve.prototype.B=function(){for(var a;a=ef(this);)ff(this,a,this.h,this.u);this.m=!1};
function ff(a,b,c,d){if(3==c&&b.onRejected&&!b.j)for(;a&&a.A;a=a.j)a.A=!1;if(b.h)b.h.j=null,lf(b,c,d);else try{b.j?b.i.call(b.context):lf(b,c,d)}catch(e){mf.call(null,e)}wd(Ye,b)}
function lf(a,b,c){2==b?a.i.call(a.context,c):a.onRejected&&a.onRejected.call(a.context,c)}
function kf(a,b){a.A=!0;Dd(function(){a.A&&mf.call(null,b)})}
var mf=zd;function cf(a){Ta.call(this,a)}
D(cf,Ta);cf.prototype.name="cancel";function M(a){L.call(this);this.u=1;this.l=[];this.m=0;this.i=[];this.j={};this.B=!!a}
D(M,L);m=M.prototype;m.subscribe=function(a,b,c){var d=this.j[a];d||(d=this.j[a]=[]);var e=this.u;this.i[e]=a;this.i[e+1]=b;this.i[e+2]=c;this.u=e+3;d.push(e);return e};
function nf(a,b,c,d){if(b=a.j[b]){var e=a.i;(b=b.find(function(f){return e[f+1]==c&&e[f+2]==d}))&&a.ja(b)}}
m.ja=function(a){var b=this.i[a];if(b){var c=this.j[b];0!=this.m?(this.l.push(a),this.i[a+1]=Ea):(c&&ab(c,a),delete this.i[a],delete this.i[a+1],delete this.i[a+2])}return!!b};
m.ca=function(a,b){var c=this.j[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.B)for(e=0;e<c.length;e++){var g=c[e];of(this.i[g+1],this.i[g+2],d)}else{this.m++;try{for(e=0,f=c.length;e<f&&!this.h;e++)g=c[e],this.i[g+1].apply(this.i[g+2],d)}finally{if(this.m--,0<this.l.length&&0==this.m)for(;c=this.l.pop();)this.ja(c)}}return 0!=e}return!1};
function of(a,b,c){Dd(function(){a.apply(b,c)})}
m.clear=function(a){if(a){var b=this.j[a];b&&(b.forEach(this.ja,this),delete this.j[a])}else this.i.length=0,this.j={}};
m.D=function(){M.O.D.call(this);this.clear();this.l.length=0};function pf(a){this.h=a}
pf.prototype.set=function(a,b){void 0===b?this.h.remove(a):this.h.set(a,Oe(b))};
pf.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
pf.prototype.remove=function(a){this.h.remove(a)};function qf(a){this.h=a}
D(qf,pf);function rf(a){this.data=a}
function sf(a){return void 0===a||a instanceof rf?a:new rf(a)}
qf.prototype.set=function(a,b){qf.O.set.call(this,a,sf(b))};
qf.prototype.i=function(a){a=qf.O.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
qf.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function tf(a){this.h=a}
D(tf,qf);tf.prototype.set=function(a,b,c){if(b=sf(b)){if(c){if(c<Date.now()){tf.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Date.now()}tf.O.set.call(this,a,b)};
tf.prototype.i=function(a){var b=tf.O.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Date.now()||c&&c>Date.now())tf.prototype.remove.call(this,a);else return b}};function uf(){}
;function vf(){}
D(vf,uf);vf.prototype[Symbol.iterator]=function(){return ae(this.M(!0)).h()};
vf.prototype.clear=function(){var a=Array.from(this);a=u(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function wf(a){this.h=a}
D(wf,vf);m=wf.prototype;m.isAvailable=function(){if(!this.h)return!1;try{return this.h.setItem("__sak","1"),this.h.removeItem("__sak"),!0}catch(a){return!1}};
m.set=function(a,b){try{this.h.setItem(a,b)}catch(c){if(0==this.h.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
m.get=function(a){a=this.h.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
m.remove=function(a){this.h.removeItem(a)};
m.M=function(a){var b=0,c=this.h,d=new $d;d.P=function(){if(b>=c.length)throw Zd;var e=c.key(b++);if(a)return e;e=c.getItem(e);if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return e};
return d};
m.clear=function(){this.h.clear()};
m.key=function(a){return this.h.key(a)};function xf(){var a=null;try{a=window.localStorage||null}catch(b){}this.h=a}
D(xf,wf);function yf(a,b){this.i=a;this.h=null;var c;if(c=lc)c=!(9<=Number(yc));if(c){zf||(zf=new fe);this.h=zf.get(a);this.h||(b?this.h=document.getElementById(b):(this.h=document.createElement("userdata"),this.h.addBehavior("#default#userData"),document.body.appendChild(this.h)),zf.set(a,this.h));try{this.h.load(this.i)}catch(d){this.h=null}}}
D(yf,vf);var Af={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},zf=null;function Bf(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return Af[b]})}
m=yf.prototype;m.isAvailable=function(){return!!this.h};
m.set=function(a,b){this.h.setAttribute(Bf(a),b);Cf(this)};
m.get=function(a){a=this.h.getAttribute(Bf(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
m.remove=function(a){this.h.removeAttribute(Bf(a));Cf(this)};
m.M=function(a){var b=0,c=this.h.XMLDocument.documentElement.attributes,d=new $d;d.P=function(){if(b>=c.length)throw Zd;var e=c[b++];if(a)return decodeURIComponent(e.nodeName.replace(/\./g,"%")).substr(1);e=e.nodeValue;if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return e};
return d};
m.clear=function(){for(var a=this.h.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);Cf(this)};
function Cf(a){try{a.h.save(a.i)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function Df(a,b){this.i=a;this.h=b+"::"}
D(Df,vf);Df.prototype.set=function(a,b){this.i.set(this.h+a,b)};
Df.prototype.get=function(a){return this.i.get(this.h+a)};
Df.prototype.remove=function(a){this.i.remove(this.h+a)};
Df.prototype.M=function(a){var b=this.i.M(!0),c=this,d=new $d;d.P=function(){for(var e=b.P();e.substr(0,c.h.length)!=c.h;)e=b.P();return a?e.substr(c.h.length):c.i.get(e)};
return d};function Ef(a,b){1<b.length?a[b[0]]=b[1]:1===b.length&&Object.assign(a,b[0])}
;var Ff,Gf,Hf=y.window,If=(null===(Ff=null===Hf||void 0===Hf?void 0:Hf.yt)||void 0===Ff?void 0:Ff.config_)||(null===(Gf=null===Hf||void 0===Hf?void 0:Hf.ytcfg)||void 0===Gf?void 0:Gf.data_)||{};z("yt.config_",If,void 0);function N(a){for(var b=0;b<arguments.length;++b);Ef(If,arguments)}
function F(a,b){return a in If?If[a]:b}
;var Jf=[];function Kf(a){Jf.forEach(function(b){return b(a)})}
function Lf(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){Mf(b)}}:a}
function Mf(a,b,c,d){var e=C("yt.logging.errors.log");e?e(a,"ERROR",b,c,d):(e=F("ERRORS",[]),e.push([a,"ERROR",b,c,d]),N("ERRORS",e));Kf(a)}
function Nf(a,b,c,d){var e=C("yt.logging.errors.log");e?e(a,"WARNING",b,c,d):(e=F("ERRORS",[]),e.push([a,"WARNING",b,c,d]),N("ERRORS",e))}
;var Of=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};z("yt.msgs_",Of,void 0);function Pf(a){Ef(Of,arguments)}
;function O(a){a=Qf(a);return"string"===typeof a&&"false"===a?!1:!!a}
function Rf(a,b){a=Qf(a);return void 0===a&&void 0!==b?b:Number(a||0)}
function Qf(a){var b=F("EXPERIMENTS_FORCED_FLAGS",{});return void 0!==b[a]?b[a]:F("EXPERIMENT_FLAGS",{})[a]}
;var Sf=0,Tf=oc?"webkit":nc?"moz":lc?"ms":kc?"o":"";z("ytDomDomGetNextId",C("ytDomDomGetNextId")||function(){return++Sf},void 0);var Uf={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function Vf(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in Uf||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.h=a.pageX;this.i=a.pageY}}catch(e){}}
function Wf(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.h=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.i=a.clientY+b}}
Vf.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
Vf.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
Vf.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var fb=y.ytEventsEventsListeners||{};z("ytEventsEventsListeners",fb,void 0);var Xf=y.ytEventsEventsCounter||{count:0};z("ytEventsEventsCounter",Xf,void 0);
function Yf(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return eb(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=Ia(e[4])&&Ia(d)&&jb(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
var Zf=Va(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function $f(a,b,c,d){d=void 0===d?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=Yf(a,b,c,d);if(e)return e;e=++Xf.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new Vf(h);if(!Xc(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new Vf(h);
h.currentTarget=a;return c.call(a,h)};
g=Lf(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),Zf()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);fb[e]=[a,b,c,g,d];return e}
function ag(a){a&&("string"==typeof a&&(a=[a]),E(a,function(b){if(b in fb){var c=fb[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?Zf()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete fb[b]}}))}
;var bg=window.ytcsi&&window.ytcsi.now?window.ytcsi.now:window.performance&&window.performance.timing&&window.performance.now&&window.performance.timing.navigationStart?function(){return window.performance.timing.navigationStart+window.performance.now()}:function(){return(new Date).getTime()};function cg(a,b){"function"===typeof a&&(a=Lf(a));return window.setTimeout(a,b)}
function dg(a){window.clearTimeout(a)}
;function eg(a){this.C=a;this.i=null;this.m=0;this.B=null;this.u=0;this.j=[];for(a=0;4>a;a++)this.j.push(0);this.l=0;this.L=$f(window,"mousemove",Pa(this.S,this));a=Pa(this.J,this);"function"===typeof a&&(a=Lf(a));this.T=window.setInterval(a,25)}
D(eg,L);eg.prototype.S=function(a){void 0===a.h&&Wf(a);var b=a.h;void 0===a.i&&Wf(a);this.i=new Pc(b,a.i)};
eg.prototype.J=function(){if(this.i){var a=bg();if(0!=this.m){var b=this.B,c=this.i,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.m);this.j[this.l]=.5<Math.abs((d-this.u)/this.u)?1:0;for(c=b=0;4>c;c++)b+=this.j[c]||0;3<=b&&this.C();this.u=d}this.m=a;this.B=this.i;this.l=(this.l+1)%4}};
eg.prototype.D=function(){window.clearInterval(this.T);ag(this.L)};function fg(){}
function gg(a,b){return hg(a,0,b)}
function ig(a,b){return hg(a,1,b)}
;function jg(){fg.apply(this,arguments)}
v(jg,fg);function kg(){jg.h||(jg.h=new jg);return jg.h}
function hg(a,b,c){void 0!==c&&Number.isNaN(Number(c))&&(c=void 0);var d=C("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):cg(a,c||0)}
function lg(a){if(void 0===a||!Number.isNaN(Number(a))){var b=C("yt.scheduler.instance.cancelJob");b?b(a):dg(a)}}
jg.prototype.start=function(){var a=C("yt.scheduler.instance.start");a&&a()};
jg.prototype.pause=function(){var a=C("yt.scheduler.instance.pause");a&&a()};kg();var mg={};
function ng(a){var b=void 0===a?{}:a;a=void 0===b.Ib?!1:b.Ib;b=void 0===b.tb?!0:b.tb;if(null==C("_lact",window)){var c=parseInt(F("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;z("_lact",c,window);z("_fact",c,window);-1==c&&og();$f(document,"keydown",og);$f(document,"keyup",og);$f(document,"mousedown",og);$f(document,"mouseup",og);a?$f(window,"touchmove",function(){pg("touchmove",200)},{passive:!0}):($f(window,"resize",function(){pg("resize",200)}),b&&$f(window,"scroll",function(){pg("scroll",200)}));
new eg(function(){pg("mouse",100)});
$f(document,"touchstart",og,{passive:!0});$f(document,"touchend",og,{passive:!0})}}
function pg(a,b){mg[a]||(mg[a]=!0,ig(function(){og();mg[a]=!1},b))}
function og(){null==C("_lact",window)&&ng();var a=Date.now();z("_lact",a,window);-1==C("_fact",window)&&z("_fact",a,window);(a=C("ytglobal.ytUtilActivityCallback_"))&&a()}
function qg(){var a=C("_lact",window);return null==a?-1:Math.max(Date.now()-a,0)}
;function rg(){var a=sg;C("yt.ads.biscotti.getId_")||z("yt.ads.biscotti.getId_",a,void 0)}
function tg(a){z("yt.ads.biscotti.lastId_",a,void 0)}
;var ug=/^[\w.]*$/,vg={q:!0,search_query:!0};function wg(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=xg(f[0]||""),h=xg(f[1]||"");g in c?Array.isArray(c[g])?cb(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(p){var k=p,l=f[0],n=String(wg);k.args=[{key:l,value:f[1],query:a,method:yg==n?"unchanged":n}];vg.hasOwnProperty(l)||Nf(k)}}return c}
var yg=String(wg);function zg(a){var b=[];db(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];E(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function Ag(a){"?"==a.charAt(0)&&(a=a.substr(1));return wg(a,"&")}
function Bg(){var a=window.location.href;return-1!=a.indexOf("?")?(a=(a||"").split("#")[0],a=a.split("?",2),Ag(1<a.length?a[1]:a[0])):{}}
function Cg(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=Ag(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);return gc(a,e)+d}
function Dg(a){if(!b)var b=window.location.href;var c=a.match(bc)[1]||null,d=dc(a);c&&d?(a=a.match(bc),b=b.match(bc),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?dc(b)==d&&(Number(b.match(bc)[4]||null)||null)==(Number(a.match(bc)[4]||null)||null):!0;return a}
function xg(a){return a&&a.match(ug)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function Eg(a){var b=Fg;a=void 0===a?C("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=gd;e.flash="0";a:{try{var f=b.h.top.location.href}catch(Ka){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=void 0===g?K:g;try{var h=g.history.length}catch(Ka){h=0}e.u_his=h;K.screen&&(e.u_h=K.screen.height,e.u_w=K.screen.width,e.u_ah=K.screen.availHeight,e.u_aw=K.screen.availWidth,e.u_cd=K.screen.colorDepth);e.u_java=!!K.navigator&&"unknown"!==
typeof K.navigator.javaEnabled&&!!K.navigator.javaEnabled&&K.navigator.javaEnabled();K.navigator&&K.navigator.plugins&&(e.u_nplug=K.navigator.plugins.length);K.navigator&&K.navigator.mimeTypes&&(e.u_nmime=K.navigator.mimeTypes.length)}catch(Ka){}h=b.h;try{var k=h.screenX;var l=h.screenY}catch(Ka){}try{var n=h.outerWidth;var p=h.outerHeight}catch(Ka){}try{var q=h.innerWidth;var r=h.innerHeight}catch(Ka){}try{var A=h.screenLeft;var B=h.screenTop}catch(Ka){}try{q=h.innerWidth,r=h.innerHeight}catch(Ka){}try{var H=
h.screen.availWidth;var V=h.screen.availTop}catch(Ka){}k=[A,B,k,l,H,V,n,p,q,r];l=b.h.top;try{var P=(l||window).document,J="CSS1Compat"==P.compatMode?P.documentElement:P.body;var R=(new Qc(J.clientWidth,J.clientHeight)).round()}catch(Ka){R=new Qc(-12245933,-12245933)}P=R;R={};J=new td;y.SVGElement&&y.document.createElementNS&&J.set(0);l=bd();l["allow-top-navigation-by-user-activation"]&&J.set(1);l["allow-popups-to-escape-sandbox"]&&J.set(2);y.crypto&&y.crypto.subtle&&J.set(3);y.TextDecoder&&y.TextEncoder&&
J.set(4);J=ud(J);R.bc=J;R.bih=P.height;R.biw=P.width;R.brdim=k.join();b=b.i;b=(R.vis={visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,R.wgl=!!K.WebGLRenderingContext,R);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var Fg=new function(){var a=window.document;this.h=window;this.i=a};
z("yt.ads_.signals_.getAdSignalsString",function(a){return zg(Eg(a))},void 0);Date.now();var Gg="XMLHttpRequest"in y?function(){return new XMLHttpRequest}:null;
function Hg(){if(!Gg)return null;var a=Gg();return"open"in a?a:null}
function Ig(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;var Jg={Authorization:"AUTHORIZATION","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL","X-YouTube-Page-Label":"PAGE_BUILD_LABEL",
"X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM"},Kg="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(fa("client_dev_mss_url client_dev_regex_map client_dev_root_url expflag jsfeat jsmode client_rollout_override".split(" "))),Lg=!1;
function Mg(a,b){b=void 0===b?{}:b;var c=Dg(a),d=O("web_ajax_ignore_global_headers_if_set"),e;for(e in Jg){var f=F(Jg[e]);!f||!c&&dc(a)||d&&void 0!==b[e]||(b[e]=f)}if(c||!dc(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!dc(a)){try{var g=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(h){}g&&(b["X-YouTube-Time-Zone"]=g)}if(c||!dc(a))b["X-YouTube-Ad-Signals"]=zg(Eg(void 0));return b}
function Ng(a){var b=window.location.search,c=dc(a);O("debug_handle_relative_url_for_query_forward_killswitch")||c||!Dg(a)||(c=document.location.hostname);var d=cc(a.match(bc)[5]||null);d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=Ag(b),f={};E(Kg,function(g){e[g]&&(f[g]=e[g])});
return Cg(a,f||{},!1)}
function Og(a,b){var c=b.format||"JSON";a=Pg(a,b);var d=Qg(a,b),e=!1,f=Rg(a,function(k){if(!e){e=!0;h&&dg(h);var l=Ig(k),n=null,p=400<=k.status&&500>k.status,q=500<=k.status&&600>k.status;if(l||p||q)n=Sg(a,c,k,b.convertToSafeHtml);if(l)a:if(k&&204==k.status)l=!0;else{switch(c){case "XML":l=0==parseInt(n&&n.return_code,10);break a;case "RAW":l=!0;break a}l=!!n}n=n||{};p=b.context||y;l?b.onSuccess&&b.onSuccess.call(p,k,n):b.onError&&b.onError.call(p,k,n);b.onFinish&&b.onFinish.call(p,k,n)}},b.method,
d,b.headers,b.responseType,b.withCredentials);
if(b.onTimeout&&0<b.timeout){var g=b.onTimeout;var h=cg(function(){e||(e=!0,f.abort(),dg(h),g.call(b.context||y,f))},b.timeout)}return f}
function Pg(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=F("XSRF_FIELD_NAME",void 0);if(b=b.urlParams)b[c]&&delete b[c],a=Cg(a,b||{},!0);return a}
function Qg(a,b){var c=F("XSRF_FIELD_NAME",void 0),d=F("XSRF_TOKEN",void 0),e=b.postBody||"",f=b.postParams,g=F("XSRF_FIELD_NAME",void 0),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||dc(a)&&!b.withCredentials&&dc(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);f&&"string"===typeof e&&(e=Ag(e),nb(e,f),e=b.postBodyFormat&&"JSON"==b.postBodyFormat?JSON.stringify(e):fc(e));f=e||f&&!gb(f);!Lg&&f&&
"POST"!=b.method&&(Lg=!0,Mf(Error("AJAX request with postData should use POST")));return e}
function Sg(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,Nf(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?Tg(a):null)e={},E(a.getElementsByTagName("*"),function(g){e[g.tagName]=Ug(g)})}d&&Vg(e);
return e}
function Vg(a){if(Ia(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;sb("HTML that is escaped and sanitized server-side and passed through yt.net.ajax");var d=Vb(a[b],null);a[c]=d}else Vg(a[b])}}
function Tg(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function Ug(a){var b="";E(a.childNodes,function(c){b+=c.nodeValue});
return b}
function Rg(a,b,c,d,e,f,g){function h(){4==(k&&"readyState"in k?k.readyState:0)&&b&&Lf(b)(k)}
c=void 0===c?"GET":c;d=void 0===d?"":d;var k=Hg();if(!k)return null;"onloadend"in k?k.addEventListener("loadend",h,!1):k.onreadystatechange=h;O("debug_forward_web_query_parameters")&&(a=Ng(a));k.open(c,a,!0);f&&(k.responseType=f);g&&(k.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=Mg(a,e))for(var l in e)k.setRequestHeader(l,e[l]),"content-type"==l.toLowerCase()&&(c=!1);c&&k.setRequestHeader("Content-Type","application/x-www-form-urlencoded");k.send(d);
return k}
;var Wg=zc||Ac;function Xg(a){var b=Ob;return b?0<=b.toLowerCase().indexOf(a):!1}
;var Yg={},Zg=0;
function $g(a,b,c,d,e){e=void 0===e?"":e;if(a)if(c&&!Xg("cobalt")){if(a){a instanceof Hb||(a="object"==typeof a&&a.W?a.V():String(a),Mb.test(a)?a=new Hb(a,Ib):(a=String(a),a=a.replace(/(%0A|%0D)/g,""),a=(b=a.match(Lb))&&Kb.test(b[1])?new Hb(a,Ib):null));b=Jb(a||Nb);if("about:invalid#zClosurez"===b||b.startsWith("data"))a="";else{if(b instanceof Ub)a=b;else{var f="object"==typeof b;a=null;f&&b.Ha&&(a=b.Da());b=f&&b.W?b.V():String(b);Gb.test(b)&&(-1!=b.indexOf("&")&&(b=b.replace(Ab,"&amp;")),-1!=b.indexOf("<")&&
(b=b.replace(Bb,"&lt;")),-1!=b.indexOf(">")&&(b=b.replace(Cb,"&gt;")),-1!=b.indexOf('"')&&(b=b.replace(Db,"&quot;")),-1!=b.indexOf("'")&&(b=b.replace(Eb,"&#39;")),-1!=b.indexOf("\x00")&&(b=b.replace(Fb,"&#0;")));a=Vb(b,a)}a instanceof Ub&&a.constructor===Ub?a=a.h:(Ga(a),a="type_error:SafeHtml");a=encodeURIComponent(String(Oe(a.toString())))}/^[\s\xa0]*$/.test(a)||(a=Uc("IFRAME",{src:'javascript:"<body><img src=\\""+'+a+'+"\\"></body>"',style:"display:none"}),(9==a.nodeType?a:a.ownerDocument||a.document).body.appendChild(a))}}else if(e)Rg(a,
b,"POST",e,d);else if(F("USE_NET_AJAX_FOR_PING_TRANSPORT",!1)||d)Rg(a,b,"GET","",d);else{b:{try{var g=new Ua({url:a});if(g.j&&g.i||g.l){var h=cc(a.match(bc)[5]||null),k;if(!(k=!h||!h.endsWith("/aclk"))){var l=a.search(hc);d:{for(c=0;0<=(c=a.indexOf("ri",c))&&c<l;){var n=a.charCodeAt(c-1);if(38==n||63==n){var p=a.charCodeAt(c+2);if(!p||61==p||38==p||35==p){var q=c;break d}}c+=3}q=-1}if(0>q)var r=null;else{var A=a.indexOf("&",q);if(0>A||A>l)A=l;q+=3;r=decodeURIComponent(a.substr(q,A-q).replace(/\+/g,
" "))}k="1"!==r}f=!k;break b}}catch(B){}f=!1}f?ah(a)?(b&&b(),f=!0):f=!1:f=!1;f||bh(a,b)}}
function ch(a,b,c){c=void 0===c?"":c;ah(a,c)?b&&b():$g(a,b,void 0,void 0,c)}
function ah(a,b){try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,void 0===b?"":b))return!0}catch(c){}return!1}
function bh(a,b){var c=new Image,d=""+Zg++;Yg[d]=c;c.onload=c.onerror=function(){b&&Yg[d]&&b();delete Yg[d]};
c.src=a}
;var dh=y.ytPubsubPubsubInstance||new M,eh=y.ytPubsubPubsubSubscribedKeys||{},fh=y.ytPubsubPubsubTopicToKeys||{},gh=y.ytPubsubPubsubIsSynchronous||{};function hh(a,b){var c=ih();if(c&&b){var d=c.subscribe(a,function(){var e=arguments;var f=function(){eh[d]&&b.apply&&"function"==typeof b.apply&&b.apply(window,e)};
try{gh[a]?f():cg(f,0)}catch(g){Mf(g)}},void 0);
eh[d]=!0;fh[a]||(fh[a]=[]);fh[a].push(d);return d}return 0}
function jh(a){var b=ih();b&&("number"===typeof a?a=[a]:"string"===typeof a&&(a=[parseInt(a,10)]),E(a,function(c){b.unsubscribeByKey(c);delete eh[c]}))}
function kh(a,b){var c=ih();c&&c.publish.apply(c,arguments)}
function lh(a){var b=ih();if(b)if(b.clear(a),a)mh(a);else for(var c in fh)mh(c)}
function ih(){return y.ytPubsubPubsubInstance}
function mh(a){fh[a]&&(a=fh[a],E(a,function(b){eh[b]&&delete eh[b]}),a.length=0)}
M.prototype.subscribe=M.prototype.subscribe;M.prototype.unsubscribeByKey=M.prototype.ja;M.prototype.publish=M.prototype.ca;M.prototype.clear=M.prototype.clear;z("ytPubsubPubsubInstance",dh,void 0);z("ytPubsubPubsubTopicToKeys",fh,void 0);z("ytPubsubPubsubIsSynchronous",gh,void 0);z("ytPubsubPubsubSubscribedKeys",eh,void 0);var nh=window,Q=nh.ytcsi&&nh.ytcsi.now?nh.ytcsi.now:nh.performance&&nh.performance.timing&&nh.performance.now&&nh.performance.timing.navigationStart?function(){return nh.performance.timing.navigationStart+nh.performance.now()}:function(){return(new Date).getTime()};var oh=Rf("initial_gel_batch_timeout",2E3),ph=Math.pow(2,16)-1,qh=void 0,rh=0,sh=0,th=0,uh=!0,vh=y.ytLoggingTransportGELQueue_||new Map;z("ytLoggingTransportGELQueue_",vh,void 0);var wh=y.ytLoggingTransportTokensToCttTargetIds_||{};z("ytLoggingTransportTokensToCttTargetIds_",wh,void 0);
function xh(a,b){if("log_event"===a.endpoint){var c="";a.sa?c="visitorOnlyApprovedKey":a.cttAuthInfo&&(wh[a.cttAuthInfo.token]=yh(a.cttAuthInfo),c=a.cttAuthInfo.token);var d=vh.get(c)||[];vh.set(c,d);d.push(a.payload);b&&(qh=new b);a=Rf("tvhtml5_logging_max_batch")||Rf("web_logging_max_batch")||100;b=Q();d.length>=a?zh({writeThenSend:!0},O("flush_only_full_queue")?c:void 0):10<=b-th&&(Ah(),th=b)}}
function Bh(a,b){if("log_event"===a.endpoint){var c="";a.sa?c="visitorOnlyApprovedKey":a.cttAuthInfo&&(wh[a.cttAuthInfo.token]=yh(a.cttAuthInfo),c=a.cttAuthInfo.token);var d=new Map;d.set(c,[a.payload]);b&&(qh=new b);return new Ve(function(e){qh&&qh.isReady()?Ch(d,e,{bypassNetworkless:!0},!0):e()})}}
function zh(a,b){a=void 0===a?{}:a;new Ve(function(c){dg(rh);dg(sh);sh=0;if(qh&&qh.isReady())if(void 0!==b){var d=new Map,e=vh.get(b)||[];d.set(b,e);Ch(d,c,a);vh.delete(b)}else Ch(vh,c,a),vh.clear();else Ah(),c()})}
function Ah(){O("web_gel_timeout_cap")&&!sh&&(sh=cg(function(){zh({writeThenSend:!0})},6E4));
dg(rh);var a=F("LOGGING_BATCH_TIMEOUT",Rf("web_gel_debounce_ms",1E4));O("shorten_initial_gel_batch_timeout")&&uh&&(a=oh);rh=cg(function(){zh({writeThenSend:!0})},a)}
function Ch(a,b,c,d){var e=qh;c=void 0===c?{}:c;var f=Math.round(Q()),g=a.size;a=u(a);for(var h=a.next();!h.done;h=a.next()){var k=u(h.value);h=k.next().value;var l=k=k.next().value;k=lb({context:Dh(e.config_||Eh())});k.events=l;(l=wh[h])&&Fh(k,h,l);delete wh[h];h="visitorOnlyApprovedKey"===h;Gh(k,f,h);O("always_send_and_write")&&(c.writeThenSend=!1);O("send_beacon_before_gel")&&window.navigator&&window.navigator.sendBeacon&&!c.writeThenSend&&ch("/generate_204");Hh(e,"log_event",k,{retry:!0,onSuccess:function(){g--;
g||b()},
onError:function(){g--;g||b()},
eb:c,sa:h,Cm:!!d});uh=!1}}
function Gh(a,b,c){a.requestTimeMs=String(b);O("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=F("EVENT_ID",void 0))&&((c=F("BATCH_CLIENT_COUNTER",void 0)||0)||(c=Math.floor(Math.random()*ph/2)),c++,c>ph&&(c=1),N("BATCH_CLIENT_COUNTER",c),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function Fh(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function yh(a){var b={};a.videoId?b.videoId=a.videoId:a.playlistId&&(b.playlistId=a.playlistId);return b}
;var Ih=y.ytLoggingGelSequenceIdObj_||{};z("ytLoggingGelSequenceIdObj_",Ih,void 0);
function Jh(a,b,c,d){d=void 0===d?{}:d;var e={},f=Math.round(d.timestamp||Q());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;a=qg();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};O("log_sequence_info_on_gel_web")&&d.aa&&(a=e.context,b=d.aa,Ih[b]=b in Ih?Ih[b]+1:0,a.sequence={index:Ih[b],groupKey:b},d.ub&&delete Ih[d.aa]);(d.Lm?Bh:xh)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,sa:d.sa},c)}
;function Kh(){if(!y.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return y.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":y.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":y.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":y.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function Lh(a,b,c,d,e){od.set(""+a,b,{Ja:c,path:"/",domain:void 0===d?"youtube.com":d,secure:void 0===e?!1:e})}
;var Mh=C("ytglobal.prefsUserPrefsPrefs_")||{};z("ytglobal.prefsUserPrefsPrefs_",Mh,void 0);function Nh(){this.h=F("ALT_PREF_COOKIE_NAME","PREF");this.i=F("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=od.get(""+this.h,void 0);if(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(Mh[d]=c.toString())}}}
Nh.prototype.get=function(a,b){Oh(a);Ph(a);a=void 0!==Mh[a]?Mh[a].toString():null;return null!=a?a:b?b:""};
Nh.prototype.set=function(a,b){Oh(a);Ph(a);if(null==b)throw Error("ExpectedNotNull");Mh[a]=b.toString()};
Nh.prototype.remove=function(a){Oh(a);Ph(a);delete Mh[a]};
Nh.prototype.clear=function(){for(var a in Mh)delete Mh[a]};
function Ph(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function Oh(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function Qh(a){a=void 0!==Mh[a]?Mh[a].toString():null;return null!=a&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
Fa(Nh);var Rh={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},Sh={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};
function Th(){var a=y.navigator;return a?a.connection:void 0}
;function Uh(){return"INNERTUBE_API_KEY"in If&&"INNERTUBE_API_VERSION"in If}
function Eh(){return{innertubeApiKey:F("INNERTUBE_API_KEY",void 0),innertubeApiVersion:F("INNERTUBE_API_VERSION",void 0),wb:F("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),xb:F("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),innertubeContextClientVersion:F("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0),zb:F("INNERTUBE_CONTEXT_HL",void 0),yb:F("INNERTUBE_CONTEXT_GL",void 0),Ab:F("INNERTUBE_HOST_OVERRIDE",void 0)||"",Cb:!!F("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),Bb:!!F("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:F("SERIALIZED_CLIENT_CONFIG_DATA",void 0)}}
function Dh(a){var b={client:{hl:a.zb,gl:a.yb,clientName:a.xb,clientVersion:a.innertubeContextClientVersion,configInfo:a.wb}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=y.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=F("EXPERIMENTS_TOKEN","");""!==c&&(b.client.experimentsToken=c);c=[];var d=F("EXPERIMENTS_FORCED_FLAGS",{});for(e in d)c.push({key:e,value:String(d[e])});var e=F("EXPERIMENT_FLAGS",{});for(var f in e)f.startsWith("force_")&&void 0===
d[f]&&c.push({key:f,value:String(e[f])});0<c.length&&(b.request={internalExperimentFlags:c});f=b.client.clientName;if("WEB"===f||"MWEB"===f||1===f||2===f){if(!O("web_include_display_mode_killswitch")){var g;b.client.mainAppWebInfo=null!=(g=b.client.mainAppWebInfo)?g:{};b.client.mainAppWebInfo.webDisplayMode=Kh()}}else if(g=b.client.clientName,("WEB_REMIX"===g||76===g)&&!O("music_web_display_mode_killswitch")){var h;b.client.cb=null!=(h=b.client.cb)?h:{};b.client.cb.webDisplayMode=Kh()}a.appInstallData&&
(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.appInstallData=a.appInstallData);F("DELEGATED_SESSION_ID")&&!O("pageid_as_header_web")&&(b.user={onBehalfOfUser:F("DELEGATED_SESSION_ID")});a:{if(h=Th()){a=Rh[h.type||"unknown"]||"CONN_UNKNOWN";h=Rh[h.effectiveType||"unknown"]||"CONN_UNKNOWN";"CONN_CELLULAR_UNKNOWN"===a&&"CONN_UNKNOWN"!==h&&(a=h);if("CONN_UNKNOWN"!==a)break a;if("CONN_UNKNOWN"!==h){a=h;break a}}a=void 0}a&&(b.client.connectionType=a);O("web_log_effective_connection_type")&&
(a=Th(),a=null!==a&&void 0!==a&&a.effectiveType?Sh.hasOwnProperty(a.effectiveType)?Sh[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN":void 0,a&&(b.client.effectiveConnectionType=a));a=Object;h=a.assign;g=b.client;f={};e=u(Object.entries(Ag(F("DEVICE",""))));for(c=e.next();!c.done;c=e.next())d=u(c.value),c=d.next().value,d=d.next().value,"cbrand"===c?f.deviceMake=d:"cmodel"===c?f.deviceModel=d:"cbr"===c?f.browserName=d:"cbrver"===c?f.browserVersion=d:"cos"===c?f.osName=d:"cosver"===c?f.osVersion=
d:"cplatform"===c&&(f.platform=d);b.client=h.call(a,g,f);return b}
function Vh(a,b,c){c=void 0===c?{}:c;var d={"X-Goog-Visitor-Id":c.visitorData||F("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;(b=c.Am||F("AUTHORIZATION"))||(a?b="Bearer "+C("gapi.auth.getToken")().zm:b=sd([]));b&&(d.Authorization=b,d["X-Goog-AuthUser"]=F("SESSION_INDEX",0),O("pageid_as_header_web")&&(d["X-Goog-PageId"]=F("DELEGATED_SESSION_ID")));return d}
;function Wh(a){a=Object.assign({},a);delete a.Authorization;var b=sd();if(b){var c=new Md;c.update(F("INNERTUBE_API_KEY",void 0));c.update(b);a.hash=Ec(c.digest())}return a}
;function Xh(a){var b=new xf;(b=b.isAvailable()?a?new Df(b,a):b:null)||(a=new yf(a||"UserDataSharedStore"),b=a.isAvailable()?a:null);this.h=(a=b)?new tf(a):null;this.i=document.domain||window.location.hostname}
Xh.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape(Oe(b))}catch(f){return}else e=escape(b);Lh(a,e,c,this.i)};
Xh.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=od.get(""+a,void 0))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
Xh.prototype.remove=function(a){this.h&&this.h.remove(a);var b=this.i;od.remove(""+a,"/",void 0===b?"youtube.com":b)};var Yh;function Zh(){Yh||(Yh=new Xh("yt.innertube"));return Yh}
function $h(a,b,c,d){if(d)return null;d=Zh().get("nextId",!0)||1;var e=Zh().get("requests",!0)||{};e[d]={method:a,request:b,authState:Wh(c),requestTime:Math.round(Q())};Zh().set("nextId",d+1,86400,!0);Zh().set("requests",e,86400,!0);return d}
function ai(a){var b=Zh().get("requests",!0)||{};delete b[a];Zh().set("requests",b,86400,!0)}
function bi(a){var b=Zh().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(Q())-d.requestTime)){var e=d.authState,f=Wh(Vh(!1));jb(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(Q())),Hh(a,d.method,e,{}));delete b[c]}}Zh().set("requests",b,86400,!0)}}
;var ci=function(){var a;return function(){a||(a=new Xh("ytidb"));return a}}();
function di(){var a;return null===(a=ci())||void 0===a?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
function ei(a){this.h=void 0===a?!1:a;(a=di())||(a={hasSucceededOnce:this.h});this.i=a;var b,c;null!==(b=ci())&&void 0!==b&&b.h&&(b={hasSucceededOnce:this.i.hasSucceededOnce||this.h},null===(c=ci())||void 0===c?void 0:c.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0))}
ei.prototype.isSupported=function(){return this.h};var fi=[],gi=!1;function hi(a){gi||(fi.push({type:"ERROR",payload:a}),10<fi.length&&fi.shift())}
function ii(a,b){gi||(fi.push({type:"EVENT",eventType:a,payload:b}),10<fi.length&&fi.shift())}
;function ji(a,b){for(var c=[],d=1;d<arguments.length;++d)c[d-1]=arguments[d];d=Error.call(this,a);this.message=d.message;"stack"in d&&(this.stack=d.stack);this.args=[].concat(fa(c))}
v(ji,Error);function ki(){try{return li(),!0}catch(a){return!1}}
function li(){if(void 0!==F("DATASYNC_ID",void 0))return F("DATASYNC_ID",void 0);throw new ji("Datasync ID not set","unknown");}
;function mi(a){if(0<=a.indexOf(":"))throw Error("Database name cannot contain ':'");}
function ni(a){return a.substr(0,a.indexOf(":"))||a}
;var oi={},pi=(oi.AUTH_INVALID="No user identifier specified.",oi.EXPLICIT_ABORT="Transaction was explicitly aborted.",oi.IDB_NOT_SUPPORTED="IndexedDB is not supported.",oi.MISSING_INDEX="Index not created.",oi.MISSING_OBJECT_STORE="Object store not created.",oi.DB_DELETED_BY_MISSING_OBJECT_STORE="Database is deleted because an expected object store was not created.",oi.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",oi.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",
oi.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",oi.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",oi.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",oi),qi={},ri=(qi.AUTH_INVALID="ERROR",qi.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",qi.EXPLICIT_ABORT="IGNORED",qi.IDB_NOT_SUPPORTED="ERROR",qi.MISSING_INDEX="WARNING",qi.MISSING_OBJECT_STORE="ERROR",qi.DB_DELETED_BY_MISSING_OBJECT_STORE=
"WARNING",qi.QUOTA_EXCEEDED="WARNING",qi.QUOTA_MAYBE_EXCEEDED="WARNING",qi.UNKNOWN_ABORT="WARNING",qi.INCOMPATIBLE_DB_VERSION="WARNING",qi),si={},ti=(si.AUTH_INVALID=!1,si.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,si.EXPLICIT_ABORT=!1,si.IDB_NOT_SUPPORTED=!1,si.MISSING_INDEX=!1,si.MISSING_OBJECT_STORE=!1,si.DB_DELETED_BY_MISSING_OBJECT_STORE=!1,si.QUOTA_EXCEEDED=!1,si.QUOTA_MAYBE_EXCEEDED=!0,si.UNKNOWN_ABORT=!0,si.INCOMPATIBLE_DB_VERSION=!1,si);
function S(a,b,c,d,e){b=void 0===b?{}:b;c=void 0===c?pi[a]:c;d=void 0===d?ri[a]:d;e=void 0===e?ti[a]:e;ji.call(this,c,Object.assign({name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,S.prototype)}
v(S,ji);function ui(a){S.call(this,"MISSING_OBJECT_STORE",{Eb:a},pi.MISSING_OBJECT_STORE);Object.setPrototypeOf(this,ui.prototype)}
v(ui,S);function vi(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,vi.prototype)}
v(vi,Error);var wi=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function xi(a,b,c,d){b=ni(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof S)return e;if("QuotaExceededError"===e.name)return new S("QUOTA_EXCEEDED",{objectStoreNames:c,dbName:b});if(Bc&&"UnknownError"===e.name)return new S("QUOTA_MAYBE_EXCEEDED",{objectStoreNames:c,dbName:b});if(e instanceof vi)return new S("MISSING_INDEX",{dbName:b,dbVersion:d,objectStore:e.objectStore,index:e.index});if("InvalidStateError"===e.name&&wi.some(function(f){return e.message.includes(f)}))return new S("EXECUTE_TRANSACTION_ON_CLOSED_DB",
{objectStoreNames:c,
dbName:b});if("AbortError"===e.name)return new S("UNKNOWN_ABORT",{objectStoreNames:c,dbName:b},e.message);e.args=[{name:"IdbError",Hm:e.name,dbName:b,objectStoreNames:c}];e.level="WARNING";return e}
function yi(a,b,c){return new S("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c}})}
;function zi(a){if(!a)throw Error();throw a;}
function Ai(a){return a}
function Bi(a){this.h=a}
function T(a){function b(e){if("PENDING"===d.state.status){d.state={status:"REJECTED",reason:e};e=u(d.onRejected);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if("PENDING"===d.state.status){d.state={status:"FULFILLED",value:e};e=u(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.h=[];this.onRejected=[];a=a.h;try{a(c,b)}catch(e){b(e)}}
T.all=function(a){return new T(new Bi(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={ea:0};f.ea<a.length;f={ea:f.ea},++f.ea)Ci(T.resolve(a[f.ea]).then(function(g){return function(h){d[g.ea]=h;e--;0===e&&b(d)}}(f)),function(g){c(g)})}))};
T.resolve=function(a){return new T(new Bi(function(b,c){a instanceof T?a.then(b,c):b(a)}))};
T.reject=function(a){return new T(new Bi(function(b,c){c(a)}))};
T.prototype.then=function(a,b){var c=this,d=null!==a&&void 0!==a?a:Ai,e=null!==b&&void 0!==b?b:zi;return new T(new Bi(function(f,g){"PENDING"===c.state.status?(c.h.push(function(){Di(c,c,d,f,g)}),c.onRejected.push(function(){Ei(c,c,e,f,g)})):"FULFILLED"===c.state.status?Di(c,c,d,f,g):"REJECTED"===c.state.status&&Ei(c,c,e,f,g)}))};
function Ci(a,b){a.then(void 0,b)}
function Di(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof T?Fi(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Ei(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof T?Fi(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Fi(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof T?Fi(a,b,f,d,e):d(f)},function(f){e(f)})}
;function Gi(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function Hi(a){return new Promise(function(b,c){Gi(a,b,c)})}
function Ii(a){return new T(new Bi(function(b,c){Gi(a,b,c)}))}
;function Ji(a,b){return new T(new Bi(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;function Ki(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(Q());this.i=!1}
m=Ki.prototype;m.add=function(a,b,c){return Li(this,[a],{mode:"readwrite",K:!0},function(d){return d.objectStore(a).add(b,c)})};
m.clear=function(a){return Li(this,[a],{mode:"readwrite",K:!0},function(b){return b.objectStore(a).clear()})};
m.close=function(){var a;this.h.close();(null===(a=this.options)||void 0===a?0:a.closed)&&this.options.closed()};
m.count=function(a,b){return Li(this,[a],{mode:"readonly",K:!0},function(c){return c.objectStore(a).count(b)})};
function Mi(a,b,c){a=a.h.createObjectStore(b,c);return new Ni(a)}
m.delete=function(a,b){return Li(this,[a],{mode:"readwrite",K:!0},function(c){return c.objectStore(a).delete(b)})};
m.get=function(a,b){return Li(this,[a],{mode:"readonly",K:!0},function(c){return c.objectStore(a).get(b)})};
function Oi(a,b){return Li(a,["LogsRequestsStore"],{mode:"readwrite",K:!0},function(c){c=c.objectStore("LogsRequestsStore");return Ii(c.h.put(b,void 0))})}
m.objectStoreNames=function(){return Array.from(this.h.objectStoreNames)};
function Li(a,b,c,d){return I(a,function f(){var g=this,h,k,l,n,p,q,r,A,B,H,V,P;return x(f,function(J){switch(J.h){case 1:var R={mode:"readonly",K:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};"string"===typeof c?R.mode=c:Object.assign(R,c);h=R;g.transactionCount++;k=h.K?3:1;l=0;case 2:if(n){J.o(3);break}l++;p=Math.round(Q());ra(J,4);q=g.h.transaction(b,h.mode);R=new Pi(q);R=Qi(R,d);return w(J,R,6);case 6:return r=J.i,A=Math.round(Q()),Ri(g,p,A,l,void 0,b.join(),h),J.return(r);case 4:B=sa(J);H=Math.round(Q());
V=xi(B,g.h.name,b.join(),g.h.version);if((P=V instanceof S&&!V.h)||l>=k)Ri(g,p,H,l,V,b.join(),h),n=V;J.o(2);break;case 3:return J.return(Promise.reject(n))}})})}
function Ri(a,b,c,d,e,f,g){b=c-b;e?(e instanceof S&&("QUOTA_EXCEEDED"===e.type||"QUOTA_MAYBE_EXCEEDED"===e.type)&&ii("QUOTA_EXCEEDED",{dbName:ni(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof S&&"UNKNOWN_ABORT"===e.type&&(c-=a.j,0>c&&c>=Math.pow(2,31)&&(c=0),ii("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.i=!0),Si(a,!1,d,f,b,g.tag),hi(e)):Si(a,!0,d,f,b,g.tag)}
function Si(a,b,c,d,e,f){ii("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c,tag:void 0===f?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
m.getName=function(){return this.h.name};
function Ni(a){this.h=a}
m=Ni.prototype;m.add=function(a,b){return Ii(this.h.add(a,b))};
m.autoIncrement=function(){return this.h.autoIncrement};
m.clear=function(){return Ii(this.h.clear()).then(function(){})};
m.count=function(a){return Ii(this.h.count(a))};
function Ti(a,b){return Ui(a,{query:b},function(c){return c.delete().then(function(){return c.continue()})}).then(function(){})}
m.delete=function(a){return a instanceof IDBKeyRange?Ti(this,a):Ii(this.h.delete(a))};
m.get=function(a){return Ii(this.h.get(a))};
m.index=function(a){try{return new Vi(this.h.index(a))}catch(b){if(b instanceof Error&&"NotFoundError"===b.name)throw new vi(a,this.h.name);throw b;}};
m.getName=function(){return this.h.name};
m.keyPath=function(){return this.h.keyPath};
function Ui(a,b,c){a=a.h.openCursor(b.query,b.direction);return Wi(a).then(function(d){return Ji(d,c)})}
function Pi(a){var b=this;this.h=a;this.j=new Map;this.i=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.i){e=S;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(null===k)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function Qi(a,b){var c=new Promise(function(d,e){try{Ci(b(a).then(function(f){d(f)}),e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return u(d).next().value})}
Pi.prototype.abort=function(){this.h.abort();this.i=!0;throw new S("EXPLICIT_ABORT");};
Pi.prototype.objectStore=function(a){a=this.h.objectStore(a);var b=this.j.get(a);b||(b=new Ni(a),this.j.set(a,b));return b};
function Vi(a){this.h=a}
m=Vi.prototype;m.count=function(a){return Ii(this.h.count(a))};
m.delete=function(a){return Xi(this,{query:a},function(b){return b.delete().then(function(){return b.continue()})})};
m.get=function(a){return Ii(this.h.get(a))};
m.getKey=function(a){return Ii(this.h.getKey(a))};
m.keyPath=function(){return this.h.keyPath};
m.unique=function(){return this.h.unique};
function Xi(a,b,c){a=a.h.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return Wi(a).then(function(d){return Ji(d,c)})}
function Yi(a,b){this.request=a;this.cursor=b}
function Wi(a){return Ii(a).then(function(b){return b?new Yi(a,b):null})}
m=Yi.prototype;m.advance=function(a){this.cursor.advance(a);return Wi(this.request)};
m.continue=function(a){this.cursor.continue(a);return Wi(this.request)};
m.delete=function(){return Ii(this.cursor.delete()).then(function(){})};
m.getKey=function(){return this.cursor.key};
m.getValue=function(){return this.cursor.value};
m.update=function(a){return Ii(this.cursor.update(a))};function Zi(a,b,c){return new Promise(function(d,e){function f(){q||(q=new Ki(g.result,{closed:p}));return q}
var g=void 0!==b?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.blocked,k=c.blocking,l=c.Tb,n=c.upgrade,p=c.closed,q;g.addEventListener("upgradeneeded",function(r){try{if(null===r.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(null===g.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");r.dataLoss&&"none"!==r.dataLoss&&ii("IDB_DATA_CORRUPTED",{reason:r.dataLossMessage||"unknown reason",dbName:ni(a)});var A=f(),B=new Pi(g.transaction);
n&&n(A,function(H){return r.oldVersion<H&&r.newVersion>=H},B);
B.done.catch(function(H){e(H)})}catch(H){e(H)}});
g.addEventListener("success",function(){var r=g.result;k&&r.addEventListener("versionchange",function(){k(f())});
r.addEventListener("close",function(){ii("IDB_UNEXPECTEDLY_CLOSED",{dbName:ni(a),dbVersion:r.version});l&&l()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function $i(a,b,c){c=void 0===c?{}:c;return Zi(a,b,c)}
function aj(a,b){b=void 0===b?{}:b;return I(this,function d(){var e,f,g;return x(d,function(h){e=self.indexedDB.deleteDatabase(a);f=b;(g=f.blocked)&&e.addEventListener("blocked",function(){g()});
return w(h,Hi(e),0)})})}
;function bj(a,b){this.name=a;this.options=b;this.l=!0;this.j=!1}
bj.prototype.i=function(a,b,c){c=void 0===c?{}:c;return $i(a,b,c)};
bj.prototype.delete=function(a){a=void 0===a?{}:a;return aj(this.name,a)};
function cj(a,b){return new S("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
bj.prototype.open=function(){function a(){return I(c,function g(){var h,k,l=this,n,p,q,r,A;return x(g,function(B){switch(B.h){case 1:return k=null!==(h=Error().stack)&&void 0!==h?h:"",ra(B,2),w(B,l.i(l.name,l.options.version,e),4);case 4:n=B.i;a:{var H=l.options;for(var V=u(Object.keys(H.wa)),P=V.next();!P.done;P=V.next()){P=P.value;var J=H.wa[P],R=void 0===J.Kb?Number.MAX_VALUE:J.Kb;if(n.h.version>=J.Ca&&!(n.h.version>=R)&&!n.h.objectStoreNames.contains(P)){H=P;break a}}H=void 0}p=H;if(void 0===
p){B.o(5);break}if(l.j){B.o(6);break}l.j=!0;return w(B,l.delete(),7);case 7:return hi(new S("DB_DELETED_BY_MISSING_OBJECT_STORE",{dbName:l.name,Eb:p})),B.return(a());case 6:throw new ui(p);case 5:return B.return(n);case 2:q=sa(B);if(q instanceof DOMException?"VersionError"!==q.name:"DOMError"in self&&q instanceof DOMError?"VersionError"!==q.name:!(q instanceof Object&&"message"in q)||"An attempt was made to open a database using a lower version than the existing version."!==q.message){B.o(8);break}return w(B,
l.i(l.name,void 0,Object.assign(Object.assign({},e),{upgrade:void 0})),9);case 9:r=B.i;A=r.h.version;if(void 0!==l.options.version&&A>l.options.version+1)throw r.close(),l.l=!1,cj(l,A);return B.return(r);case 8:throw b(),q instanceof Error&&(q.stack=q.stack+"\n"+k.substring(k.indexOf("\n")+1)),q;}})})}
function b(){c.h===d&&(c.h=void 0)}
var c=this;if(!this.l)throw cj(this);if(this.h)return this.h;var d,e={blocking:function(f){f.close()},
closed:b,Tb:b,upgrade:this.options.upgrade};return this.h=d=a()};var dj=new bj("YtIdbMeta",{wa:{databases:{Ca:1}},upgrade:function(a,b){b(1)&&Mi(a,"databases",{keyPath:"actualName"})}});
function ej(a){return I(this,function c(){var d;return x(c,function(e){if(1==e.h)return w(e,dj.open(),2);d=e.i;return e.return(Li(d,["databases"],{K:!0,mode:"readwrite"},function(f){var g=f.objectStore("databases");return g.get(a.actualName).then(function(h){if(h?a.actualName!==h.actualName||a.publicName!==h.publicName||a.userIdentifier!==h.userIdentifier:1)return Ii(g.h.put(a,void 0)).then(function(){})})}))})})}
function fj(a){return I(this,function c(){var d;return x(c,function(e){if(1==e.h)return a?w(e,dj.open(),2):e.return();d=e.i;return e.return(d.delete("databases",a))})})}
function gj(a){return I(this,function c(){var d,e;return x(c,function(f){return 1==f.h?(d=[],w(f,dj.open(),2)):3!=f.h?(e=f.i,w(f,Li(e,["databases"],{K:!0,mode:"readonly"},function(g){d.length=0;return Ui(g.objectStore("databases"),{},function(h){a(h.getValue())&&d.push(h.getValue());return h.continue()})}),3)):f.return(d)})})}
function hj(){return gj(function(a){return"LogsDatabaseV2"===a.publicName&&void 0!==a.userIdentifier})}
;var ij,jj=new function(){}(new function(){});
function kj(){return I(this,function b(){var c,d,e;return x(b,function(f){switch(f.h){case 1:c=di();if(null===c||void 0===c?0:c.hasSucceededOnce)return f.return(new ei(!0));var g;if(g=Wg)g=/WebKit\/([0-9]+)/.exec(Ob),g=!!(g&&600<=parseInt(g[1],10));g&&(g=/WebKit\/([0-9]+)/.exec(Ob),g=!(g&&602<=parseInt(g[1],10)));if(g||mc)return f.return(new ei(!1));try{if(d=self,!(d.indexedDB&&d.IDBIndex&&d.IDBKeyRange&&d.IDBObjectStore))return f.return(new ei(!1))}catch(h){return f.return(new ei(!1))}if(!("IDBTransaction"in
self&&"objectStoreNames"in IDBTransaction.prototype))return f.return(new ei(!1));ra(f,2);e={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return w(f,ej(e),4);case 4:return w(f,fj("yt-idb-test-do-not-use"),5);case 5:return f.return(new ei(!0));case 2:return sa(f),f.return(new ei(!1))}})})}
function lj(){if(void 0!==ij)return ij;gi=!0;return ij=kj().then(function(a){gi=!1;return a.isSupported()})}
function mj(){return lj().then(function(a){return a?jj:void 0})}
;new function(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})};function nj(a){if(!ki())throw a=new S("AUTH_INVALID",{dbName:a}),hi(a),a;var b=li();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function oj(a,b,c,d){var e;return I(this,function g(){var h,k,l,n,p;return x(g,function(q){switch(q.h){case 1:return h=null!==(e=Error().stack)&&void 0!==e?e:"",w(q,mj(),2);case 2:k=q.i;if(!k)throw l=yi("openDbImpl",a,b),l.stack=l.stack+"\n"+h.substring(h.indexOf("\n")+1),hi(l),l;mi(a);n=c?{actualName:a,publicName:a,userIdentifier:void 0}:nj(a);ra(q,3);return w(q,ej(n),5);case 5:return w(q,$i(n.actualName,b,d),6);case 6:return q.return(q.i);case 3:return p=sa(q),ra(q,7),w(q,fj(n.actualName),9);case 9:q.h=
8;q.m=0;break;case 7:sa(q);case 8:throw p;}})})}
function pj(a,b,c){c=void 0===c?{}:c;return oj(a,b,!1,c)}
function qj(a,b,c){c=void 0===c?{}:c;return oj(a,b,!0,c)}
function rj(a,b){b=void 0===b?{}:b;return I(this,function d(){var e,f;return x(d,function(g){if(1==g.h)return w(g,mj(),2);if(3!=g.h){e=g.i;if(!e)return g.return();mi(a);f=nj(a);return w(g,aj(f.actualName,b),3)}return w(g,fj(f.actualName),0)})})}
function sj(a,b){var c=this;a=a.map(function(d){return I(c,function f(){return x(f,function(g){return 1==g.h?w(g,aj(d.actualName,b),2):w(g,fj(d.actualName),0)})})});
return Promise.all(a).then(function(){})}
function tj(){var a=void 0===a?{}:a;return I(this,function c(){var d,e;return x(c,function(f){if(1==f.h)return w(f,mj(),2);if(3!=f.h){d=f.i;if(!d)return f.return();mi("LogsDatabaseV2");return w(f,hj(),3)}e=f.i;return w(f,sj(e,a),0)})})}
function uj(a,b){b=void 0===b?{}:b;return I(this,function d(){var e;return x(d,function(f){if(1==f.h)return w(f,mj(),2);if(3!=f.h){e=f.i;if(!e)return f.return();mi(a);return w(f,aj(a,b),3)}return w(f,fj(a),0)})})}
;function vj(a){var b,c,d,e,f,g,h,k;this.h=!1;this.potentialEsfErrorCounter=this.i=0;this.handleError=function(){};
this.ia=function(){};
this.now=Date.now;this.lb=null!==(b=a.lb)&&void 0!==b?b:100;this.jb=null!==(c=a.jb)&&void 0!==c?c:1;this.hb=null!==(d=a.hb)&&void 0!==d?d:2592E6;this.fb=null!==(e=a.fb)&&void 0!==e?e:12E4;this.ib=null!==(f=a.ib)&&void 0!==f?f:5E3;this.databaseToken=null!==(g=a.databaseToken)&&void 0!==g?g:void 0;this.ta=!!a.ta;this.ra=null!==(h=a.ra)&&void 0!==h?h:.1;this.ya=null!==(k=a.ya)&&void 0!==k?k:10;a.handleError&&(this.handleError=a.handleError);a.ia&&(this.ia=a.ia);this.F=a.F;this.ab=a.ab;this.G=a.G;this.I=
a.I;this.R=a.R;this.Ma=a.Ma;this.La=a.La;this.databaseToken&&(!this.F||this.F("networkless_logging"))&&wj(this)}
function wj(a){I(a,function c(){var d=this;return x(c,function(e){if(!d.databaseToken)return e.return();xj(d);d.I.H()&&d.la();d.I.X(d.Ma,d.la.bind(d));d.I.X(d.La,d.Sa.bind(d));d.h=!0;return d.ta&&Math.random()<=d.ra?w(e,d.G.qb(d.databaseToken),0):e.o(0)})})}
m=vj.prototype;m.writeThenSend=function(a,b){var c=this;b=void 0===b?{}:b;if(this.databaseToken&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.G.set(d,this.databaseToken).then(function(e){d.id=e;c.I.H()&&yj(c,d)}).catch(function(e){yj(c,d);
zj(c,e)})}else this.R(a,b)};
m.sendThenWrite=function(a,b,c){var d=this;b=void 0===b?{}:b;if(this.databaseToken&&this.h){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.F&&this.F("nwl_skip_retry")&&(e.skipRetry=c);if(this.I.H()){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return I(d,function l(){var n=this,p;return x(l,function(q){if(1==q.h)return p=n,w(q,n.G.set(e,n.databaseToken).catch(function(r){zj(p,r)}),2);
f(g,h);q.h=0})})}}this.R(a,b,e.skipRetry)}else this.G.set(e,this.databaseToken).catch(function(g){d.R(a,b,e.skipRetry);
zj(d,g)})}else this.R(a,b,this.F&&this.F("nwl_skip_retry")&&c)};
m.sendAndWrite=function(a,b){var c=this;b=void 0===b?{}:b;if(this.databaseToken&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){void 0!==d.id?c.G.ha(d.id,c.databaseToken):e=!0;c.I.Z&&c.F&&c.F("vss_network_hint")&&c.I.Z(!0);f(g,h)};
this.R(d.url,d.options);this.G.set(d,this.databaseToken).then(function(g){d.id=g;e&&c.G.ha(d.id,c.databaseToken)}).catch(function(g){zj(c,g)})}else this.R(a,b)};
m.la=function(){var a=this;if(!this.databaseToken)throw yi("throttleSend");this.i||(this.i=ig(function(){return I(a,function c(){var d=this,e;return x(c,function(f){if(1==f.h)return w(f,d.G.Ya("NEW",d.databaseToken),2);if(3!=f.h)return e=f.i,e?w(f,yj(d,e),3):(d.Sa(),f.return());d.i&&(d.i=0,d.la());f.h=0})})},this.lb))};
m.Sa=function(){lg(this.i);this.i=0};
function yj(a,b){return I(a,function d(){var e=this,f,g;return x(d,function(h){switch(h.h){case 1:if(!e.databaseToken)throw f=yi("immediateSend"),f;if(void 0===b.id){h.o(2);break}return w(h,e.G.Db(b.id,e.databaseToken),3);case 3:(g=h.i)?b=g:e.ia(Error("The request cannot be found in the database."));case 2:if(Aj(e,b,e.hb)){h.o(4);break}e.ia(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===b.id){h.o(5);break}return w(h,e.G.ha(b.id,e.databaseToken),5);case 5:return h.return();
case 4:b.skipRetry||(b=Bj(e,b));if(!b){h.o(0);break}if(!b.skipRetry||void 0===b.id){h.o(8);break}return w(h,e.G.ha(b.id,e.databaseToken),8);case 8:e.R(b.url,b.options,!!b.skipRetry),h.h=0}})})}
function Bj(a,b){if(!a.databaseToken)throw yi("updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){return I(a,function h(){var k=this,l,n;return x(h,function(p){switch(p.h){case 1:l=k;n=Cj(f);if(!(k.F&&k.F("nwl_consider_error_code")&&n||k.F&&!k.F("nwl_consider_error_code")&&k.potentialEsfErrorCounter<=k.ya)){p.o(2);break}if(!k.I.N){p.o(3);break}return w(p,k.I.N(),3);case 3:if(k.I.H()){p.o(2);break}c(e,f);if(!k.F||!k.F("nwl_consider_error_code")||void 0===(null===b||void 0===b?void 0:b.id)){p.o(6);break}return w(p,k.G.Na(b.id,k.databaseToken,!1),6);case 6:return p.return();
case 2:if(k.F&&k.F("nwl_consider_error_code")&&!n&&k.potentialEsfErrorCounter>k.ya)return p.return();k.potentialEsfErrorCounter++;if(void 0===(null===b||void 0===b?void 0:b.id)){p.o(8);break}return b.sendCount<k.jb?w(p,k.G.Na(b.id,k.databaseToken),12):w(p,k.G.ha(b.id,k.databaseToken),8);case 12:ig(function(){l.I.H()&&l.la()},k.ib);
case 8:c(e,f),p.h=0}})})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){return I(a,function h(){var k=this;return x(h,function(l){if(1==l.h)return void 0===(null===b||void 0===b?void 0:b.id)?l.o(2):w(l,k.G.ha(b.id,k.databaseToken),2);k.I.Z&&k.F&&k.F("vss_network_hint")&&k.I.Z(!0);d(e,f);l.h=0})})};
return b}
function Aj(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function xj(a){if(!a.databaseToken)throw yi("retryQueuedRequests");a.G.Ya("QUEUED",a.databaseToken).then(function(b){b&&!Aj(a,b,a.fb)?ig(function(){return I(a,function d(){var e=this;return x(d,function(f){if(1==f.h)return void 0===b.id?f.o(2):w(f,e.G.Na(b.id,e.databaseToken),2);xj(e);f.h=0})})}):a.I.H()&&a.la()})}
function zj(a,b){a.mb&&!a.I.H()?a.mb(b):a.handleError(b)}
function Cj(a){var b;return(a=null===(b=null===a||void 0===a?void 0:a.error)||void 0===b?void 0:b.code)&&400<=a&&599>=a?!1:!0}
;function Dj(a,b){this.version=a;this.args=b}
;function Ej(a,b){this.topic=a;this.h=b}
Ej.prototype.toString=function(){return this.topic};var Fj=C("ytPubsub2Pubsub2Instance")||new M;M.prototype.subscribe=M.prototype.subscribe;M.prototype.unsubscribeByKey=M.prototype.ja;M.prototype.publish=M.prototype.ca;M.prototype.clear=M.prototype.clear;z("ytPubsub2Pubsub2Instance",Fj,void 0);var Gj=C("ytPubsub2Pubsub2SubscribedKeys")||{};z("ytPubsub2Pubsub2SubscribedKeys",Gj,void 0);var Hj=C("ytPubsub2Pubsub2TopicToKeys")||{};z("ytPubsub2Pubsub2TopicToKeys",Hj,void 0);var Ij=C("ytPubsub2Pubsub2IsAsync")||{};z("ytPubsub2Pubsub2IsAsync",Ij,void 0);
z("ytPubsub2Pubsub2SkipSubKey",null,void 0);function Jj(a,b){var c=Kj();c&&c.publish.call(c,a.toString(),a,b)}
function Lj(a){var b=Mj,c=Kj();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=C("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(Gj[d])try{if(f&&b instanceof Ej&&b!=e)try{var h=b.h,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.ba){var l=new h;h.ba=l.version}var n=h.ba}catch(p){}if(!n||k.version!=n)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{f=Reflect.construct(h,
bb(k.args))}catch(p){throw p.message="yt.pubsub2.Data.deserialize(): "+p.message,p;}}catch(p){throw p.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+p.message,p;}a.call(window,f)}catch(p){Mf(p)}},Ij[b.toString()]?C("yt.scheduler.instance")?hg(g,1,void 0):cg(g,0):g())});
Gj[d]=!0;Hj[b.toString()]||(Hj[b.toString()]=[]);Hj[b.toString()].push(d);return d}
function Nj(){var a=Oj,b=Lj(function(c){a.apply(void 0,arguments);Pj(b)});
return b}
function Pj(a){var b=Kj();b&&("number"===typeof a&&(a=[a]),E(a,function(c){b.unsubscribeByKey(c);delete Gj[c]}))}
function Kj(){return C("ytPubsub2Pubsub2Instance")}
;function Qj(a,b){bj.call(this,a,b);this.options=b;mi(a)}
v(Qj,bj);function Rj(a,b){var c;return function(){c||(c=new Qj(a,b));return c}}
Qj.prototype.i=function(a,b,c){c=void 0===c?{}:c;return(this.options.Oa?qj:pj)(a,b,Object.assign({},c))};
Qj.prototype.delete=function(a){a=void 0===a?{}:a;return(this.options.Oa?uj:rj)(this.name,a)};
function Sj(a,b){return Rj(a,b)}
;var Tj;
function Uj(){if(Tj)return Tj();var a={};Tj=Sj("LogsDatabaseV2",{wa:(a.LogsRequestsStore={Ca:2},a),Oa:!1,upgrade:function(b,c,d){c(2)&&Mi(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.h.indexNames.contains("newRequest")&&d.h.deleteIndex("newRequest"),d.h.createIndex("newRequestV2",["status","interface","timestamp"],{unique:!1}));c(7)&&b.h.objectStoreNames.contains("sapisid")&&b.h.deleteObjectStore("sapisid");c(9)&&b.h.objectStoreNames.contains("SWHealthLog")&&b.h.deleteObjectStore("SWHealthLog")},
version:9});return Tj()}
;function Vj(a){return I(this,function c(){var d,e,f,g;return x(c,function(h){if(1==h.h)return d={startTime:Q(),transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},w(h,Uj().open(),2);if(3!=h.h)return e=h.i,f=Object.assign(Object.assign({},a),{options:JSON.parse(JSON.stringify(a.options)),interface:F("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),w(h,Oi(e,f),3);g=h.i;d.Ub=Q();Wj(d);return h.return(g)})})}
function Xj(a){return I(this,function c(){var d,e,f,g,h,k,l;return x(c,function(n){if(1==n.h)return d={startTime:Q(),transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},w(n,Uj().open(),2);if(3!=n.h)return e=n.i,f=F("INNERTUBE_CONTEXT_CLIENT_NAME",0),g=[a,f,0],h=[a,f,Q()],k=IDBKeyRange.bound(g,h),l=void 0,w(n,Li(e,["LogsRequestsStore"],{mode:"readwrite",K:!0},function(p){return Xi(p.objectStore("LogsRequestsStore").index("newRequestV2"),{query:k,direction:"prev"},function(q){q.getValue()&&(l=q.getValue(),
"NEW"===a&&(l.status="QUEUED",q.update(l)))})}),3);
d.Ub=Q();Wj(d);return n.return(l)})})}
function Yj(a){return I(this,function c(){var d;return x(c,function(e){if(1==e.h)return w(e,Uj().open(),2);d=e.i;return e.return(Li(d,["LogsRequestsStore"],{mode:"readwrite",K:!0},function(f){var g=f.objectStore("LogsRequestsStore");return g.get(a).then(function(h){if(h)return h.status="QUEUED",Ii(g.h.put(h,void 0)).then(function(){return h})})}))})})}
function Zj(a,b,c){c=void 0===c?!0:c;return I(this,function e(){var f;return x(e,function(g){if(1==g.h)return w(g,Uj().open(),2);f=g.i;return g.return(Li(f,["LogsRequestsStore"],{mode:"readwrite",K:!0},function(h){var k=h.objectStore("LogsRequestsStore");return k.get(a).then(function(l){return l?(l.status="NEW",c&&(l.sendCount+=1),Ii(k.h.put(l,void 0)).then(function(){return l})):T.resolve(void 0)})}))})})}
function ak(a){return I(this,function c(){var d;return x(c,function(e){if(1==e.h)return w(e,Uj().open(),2);d=e.i;return e.return(d.delete("LogsRequestsStore",a))})})}
function bk(){return I(this,function b(){var c,d;return x(b,function(e){if(1==e.h)return w(e,Uj().open(),2);c=e.i;d=Q()-2592E6;return w(e,Li(c,["LogsRequestsStore"],{mode:"readwrite",K:!0},function(f){return Ui(f.objectStore("LogsRequestsStore"),{},function(g){if(g.getValue().timestamp<=d)return g.delete().then(function(){return g.continue()})})}),0)})})}
function ck(){return I(this,function b(){return x(b,function(c){return w(c,tj(),0)})})}
function Wj(a){O("nwl_csi_killswitch")||.01>=Math.random()&&Jj("nwl_transaction_latency_payload",a)}
;var dk={},ek=Sj("ServiceWorkerLogsDatabase",{wa:(dk.SWHealthLog={Ca:1},dk),Oa:!0,upgrade:function(a,b){b(1)&&Mi(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}).h.createIndex("swHealthNewRequest",["interface","timestamp"],{unique:!1})},
version:1});function fk(){return I(this,function b(){var c,d;return x(b,function(e){if(1==e.h)return O("web_clean_sw_logs_store")?w(e,ek().open(),3):e.o(0);c=e.i;d=Q()-2592E6;return w(e,Li(c,["SWHealthLog"],{mode:"readwrite",K:!0},function(f){return Ui(f.objectStore("SWHealthLog"),{},function(g){if(g.getValue().timestamp<=d)return g.delete().then(function(){return g.continue()})})}),0)})})}
function gk(){return I(this,function b(){var c;return x(b,function(d){if(1==d.h)return w(d,ek().open(),2);c=d.i;return w(d,c.clear("SWHealthLog"),0)})})}
;var hk;function ik(){hk||(hk=new Xh("yt.offline"));return hk}
function jk(a){if(O("offline_error_handling")){var b=ik().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);ik().set("errors",b,2592E3,!0)}}
;var kk=Rf("network_polling_interval",3E4);function U(){Je.call(this);this.C=0;this.J=this.l=!1;this.j=this.Ga();lk(this);mk(this)}
v(U,Je);function nk(){if(!U.h){var a=C("yt.networkStatusManager.instance")||new U;z("yt.networkStatusManager.instance",a,void 0);U.h=a}return U.h}
m=U.prototype;m.H=function(){return this.j};
m.Z=function(a,b){a!==this.j&&((void 0===b?0:b)?this.N():this.j=a)};
m.Fb=function(a){this.l=!0;if(void 0===a?0:a)this.C||ok(this)};
m.Ga=function(){var a=window.navigator.onLine;return void 0===a?!0:a};
m.sb=function(){this.J=!0};
m.X=function(a,b){return Je.prototype.X.call(this,a,b)};
function mk(a){window.addEventListener("online",function(){return I(a,function c(){var d=this;return x(c,function(e){if(1==e.h)return w(e,d.N(),2);if(d.J&&O("offline_error_handling")){var f=ik().get("errors",!0);if(f){for(var g in f)if(f[g]){var h=new ji(g,"sent via offline_errors");h.name=f[g].name;h.stack=f[g].stack;h.level=f[g].level;Mf(h)}ik().set("errors",{},2592E3,!0)}}e.h=0})})})}
function lk(a){window.addEventListener("offline",function(){return I(a,function c(){var d=this;return x(c,function(e){return w(e,d.N(),0)})})})}
function ok(a){a.C=gg(function(){return I(a,function c(){var d=this;return x(c,function(e){if(1==e.h)return d.j?d.Ga()||!d.l?e.o(3):w(e,d.N(),3):w(e,d.N(),3);ok(d);e.h=0})})},kk)}
m.N=function(a){var b=this;return this.m?this.m:this.m=new Promise(function(c){return I(b,function e(){var f,g,h,k=this;return x(e,function(l){switch(l.h){case 1:return f=window.AbortController?new window.AbortController:void 0,g=null===f||void 0===f?void 0:f.signal,h=!1,ra(l,2,3),f&&(k.B=ig(function(){f.abort()},a||2E4)),w(l,fetch("/generate_204",{method:"HEAD",
signal:g}),5);case 5:h=!0;case 3:ta(l);k.m=void 0;k.B&&lg(k.B);h!==k.j&&(k.j=h,k.j&&k.l?Ke(k,"ytnetworkstatus-online"):k.l&&Ke(k,"ytnetworkstatus-offline"));c(h);ua(l);break;case 2:sa(l),h=!1,l.o(3)}})})})};
U.prototype.sendNetworkCheckRequest=U.prototype.N;U.prototype.listen=U.prototype.X;U.prototype.enableErrorFlushing=U.prototype.sb;U.prototype.getWindowStatus=U.prototype.Ga;U.prototype.monitorNetworkStatusChange=U.prototype.Fb;U.prototype.networkStatusHint=U.prototype.Z;U.prototype.isNetworkAvailable=U.prototype.H;U.getInstance=nk;function pk(a){a=void 0===a?{}:a;Je.call(this);var b=this;this.l=this.B=0;this.j=nk();var c=C("yt.networkStatusManager.instance.monitorNetworkStatusChange").bind(this.j);c&&c(a.Wa);a.bb&&(c=C("yt.networkStatusManager.instance.enableErrorFlushing").bind(this.j))&&c();if(c=C("yt.networkStatusManager.instance.listen").bind(this.j))a.za?(this.za=a.za,c("ytnetworkstatus-online",function(){qk(b,"publicytnetworkstatus-online")}),c("ytnetworkstatus-offline",function(){qk(b,"publicytnetworkstatus-offline")})):
(c("ytnetworkstatus-online",function(){Ke(b,"publicytnetworkstatus-online")}),c("ytnetworkstatus-offline",function(){Ke(b,"publicytnetworkstatus-offline")}))}
v(pk,Je);pk.prototype.H=function(){var a=C("yt.networkStatusManager.instance.isNetworkAvailable").bind(this.j);return a?a():!0};
pk.prototype.Z=function(a,b){b=void 0===b?!1:b;var c=C("yt.networkStatusManager.instance.networkStatusHint").bind(this.j);c&&c(a,b)};
pk.prototype.N=function(a){return I(this,function c(){var d=this,e;return x(c,function(f){return(e=C("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(d.j))?f.return(e(a)):f.return(!0)})})};
function qk(a,b){a.za?a.l?(lg(a.B),a.B=ig(function(){a.m!==b&&(Ke(a,b),a.m=b,a.l=Q())},a.za-(Q()-a.l))):(Ke(a,b),a.m=b,a.l=Q()):Ke(a,b)}
;var rk=!1,sk,tk=0,uk=0,vk,wk=y.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:rk,databaseToken:sk,potentialEsfErrorCounter:uk,isIdbSupported:!!sk};z("ytNetworklessLoggingInitializationOptions",wk,void 0);
function xk(){I(this,function b(){return x(b,function(c){switch(c.h){case 1:return w(c,mj(),2);case 2:sk=c.i;if(!sk||!ki()&&!O("nwl_init_require_datasync_id_killswitch")){c.o(0);break}rk=!0;wk.isNwlInitialized=rk;wk.databaseToken=sk;wk.isIdbSupported=!!sk;return w(c,uj("LogsDatabaseV2"),4);case 4:if(!(.1>=Math.random())){c.o(5);break}return w(c,bk(sk),6);case 6:return w(c,fk(),5);case 5:yk();zk().H()&&Ak();zk().X("publicytnetworkstatus-online",Ak);zk().X("publicytnetworkstatus-offline",Bk);if(!O("networkless_immediately_drop_sw_health_store")){c.o(8);
break}return w(c,Ck(),8);case 8:if(O("networkless_immediately_drop_all_requests"))return w(c,ck(),0);c.o(0)}})})}
function Dk(a,b){function c(d){var e=zk().H();if(!Ek()||!d||e&&O("vss_networkless_bypass_write"))Fk(a,b);else{var f={url:a,options:b,timestamp:Q(),status:"NEW",sendCount:0};Vj(f,d).then(function(g){f.id=g;zk().H()&&Gk(f)}).catch(function(g){Gk(f);
zk().H()?Mf(g):jk(g)})}}
b=void 0===b?{}:b;O("skip_is_supported_killswitch")?mj().then(function(d){c(d)}):c(Hk())}
function Ik(a,b){function c(d){if(Ek()&&d){var e={url:a,options:b,timestamp:Q(),status:"NEW",sendCount:0},f=!1,g=b.onSuccess?b.onSuccess:function(){};
e.options.onSuccess=function(h,k){void 0!==e.id?ak(e.id,d):f=!0;O("vss_network_hint")&&zk().Z(!0);g(h,k)};
Fk(e.url,e.options);Vj(e,d).then(function(h){e.id=h;f&&ak(e.id,d)}).catch(function(h){zk().H()?Mf(h):jk(h)})}else Fk(a,b)}
b=void 0===b?{}:b;O("skip_is_supported_killswitch")?mj().then(function(d){c(d)}):c(Hk())}
function Ak(){var a=this,b=Hk();if(!b)throw yi("throttleSend");tk||(tk=ig(function(){return I(a,function d(){var e;return x(d,function(f){if(1==f.h)return w(f,Xj("NEW",b),2);if(3!=f.h)return e=f.i,e?w(f,Gk(e),3):(Bk(),f.return());tk&&(tk=0,Ak());f.h=0})})},100))}
function Bk(){lg(tk);tk=0}
function Gk(a){return I(this,function c(){var d,e,f;return x(c,function(g){switch(g.h){case 1:d=Hk();if(!d)throw e=yi("immediateSend"),e;if(void 0===a.id){g.o(2);break}return w(g,Yj(a.id,d),3);case 3:(f=g.i)?a=f:Nf(Error("The request cannot be found in the database."));case 2:if(Jk(a,2592E6)){g.o(4);break}Nf(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===a.id){g.o(5);break}return w(g,ak(a.id,d),5);case 5:return g.return();case 4:a.skipRetry||(a=Kk(a));var h=a,k,l;
if(null===(l=null===(k=null===h||void 0===h?void 0:h.options)||void 0===k?void 0:k.postParams)||void 0===l?0:l.requestTimeMs)h.options.postParams.requestTimeMs=Math.round(Q());a=h;if(!a){g.o(0);break}if(!a.skipRetry||void 0===a.id){g.o(8);break}return w(g,ak(a.id,d),8);case 8:Fk(a.url,a.options,!!a.skipRetry),g.h=0}})})}
function Kk(a){var b=this,c=Hk();if(!c)throw yi("updateRequestHandlers");var d=a.options.onError?a.options.onError:function(){};
a.options.onError=function(f,g){return I(b,function k(){var l;return x(k,function(n){switch(n.h){case 1:l=Cj(g);if(!(O("nwl_consider_error_code")&&l||!O("nwl_consider_error_code")&&Lk()<=Rf("potential_esf_error_limit",10))){n.o(2);break}return w(n,zk().N(),3);case 3:if(zk().H()){n.o(2);break}d(f,g);if(!O("nwl_consider_error_code")||void 0===(null===a||void 0===a?void 0:a.id)){n.o(5);break}return w(n,Zj(a.id,c,!1),5);case 5:return n.return();case 2:if(O("nwl_consider_error_code")&&!l&&Lk()>Rf("potential_esf_error_limit",
10))return n.return();C("ytNetworklessLoggingInitializationOptions")&&wk.potentialEsfErrorCounter++;uk++;if(void 0===(null===a||void 0===a?void 0:a.id)){n.o(7);break}return 1>a.sendCount?w(n,Zj(a.id,c),11):w(n,ak(a.id,c),7);case 11:ig(function(){zk().H()&&Ak()},5E3);
case 7:d(f,g),n.h=0}})})};
var e=a.options.onSuccess?a.options.onSuccess:function(){};
a.options.onSuccess=function(f,g){return I(b,function k(){return x(k,function(l){if(1==l.h)return void 0===(null===a||void 0===a?void 0:a.id)?l.o(2):w(l,ak(a.id,c),2);O("vss_network_hint")&&zk().Z(!0);e(f,g);l.h=0})})};
return a}
function Jk(a,b){a=a.timestamp;return Q()-a>=b?!1:!0}
function yk(){var a=this,b=Hk();if(!b)throw yi("retryQueuedRequests");Xj("QUEUED",b).then(function(c){c&&!Jk(c,12E4)?ig(function(){return I(a,function e(){return x(e,function(f){if(1==f.h)return void 0===c.id?f.o(2):w(f,Zj(c.id,b),2);yk();f.h=0})})}):zk().H()&&Ak()})}
function Ck(){return I(this,function b(){var c,d;return x(b,function(e){c=Hk();if(!c)throw d=yi("clearSWHealthLogsDb"),d;return e.return(gk().catch(function(f){Mf(f)}))})})}
function zk(){vk||(vk=new pk({bb:!0,Wa:!0}));return vk}
function Fk(a,b,c){if(O("networkless_with_beacon")){var d=["method","postBody"];if(Object.keys(b).length>d.length)c=!0;else{c=0;d=u(d);for(var e=d.next();!e.done;e=d.next())b.hasOwnProperty(e.value)&&c++;c=Object.keys(b).length!==c}c?Og(a,b):ch(a,void 0,b.postBody)}else c&&0===Object.keys(b).length?$g(a):Og(a,b)}
function Ek(){return C("ytNetworklessLoggingInitializationOptions")?wk.isNwlInitialized:rk}
function Hk(){return C("ytNetworklessLoggingInitializationOptions")?wk.databaseToken:sk}
function Lk(){return C("ytNetworklessLoggingInitializationOptions")?wk.potentialEsfErrorCounter:uk}
;function Mk(){vj.call(this,{G:{qb:bk,ha:ak,Ya:Xj,Db:Yj,Na:Zj,set:Vj},I:new pk({bb:!0,Wa:!0}),handleError:Mf,ia:Nf,R:Nk,now:Q,mb:jk,ab:kg(),Ma:"publicytnetworkstatus-online",La:"publicytnetworkstatus-offline",ta:!0,ra:.1,ya:Rf("potential_esf_error_limit",10),F:O});this.ta&&Math.random()<=this.ra&&this.databaseToken&&fk();O("networkless_immediately_drop_sw_health_store")&&Ok(this);O("networkless_immediately_drop_all_requests")&&ck();uj("LogsDatabaseV2")}
v(Mk,vj);function Pk(){var a=C("yt.networklessRequestController.instance");a||(a=new Mk,z("yt.networklessRequestController.instance",a,void 0),O("networkless_logging")&&mj().then(function(b){a.databaseToken=b;wj(a)}));
return a}
Mk.prototype.writeThenSend=function(a,b){b||(b={});ki()||(this.h=!1);vj.prototype.writeThenSend.call(this,a,b)};
Mk.prototype.sendThenWrite=function(a,b,c){b||(b={});ki()||(this.h=!1);vj.prototype.sendThenWrite.call(this,a,b,c)};
Mk.prototype.sendAndWrite=function(a,b){b||(b={});ki()||(this.h=!1);vj.prototype.sendAndWrite.call(this,a,b)};
function Ok(a){I(a,function c(){var d=this,e,f;return x(c,function(g){e=d;if(!d.databaseToken)throw f=yi("clearSWHealthLogsDb"),f;return g.return(gk().catch(function(h){e.handleError(h)}))})})}
function Nk(a,b,c){var d;if(null===(d=b.postParams)||void 0===d?0:d.requestTimeMs)b.postParams.requestTimeMs=Math.round(Q());if(O("networkless_with_beacon")){c=b;var e=["method","postBody"];if(Object.keys(c).length>e.length)c=!0;else{d=0;e=u(e);for(var f=e.next();!f.done;f=e.next())c.hasOwnProperty(f.value)&&d++;c=Object.keys(c).length!==d}c?Og(a,b):ch(a,void 0,b.postBody)}else c&&0===Object.keys(b).length?$g(a):Og(a,b)}
;function Qk(a){var b=this;this.config_=null;a?this.config_=a:Uh()&&(this.config_=Eh());gg(function(){bi(b)},5E3)}
Qk.prototype.isReady=function(){!this.config_&&Uh()&&(this.config_=Eh());return!!this.config_};
function Hh(a,b,c,d){function e(q){q=void 0===q?!1:q;var r;if(d.retry&&"www.youtube-nocookie.com"!=h&&(q||O("skip_ls_gel_retry")||(r=$h(b,c,l,k)),r)){var A=g.onSuccess,B=g.onFetchSuccess;g.onSuccess=function(H,V){ai(r);A(H,V)};
c.onFetchSuccess=function(H,V){ai(r);B(H,V)}}try{q&&d.retry&&!d.eb.bypassNetworkless?(g.method="POST",d.eb.writeThenSend?O("use_new_nwl")?Pk().writeThenSend(p,g):Dk(p,g):O("use_new_nwl")?Pk().sendAndWrite(p,g):Ik(p,g)):(g.method="POST",g.postParams||(g.postParams={}),Og(p,g))}catch(H){if("InvalidAccessError"==H.name)r&&(ai(r),r=0),Nf(Error("An extension is blocking network request."));
else throw H;}r&&gg(function(){bi(a)},5E3)}
!F("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&Nf(new ji("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new ji("innertube xhrclient not ready",b,c,d);Mf(f);throw f;}var g={headers:{"Content-Type":"application/json"},method:"POST",postParams:c,postBodyFormat:"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(q,r){if(d.onSuccess)d.onSuccess(r)},
onFetchSuccess:function(q){if(d.onSuccess)d.onSuccess(q)},
onError:function(q,r){if(d.onError)d.onError(r)},
onFetchError:function(q){if(d.onError)d.onError(q)},
timeout:d.timeout,withCredentials:!0},h="";(f=a.config_.Ab)&&(h=f);var k=a.config_.Cb||!1,l=Vh(k,h,d);Object.assign(g.headers,l);g.headers.Authorization&&!h&&(g.headers["x-origin"]=window.location.origin);f="/youtubei/"+a.config_.innertubeApiVersion+"/"+b;var n={alt:"json"};a.config_.Bb&&g.headers.Authorization||(n.key=a.config_.innertubeApiKey);var p=Cg(""+h+f,n||{},!0);O("use_new_nwl")||Ek()?lj().then(function(q){e(q)}):e(!1)}
;function Rk(a,b,c){c=void 0===c?{}:c;var d=Qk;F("ytLoggingEventsDefaultDisabled",!1)&&Qk==Qk&&(d=null);Jh(a,b,d,c)}
;var Sk=[{Ka:function(a){return"Cannot read property '"+a.key+"'"},
xa:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Ka:function(a){return"Cannot call '"+a.key+"'"},
xa:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Ka:function(a){return a.key+" is not defined"},
xa:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var Uk={Y:[],U:[{Ra:Tk,weight:500}]};function Tk(a){if("JavaException"===a.name)return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function Vk(){this.U=[];this.Y=[]}
var Wk;function Xk(){if(!Wk){var a=Wk=new Vk;a.Y.length=0;a.U.length=0;Uk.Y&&a.Y.push.apply(a.Y,Uk.Y);Uk.U&&a.U.push.apply(a.U,Uk.U)}return Wk}
;var Yk=new M;function Zk(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=$k(b);if(Infinity===e)break;var f=e>>3;switch(e&7){case 0:e=$k(b);if(2===f)return e;break;case 1:if(2===f)return;d+=8;break;case 2:e=$k(b);if(2===f)return a.substr(d,e);d+=e;break;case 5:if(2===f)return;d+=4;break;default:return}}while(d<c)}
function $k(a){var b=a(),c=b&127;if(128>b)return c;b=a();c|=(b&127)<<7;if(128>b)return c;b=a();c|=(b&127)<<14;if(128>b)return c;b=a();return 128>b?c|(b&127)<<21:Infinity}
;function al(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=bl(d,a[d],b,c),500<e));d++);d=e}else if("object"===typeof a)for(e in a){if(a[e]){var f=a[e];var g=b;var h=c;g="string"!==typeof f||"clickTrackingParams"!==e&&"trackingParams"!==e?0:(f=Zk(atob(f.replace(/-/g,"+").replace(/_/g,"/"))))?bl(e+".ve",f,g,h):0;d+=g;d+=bl(e,a[e],b,c);if(500<d)break}}else c[b]=cl(a),d+=c[b].length;else c[b]=cl(a),d+=c[b].length;return d}
function bl(a,b,c,d){c+="."+a;a=cl(b);d[c]=a;return c.length+a.length}
function cl(a){return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}
;var dl=new Set,el=0,fl=0,gl=0,hl=[],il=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function jl(a){kl(a,"WARNING")}
function kl(a,b,c,d,e,f){f=void 0===f?{}:f;f.name=c||F("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||F("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0);c=f||{};b=void 0===b?"ERROR":b;b=void 0===b?"ERROR":b;if(a&&(a.hasOwnProperty("level")&&a.level&&(b=a.level),O("console_log_js_exceptions")&&(d=[],d.push("Name: "+a.name),d.push("Message: "+a.message),a.hasOwnProperty("params")&&d.push("Error Params: "+JSON.stringify(a.params)),a.hasOwnProperty("args")&&d.push("Error args: "+JSON.stringify(a.args)),d.push("File name: "+
a.fileName),d.push("Stacktrace: "+a.stack),window.console.log(d.join("\n"),a)),!(5<=el))){var g=Od(a);d=g.message||"Unknown Error";e=g.name||"UnknownError";var h=g.stack||a.i||"Not available";h.startsWith(e+": "+d)&&(f=h.split("\n"),f.shift(),h=f.join("\n"));f=g.lineNumber||"Not available";g=g.fileName||"Not available";var k=0;if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var l=0;l<a.args.length&&!(k=al(a.args[l],"params."+l,c,k),500<=k);l++);else if(a.hasOwnProperty("params")&&a.params){var n=
a.params;if("object"===typeof a.params)for(l in n){if(n[l]){var p="params."+l,q=cl(n[l]);c[p]=q;k+=p.length+q.length;if(500<k)break}}else c.params=cl(n)}if(hl.length)for(l=0;l<hl.length&&!(k=al(hl[l],"params.context."+l,c,k),500<=k);l++);navigator.vendor&&!c.hasOwnProperty("vendor")&&(c["device.vendor"]=navigator.vendor);l={message:d,name:e,lineNumber:f,fileName:g,stack:h,params:c,sampleWeight:1};c=Number(a.columnNumber);isNaN(c)||(l.lineNumber=l.lineNumber+":"+c);if("IGNORED"===a.level)a=0;else a:{a=
Xk();c=u(a.Y);for(d=c.next();!d.done;d=c.next())if(d=d.value,l.message&&l.message.match(d.Gm)){a=d.weight;break a}a=u(a.U);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.Ra(l)){a=c.weight;break a}a=1}l.sampleWeight=a;a=u(Sk);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.xa[l.name])for(e=u(c.xa[l.name]),d=e.next();!d.done;d=e.next())if(f=d.value,d=l.message.match(f.regexp)){l.params["params.error.original"]=d[0];e=f.groups;f={};for(g=0;g<e.length;g++)f[e[g]]=d[g+1],l.params["params.error."+e[g]]=
d[g+1];l.message=c.Ka(f);break}l.params||(l.params={});a=Xk();l.params["params.errorServiceSignature"]="msg="+a.Y.length+"&cb="+a.U.length;l.params["params.serviceWorker"]="false";y.document&&y.document.querySelectorAll&&(l.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));sb("sample").constructor!==qb&&(l.params["params.fconst"]="true");window.yterr&&"function"===typeof window.yterr&&window.yterr(l);if(0!==l.sampleWeight&&!dl.has(l.message)){"ERROR"===b?(Yk.ca("handleError",
l),O("record_app_crashed_web")&&0===gl&&1===l.sampleWeight&&(gl++,Rk("appCrashed",{appCrashType:"APP_CRASH_TYPE_BREAKPAD"})),fl++):"WARNING"===b&&Yk.ca("handleWarning",l);if(O("kevlar_gel_error_routing")){a=b;b:{c=u(il);for(d=c.next();!d.done;d=c.next())if(Xg(d.value.toLowerCase())){c=!0;break b}c=!1}if(c)c=void 0;else{d={stackTrace:l.stack};l.fileName&&(d.filename=l.fileName);c=l.lineNumber&&l.lineNumber.split?l.lineNumber.split(":"):[];0!==c.length&&(1!==c.length||isNaN(Number(c[0]))?2!==c.length||
isNaN(Number(c[0]))||isNaN(Number(c[1]))||(d.lineNumber=Number(c[0]),d.columnNumber=Number(c[1])):d.lineNumber=Number(c[0]));c={level:"ERROR_LEVEL_UNKNOWN",message:l.message,errorClassName:l.name,sampleWeight:l.sampleWeight};"ERROR"===a?c.level="ERROR_LEVEL_ERROR":"WARNING"===a&&(c.level="ERROR_LEVEL_WARNNING");d={isObfuscated:!0,browserStackInfo:d};e={pageUrl:window.location.href,kvPairs:[]};F("FEXP_EXPERIMENTS")&&(e.experimentIds=F("FEXP_EXPERIMENTS"));if(f=l.params)for(g=u(Object.keys(f)),h=g.next();!h.done;h=
g.next())h=h.value,e.kvPairs.push({key:"client."+h,value:String(f[h])});f=F("SERVER_NAME",void 0);g=F("SERVER_VERSION",void 0);f&&g&&(e.kvPairs.push({key:"server.name",value:f}),e.kvPairs.push({key:"server.version",value:g}));c={errorMetadata:e,stackTrace:d,logMessage:c}}c&&(Rk("clientError",c),("ERROR"===a||O("errors_flush_gel_always_killswitch"))&&zh())}if(!O("suppress_error_204_logging")){a=l.params||{};b={urlParams:{a:"logerror",t:"jserror",type:l.name,msg:l.message.substr(0,250),line:l.lineNumber,
level:b,"client.name":a.name},postParams:{url:F("PAGE_NAME",window.location.href),file:l.fileName},method:"POST"};a.version&&(b["client.version"]=a.version);if(b.postParams){l.stack&&(b.postParams.stack=l.stack);c=u(Object.keys(a));for(d=c.next();!d.done;d=c.next())d=d.value,b.postParams["client."+d]=a[d];if(a=F("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS",void 0))for(c=u(Object.keys(a)),d=c.next();!d.done;d=c.next())d=d.value,b.postParams[d]=a[d];a=F("SERVER_NAME",void 0);c=F("SERVER_VERSION",void 0);
a&&c&&(b.postParams["server.name"]=a,b.postParams["server.version"]=c)}Og(F("ECATCHER_REPORT_HOST","")+"/error_204",b)}try{dl.add(l.message)}catch(r){}el++}}}
function ll(a,b){for(var c=[],d=1;d<arguments.length;++d)c[d-1]=arguments[d];a.args||(a.args=[]);a.args.push.apply(a.args,fa(c))}
;var ml={Ic:3611,Vb:27686,Wb:85013,Xb:23462,Zb:42016,ac:62407,cc:26926,Yb:43781,dc:51236,ec:79148,fc:50160,hc:77504,uc:87907,wc:18630,xc:54445,yc:80935,zc:105675,Ac:37521,Bc:47786,Cc:98349,Dc:123695,Ec:6827,Fc:29434,Gc:7282,Hc:124448,Lc:32276,Kc:76278,Mc:93911,Nc:106531,Oc:27259,Pc:27262,Qc:27263,Sc:21759,Tc:27107,Uc:62936,Vc:49568,Wc:38408,Xc:80637,Yc:68727,Zc:68728,bd:80353,cd:80356,dd:74610,ed:45707,fd:83962,gd:83970,hd:46713,jd:89711,kd:74612,ld:93265,md:74611,nd:131380,pd:128979,qd:128978,od:131391,
rd:105350,td:134800,sd:131392,vd:113533,wd:93252,xd:99357,zd:94521,Ad:114252,Bd:113532,Cd:94522,yd:94583,Dd:88E3,Ed:93253,Fd:93254,Gd:94387,Hd:94388,Id:93255,Jd:97424,ud:72502,Kd:110111,Ld:76019,Nd:117092,Od:117093,Md:89431,Pd:110466,Qd:77240,Rd:60508,Sd:137401,Td:137402,Ud:137046,Vd:73393,Wd:113534,Xd:92098,Yd:131381,Zd:84517,ae:83759,be:80357,ce:86113,de:72598,ee:72733,ge:107349,he:124275,ie:118203,je:133275,ke:133274,le:133272,me:133273,ne:133276,pe:117431,oe:133797,qe:128572,re:133405,se:117429,
te:117430,ue:117432,we:120080,xe:117259,ye:121692,ze:132972,Ae:133051,Be:133658,Ce:132971,De:97615,Ee:31402,Ge:133624,He:133623,Ie:133622,Fe:133621,Je:84774,Ke:95117,Le:98930,Me:98931,Ne:98932,Oe:43347,Pe:129889,Qe:45474,Re:100352,Se:84758,Te:98443,Ue:117985,Ve:74613,We:74614,Xe:64502,Ye:136032,Ze:74615,af:74616,bf:122224,cf:74617,df:77820,ef:74618,ff:93278,gf:93274,hf:93275,jf:93276,kf:22110,lf:29433,mf:133798,nf:132295,qf:120541,sf:82047,tf:113550,uf:75836,vf:75837,wf:42352,xf:84512,yf:76065,zf:75989,
Af:16623,Bf:32594,Cf:27240,Df:32633,Ef:74858,Gf:3945,Ff:16989,Hf:45520,If:25488,Jf:25492,Kf:25494,Lf:55760,Mf:14057,Nf:18451,Of:57204,Pf:57203,Qf:17897,Rf:57205,Sf:18198,Tf:17898,Uf:17909,Vf:43980,Wf:46220,Xf:11721,Yf:49954,Zf:96369,ag:3854,cg:56251,dg:25624,eg:16906,fg:99999,gg:68172,hg:27068,ig:47973,jg:72773,kg:26970,lg:26971,mg:96805,ng:17752,og:73233,pg:109512,qg:22256,rg:14115,sg:22696,tg:89278,ug:89277,vg:109513,wg:43278,xg:43459,yg:43464,zg:89279,Ag:43717,Bg:55764,Cg:22255,Dg:89281,Eg:40963,
Fg:43277,Gg:43442,Hg:91824,Ig:120137,Jg:96367,Kg:36850,Lg:72694,Mg:37414,Ng:36851,Pg:124863,Og:121343,Qg:73491,Rg:54473,Sg:43375,Tg:46674,Ug:32473,Vg:72901,Wg:72906,Xg:50947,Yg:50612,Zg:50613,ah:50942,bh:84938,dh:84943,eh:84939,fh:84941,gh:84944,hh:84940,ih:84942,jh:35585,kh:51926,lh:79983,mh:63238,nh:18921,oh:63241,ph:57893,qh:41182,rh:135732,sh:33424,th:22207,uh:42993,vh:36229,wh:22206,xh:22205,yh:18993,zh:19001,Ah:18990,Bh:18991,Ch:18997,Dh:18725,Eh:19003,Fh:36874,Gh:44763,Hh:33427,Ih:67793,Jh:22182,
Kh:37091,Lh:34650,Mh:50617,Nh:47261,Oh:22287,Ph:25144,Qh:97917,Rh:62397,Sh:125598,Th:36961,Uh:108035,Vh:27426,Wh:27857,Xh:27846,Yh:27854,Zh:69692,ai:61411,bi:39299,ci:38696,di:62520,fi:36382,gi:108701,hi:50663,ii:36387,ji:14908,ki:37533,li:105443,mi:61635,ni:62274,oi:133818,ri:65702,si:65703,ti:65701,vi:76256,wi:37671,xi:49953,zi:36216,Ai:28237,Bi:39553,Ci:29222,Di:26107,Ei:38050,Fi:26108,Hi:120745,Gi:26109,Ii:26110,Ji:66881,Ki:28236,Li:14586,Mi:57929,Ni:74723,Oi:44098,Pi:44099,Si:23528,Ti:61699,
Qi:134104,Ri:134103,Ui:59149,Vi:101951,Wi:97346,Xi:118051,Yi:95102,Zi:64882,aj:119505,bj:63595,cj:63349,dj:95101,ej:75240,fj:27039,gj:68823,hj:21537,ij:83464,jj:75707,kj:83113,lj:101952,mj:101953,oj:79610,pj:125755,qj:24402,rj:24400,sj:32925,tj:57173,uj:122502,vj:64423,wj:64424,xj:33986,yj:100828,zj:129089,Aj:21409,Ej:135155,Fj:135156,Gj:135157,Hj:135158,Ij:135159,Jj:135160,Kj:135161,Lj:135162,Mj:135163,Nj:135164,Oj:135165,Pj:135166,Bj:11070,Cj:11074,Dj:17880,Qj:14001,Sj:30709,Tj:30707,Uj:30711,Vj:30710,
Wj:30708,Rj:26984,Xj:63648,Yj:63649,Zj:51879,ak:111059,bk:5754,ck:20445,ek:130975,dk:130976,fk:110386,gk:113746,hk:66557,ik:17310,jk:28631,kk:21589,lk:68012,mk:60480,nk:31571,pk:76980,qk:41577,rk:45469,sk:38669,tk:13768,uk:13777,vk:62985,wk:4724,xk:59369,yk:43927,zk:43928,Ak:12924,Bk:100355,Ek:56219,Fk:27669,Gk:10337,Dk:47896,Hk:122629,Ik:121258,Jk:107598,Kk:127991,Lk:96639,Mk:107536,Nk:130169,Ok:96661,Pk:96658,Qk:116646,Rk:121122,Sk:96660,Tk:127738,Uk:127083,Vk:104443,Wk:96659,Xk:106442,Yk:134840,
Zk:63667,al:63668,bl:63669,dl:130686,fl:78314,il:55761,jl:127098,kl:134841,ll:96368,ml:67374,nl:48992,ol:49956,pl:31961,ql:26388,rl:23811,sl:5E4,ul:126250,vl:96370,wl:47355,xl:47356,yl:37935,zl:45521,Al:21760,Bl:83769,Cl:49977,Dl:49974,El:93497,Fl:93498,Gl:34325,Hl:115803,Il:123707,Jl:100081,Kl:35309,Ll:68314,Ml:25602,Nl:100339,Ol:59018,Pl:18248,Ql:50625,Rl:9729,Sl:37168,Tl:37169,Ul:21667,Vl:16749,Wl:18635,Xl:39305,Yl:18046,Zl:53969,am:8213,bm:93926,cm:102852,dm:110099,em:22678,fm:69076,hm:100856,
im:17736,jm:3832,km:55759,lm:64031,mm:93044,nm:93045,om:34388,pm:17657,qm:17655,rm:39579,sm:39578,tm:77448,um:8196,vm:11357,wm:69877,xm:8197,ym:82039};function nl(){var a=kb(ol),b;return bf(new Ve(function(c,d){a.onSuccess=function(e){Ig(e)?c(new pl(e)):d(new ql("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new ql("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new ql("Request timed out","net.timeout",e))};
b=Og("//googleads.g.doubleclick.net/pagead/id",a)}),function(c){c instanceof cf&&b.abort();
return $e(c)})}
function ql(a,b,c){Ta.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
v(ql,Ta);function pl(a){this.xhr=a}
;function rl(){this.i=0;this.h=null}
rl.prototype.then=function(a,b,c){return 1===this.i&&a?(a=a.call(c,this.h),Ue(a)?a:sl(a)):2===this.i&&b?(a=b.call(c,this.h),Ue(a)?a:tl(a)):this};
rl.prototype.getValue=function(){return this.h};
rl.prototype.$goog_Thenable=!0;function tl(a){var b=new rl;a=void 0===a?null:a;b.i=2;b.h=void 0===a?null:a;return b}
function sl(a){var b=new rl;a=void 0===a?null:a;b.i=1;b.h=void 0===a?null:a;return b}
;function ul(){if(qd())return!0;var a=F("INNERTUBE_CLIENT_NAME");return!a||"WEB"!==a&&"MWEB"!==a||Wg&&Xg("applewebkit")&&!Xg("version")&&(!Xg("safari")||Xg("gsa/"))||pc&&Xg("version/")?!0:(a=od.get("CONSENT",void 0))?a.startsWith("YES+"):!0}
;function vl(a){Ta.call(this,a.message||a.description||a.name);this.isMissing=a instanceof wl;this.isTimeout=a instanceof ql&&"net.timeout"==a.errorCode;this.isCanceled=a instanceof cf}
v(vl,Ta);vl.prototype.name="BiscottiError";function wl(){Ta.call(this,"Biscotti ID is missing from server")}
v(wl,Ta);wl.prototype.name="BiscottiMissingError";var ol={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},xl=null;function sg(){if(O("disable_biscotti_fetch_entirely_for_all_web_clients"))return $e(Error("Biscotti id fetching has been disabled entirely."));if(!ul())return $e(Error("User has not consented - not fetching biscotti id."));if("1"==ib())return $e(Error("Biscotti ID is not available in private embed mode"));xl||(xl=bf(nl().then(yl),function(a){return zl(2,a)}));
return xl}
function yl(a){a=a.xhr.responseText;if(0!=a.lastIndexOf(")]}'",0))throw new wl;a=JSON.parse(a.substr(4));if(1<(a.type||1))throw new wl;a=a.id;tg(a);xl=sl(a);Al(18E5,2);return a}
function zl(a,b){b=new vl(b);tg("");xl=tl(b);0<a&&Al(12E4,a-1);throw b;}
function Al(a,b){cg(function(){bf(nl().then(yl,function(c){return zl(b,c)}),Ea)},a)}
function Bl(){try{var a=C("yt.ads.biscotti.getId_");return a?a():sg()}catch(b){return $e(b)}}
;function Cl(a){if("1"!=ib()){a&&rg();try{Bl().then(function(){},function(){}),cg(Cl,18E5)}catch(b){Mf(b)}}}
;var Dl=Date.now().toString();
function El(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;16>a;a++){b=Date.now();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(256*Math.random())}if(Dl)for(a=1,b=0;b<Dl.length;b++)d[a%16]=d[a%16]^d[(a-1)%16]/4^Dl.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var Fl,Gl=y.ytLoggingDocDocumentNonce_;Gl||(Gl=El(),Ra("ytLoggingDocDocumentNonce_",Gl));Fl=Gl;var Hl={pf:0,Jc:1,Rc:2,yi:3,rf:4,gm:5,nj:6,Ck:7,0:"DEFAULT",1:"CHAT",2:"CONVERSATIONS",3:"MINIPLAYER",4:"DIALOG",5:"VOZ",6:"MUSIC_WATCH_TABS",7:"SHARE"};function Il(a){this.h=a}
function Jl(a){return new Il({trackingParams:a})}
Il.prototype.getAsJson=function(){var a={};void 0!==this.h.trackingParams?a.trackingParams=this.h.trackingParams:(a.veType=this.h.veType,void 0!==this.h.veCounter&&(a.veCounter=this.h.veCounter),void 0!==this.h.elementIndex&&(a.elementIndex=this.h.elementIndex));void 0!==this.h.dataElement&&(a.dataElement=this.h.dataElement.getAsJson());void 0!==this.h.youtubeData&&(a.youtubeData=this.h.youtubeData);return a};
Il.prototype.toString=function(){return JSON.stringify(this.getAsJson())};
Il.prototype.isClientVe=function(){return!this.h.trackingParams&&!!this.h.veType};function Kl(a){a=void 0===a?0:a;return 0==a?"client-screen-nonce":"client-screen-nonce."+a}
function Ll(a){a=void 0===a?0:a;return 0==a?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function Ml(a){return F(Ll(void 0===a?0:a),void 0)}
z("yt_logging_screen.getRootVeType",Ml,void 0);function Nl(a){return(a=Ml(void 0===a?0:a))?new Il({veType:a,youtubeData:void 0}):null}
function Ol(){var a=F("csn-to-ctt-auth-info");a||(a={},N("csn-to-ctt-auth-info",a));return a}
function Pl(a){a=void 0===a?0:a;var b=F(Kl(a));if(!b&&!F("USE_CSN_FALLBACK",!0))return null;b||!O("use_undefined_csn_any_layer")&&0!=a||(b="UNDEFINED_CSN");return b?b:null}
z("yt_logging_screen.getCurrentCsn",Pl,void 0);function Ql(a,b,c){var d=Ol();(c=Pl(c))&&delete d[c];b&&(d[a]=b)}
function Rl(a){return Ol()[a]}
z("yt_logging_screen.getCttAuthInfo",Rl,void 0);function Sl(a,b,c,d){c=void 0===c?0:c;if(a!==F(Kl(c))||b!==F(Ll(c)))Ql(a,d,c),N(Kl(c),a),N(Ll(c),b),b=function(){setTimeout(function(){a&&Jh("foregroundHeartbeatScreenAssociated",{clientDocumentNonce:Fl,clientScreenNonce:a},Qk)},0)},"requestAnimationFrame"in window?window.requestAnimationFrame(b):b()}
z("yt_logging_screen.setCurrentScreen",Sl,void 0);function Tl(a){Dj.call(this,1,arguments);this.csn=a}
v(Tl,Dj);var Mj=new Ej("screen-created",Tl),Ul=[],Wl=Vl,Xl=0;function Yl(a,b,c,d){var e=d.filter(function(f){f.csn!==b?(f.csn=b,f=!0):f=!1;return f});
c={csn:b,parentVe:c.getAsJson(),childVes:Ya(e,function(f){return f.getAsJson()})};
d=u(d);for(e=d.next();!e.done;e=d.next())e=e.value.getAsJson(),(gb(e)||!e.trackingParams&&!e.veType)&&jl(Error("Child VE logged with no data"));d={cttAuthInfo:Rl(b),aa:b};"UNDEFINED_CSN"==b?Zl("visualElementAttached",c,d):a?Jh("visualElementAttached",c,a,d):Rk("visualElementAttached",c,d)}
function Vl(){for(var a=Math.random()+"",b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);255<e&&(b[c++]=e&255,e>>=8);b[c++]=e}return Ec(b)}
function Zl(a,b,c){Ul.push({payloadName:a,payload:b,options:c});Xl||(Xl=Nj())}
function Oj(a){if(Ul){for(var b=u(Ul),c=b.next();!c.done;c=b.next())c=c.value,c.payload&&(c.payload.csn=a.csn,Jh(c.payloadName,c.payload,null,c.options));Ul.length=0}Xl=0}
;function $l(){this.i=new Set;this.h=new Set;this.j=new Map}
$l.prototype.clear=function(){this.i.clear();this.h.clear();this.j.clear()};
Fa($l);function am(a,b){for(var c=[],d=1;d<arguments.length;++d)c[d-1]=arguments[d];if(!bm(a)||c.some(function(e){return!bm(e)}))throw Error("Only objects may be merged.");
c=u(c);for(d=c.next();!d.done;d=c.next())cm(a,d.value);return a}
function cm(a,b){for(var c in b)if(bm(b[c])){if(c in a&&!bm(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});cm(a[c],b[c])}else if(dm(b[c])){if(c in a&&!dm(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);em(a[c],b[c])}else a[c]=b[c];return a}
function em(a,b){b=u(b);for(var c=b.next();!c.done;c=b.next())c=c.value,bm(c)?a.push(cm({},c)):dm(c)?a.push(em([],c)):a.push(c);return a}
function bm(a){return"object"===typeof a&&!Array.isArray(a)}
function dm(a){return"object"===typeof a&&Array.isArray(a)}
;function fm(a,b){Dj.call(this,1,arguments)}
v(fm,Dj);function gm(a,b){Dj.call(this,1,arguments)}
v(gm,Dj);var hm=new Ej("aft-recorded",fm),im=new Ej("timing-sent",gm);var jm=window;function km(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
var W=jm.performance||jm.mozPerformance||jm.msPerformance||jm.webkitPerformance||new km;var lm=!1,mm={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",
'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",'script[name="mobile_blazer_watch_mod"]':"mbwj"};
Pa(W.clearResourceTimings||W.webkitClearResourceTimings||W.mozClearResourceTimings||W.msClearResourceTimings||W.oClearResourceTimings||Ea,W);function nm(a){var b=om(a);if(b.aft)return b.aft;a=F((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=a.length,d=0;d<c;d++){var e=b[a[d]];if(e)return e}return NaN}
function pm(){var a;if(O("csi_use_performance_navigation_timing")){var b,c,d,e=null===(d=null===(c=null===(b=null===(a=null===W||void 0===W?void 0:W.getEntriesByType)||void 0===a?void 0:a.call(W,"navigation"))||void 0===b?void 0:b[0])||void 0===c?void 0:c.toJSON)||void 0===d?void 0:d.call(c);e?(e.requestStart=qm(e.requestStart),e.responseEnd=qm(e.responseEnd),e.redirectStart=qm(e.redirectStart),e.redirectEnd=qm(e.redirectEnd),e.domainLookupEnd=qm(e.domainLookupEnd),e.connectStart=qm(e.connectStart),
e.connectEnd=qm(e.connectEnd),e.responseStart=qm(e.responseStart),e.secureConnectionStart=qm(e.secureConnectionStart),e.domainLookupStart=qm(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=W.timing}else a=W.timing;return a}
function rm(){return O("csi_use_time_origin")&&W.timeOrigin?Math.floor(W.timeOrigin):W.timing.navigationStart}
function qm(a){return Math.round(rm()+a)}
function sm(a){var b;(b=C("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},Ra("ytcsi."+(a||"")+"data_",b));return b}
function tm(a){a=sm(a);a.info||(a.info={});return a.info}
function om(a){a=sm(a);a.tick||(a.tick={});return a.tick}
function um(a){var b=sm(a).nonce;b||(b=El(),sm(a).nonce=b);return b}
function vm(a){var b=om(a||""),c=nm(a);c&&!lm&&(Jj(hm,new fm(Math.round(c-b._start),a)),lm=!0)}
;function wm(){if(W.getEntriesByType){var a=W.getEntriesByType("paint");if(a=$a(a,function(b){return"first-paint"===b.name}))return qm(a.startTime)}a=W.timing;
return a.Gb?Math.max(0,a.Gb):0}
;function xm(){var a=C("ytcsi.debug");a||(a=[],z("ytcsi.debug",a,void 0),z("ytcsi.reference",{},void 0));return a}
function ym(a){a=a||"";var b=C("ytcsi.reference");b||(xm(),b=C("ytcsi.reference"));if(b[a])return b[a];var c=xm(),d={timerName:a,info:{},tick:{},span:{}};c.push(d);return b[a]=d}
;var zm=y.ytLoggingLatencyUsageStats_||{};z("ytLoggingLatencyUsageStats_",zm,void 0);function Am(){this.h=0}
function Bm(){Am.h||(Am.h=new Am);return Am.h}
Am.prototype.tick=function(a,b,c,d){Cm(this,"tick_"+a+"_"+b)||Rk("latencyActionTicked",{tickName:a,clientActionNonce:b},{timestamp:c,cttAuthInfo:d})};
Am.prototype.info=function(a,b,c){var d=Object.keys(a).join("");Cm(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,Rk("latencyActionInfo",a,{cttAuthInfo:c}))};
Am.prototype.span=function(a,b,c){var d=Object.keys(a).join("");Cm(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,Rk("latencyActionSpan",a,{cttAuthInfo:c}))};
function Cm(a,b){zm[b]=zm[b]||{count:0};var c=zm[b];c.count++;c.time=Q();a.h||(a.h=gg(function(){var d=Q(),e;for(e in zm)zm[e]&&6E4<d-zm[e].time&&delete zm[e];a&&(a.h=0)},5E3));
return 5<c.count?(6===c.count&&1>1E5*Math.random()&&(c=new ji("CSI data exceeded logging limit with key",b.split("_")),0<=b.indexOf("plev")||jl(c)),!0):!1}
;var X={},Dm=(X.auto_search="LATENCY_ACTION_AUTO_SEARCH",X.ad_to_ad="LATENCY_ACTION_AD_TO_AD",X.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",X["analytics.explore"]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE",X.app_startup="LATENCY_ACTION_APP_STARTUP",X["artist.analytics"]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS",X["artist.events"]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS",X["artist.presskit"]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE",X.browse="LATENCY_ACTION_BROWSE",X.channels="LATENCY_ACTION_CHANNELS",X.creator_channel_dashboard=
"LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD",X["channel.analytics"]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS",X["channel.comments"]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS",X["channel.content"]="LATENCY_ACTION_CREATOR_POST_LIST",X["channel.copyright"]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT",X["channel.editing"]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING",X["channel.monetization"]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION",X["channel.music"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC",X["channel.playlists"]=
"LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS",X["channel.translations"]="LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS",X["channel.videos"]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS",X["channel.live_streaming"]="LATENCY_ACTION_CREATOR_LIVE_STREAMING",X.chips="LATENCY_ACTION_CHIPS",X["dialog.copyright_strikes"]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES",X["dialog.uploads"]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS",X.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",X.embed="LATENCY_ACTION_EMBED",X.entity_key_serialization_perf=
"LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",X.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",X.explore="LATENCY_ACTION_EXPLORE",X.home="LATENCY_ACTION_HOME",X.library="LATENCY_ACTION_LIBRARY",X.live="LATENCY_ACTION_LIVE",X.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",X.onboarding="LATENCY_ACTION_ONBOARDING",X.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",X.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",X.parent_tools_dashboard=
"LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",X.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",X["post.comments"]="LATENCY_ACTION_CREATOR_POST_COMMENTS",X["post.edit"]="LATENCY_ACTION_CREATOR_POST_EDIT",X.prebuffer="LATENCY_ACTION_PREBUFFER",X.prefetch="LATENCY_ACTION_PREFETCH",X.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",X.profile_switcher="LATENCY_ACTION_LOGIN",X.reel_watch="LATENCY_ACTION_REEL_WATCH",X.results="LATENCY_ACTION_RESULTS",X.search_ui="LATENCY_ACTION_SEARCH_UI",X.search_suggest=
"LATENCY_ACTION_SUGGEST",X.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",X.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",X.seek="LATENCY_ACTION_PLAYER_SEEK",X.settings="LATENCY_ACTION_SETTINGS",X.tenx="LATENCY_ACTION_TENX",X.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",X.watch="LATENCY_ACTION_WATCH",X.watch_it_again="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",X["watch,watch7"]="LATENCY_ACTION_WATCH",X["watch,watch7_html5"]="LATENCY_ACTION_WATCH",X["watch,watch7ad"]="LATENCY_ACTION_WATCH",X["watch,watch7ad_html5"]=
"LATENCY_ACTION_WATCH",X.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",X.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",X["video.analytics"]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS",X["video.comments"]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS",X["video.edit"]="LATENCY_ACTION_CREATOR_VIDEO_EDIT",X["video.editor"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR",X["video.editor_async"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC",X["video.live_settings"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS",X["video.live_streaming"]=
"LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING",X["video.monetization"]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION",X["video.translations"]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS",X.voice_assistant="LATENCY_ACTION_VOICE_ASSISTANT",X.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",X.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",X),Y={},Em=(Y.ad_allowed="adTypesAllowed",Y.yt_abt="adBreakType",Y.ad_cpn="adClientPlaybackNonce",Y.ad_docid="adVideoId",Y.yt_ad_an=
"adNetworks",Y.ad_at="adType",Y.aida="appInstallDataAgeMs",Y.browse_id="browseId",Y.p="httpProtocol",Y.t="transportProtocol",Y.cs="commandSource",Y.cpn="clientPlaybackNonce",Y.ccs="creatorInfo.creatorCanaryState",Y.ctop="creatorInfo.topEntityType",Y.csn="clientScreenNonce",Y.docid="videoId",Y.GetHome_rid="requestIds",Y.GetSearch_rid="requestIds",Y.GetPlayer_rid="requestIds",Y.GetWatchNext_rid="requestIds",Y.GetBrowse_rid="requestIds",Y.GetLibrary_rid="requestIds",Y.is_continuation="isContinuation",
Y.is_nav="isNavigation",Y.b_p="kabukiInfo.browseParams",Y.is_prefetch="kabukiInfo.isPrefetch",Y.is_secondary_nav="kabukiInfo.isSecondaryNav",Y.nav_type="kabukiInfo.navigationType",Y.prev_browse_id="kabukiInfo.prevBrowseId",Y.query_source="kabukiInfo.querySource",Y.voz_type="kabukiInfo.vozType",Y.yt_lt="loadType",Y.mver="creatorInfo.measurementVersion",Y.yt_ad="isMonetized",Y.nr="webInfo.navigationReason",Y.nrsu="navigationRequestedSameUrl",Y.ncnp="webInfo.nonPreloadedNodeCount",Y.pnt="performanceNavigationTiming",
Y.prt="playbackRequiresTap",Y.plt="playerInfo.playbackType",Y.pis="playerInfo.playerInitializedState",Y.paused="playerInfo.isPausedOnLoad",Y.yt_pt="playerType",Y.fmt="playerInfo.itag",Y.yt_pl="watchInfo.isPlaylist",Y.yt_pre="playerInfo.preloadType",Y.yt_ad_pr="prerollAllowed",Y.pa="previousAction",Y.yt_red="isRedSubscriber",Y.rce="mwebInfo.responseContentEncoding",Y.rc="resourceInfo.resourceCache",Y.scrh="screenHeight",Y.scrw="screenWidth",Y.st="serverTimeMs",Y.ssdm="shellStartupDurationMs",Y.br_trs=
"tvInfo.bedrockTriggerState",Y.kebqat="kabukiInfo.earlyBrowseRequestInfo.abandonmentType",Y.kebqa="kabukiInfo.earlyBrowseRequestInfo.adopted",Y.label="tvInfo.label",Y.is_mdx="tvInfo.isMdx",Y.preloaded="tvInfo.isPreloaded",Y.aac_type="tvInfo.authAccessCredentialType",Y.upg_player_vis="playerInfo.visibilityState",Y.query="unpluggedInfo.query",Y.upg_chip_ids_string="unpluggedInfo.upgChipIdsString",Y.yt_vst="videoStreamType",Y.vph="viewportHeight",Y.vpw="viewportWidth",Y.yt_vis="isVisible",Y.rcl="mwebInfo.responseContentLength",
Y.GetSettings_rid="requestIds",Y.GetTrending_rid="requestIds",Y.GetMusicSearchSuggestions_rid="requestIds",Y.REQUEST_ID="requestIds",Y),Fm="isContinuation isNavigation kabukiInfo.earlyBrowseRequestInfo.adopted kabukiInfo.isPrefetch kabukiInfo.isSecondaryNav isMonetized navigationRequestedSameUrl performanceNavigationTiming playerInfo.isPausedOnLoad prerollAllowed isRedSubscriber tvInfo.isMdx tvInfo.isPreloaded isVisible watchInfo.isPlaylist playbackRequiresTap".split(" "),Gm={},Hm=(Gm.ccs="CANARY_STATE_",
Gm.mver="MEASUREMENT_VERSION_",Gm.pis="PLAYER_INITIALIZED_STATE_",Gm.yt_pt="LATENCY_PLAYER_",Gm.pa="LATENCY_ACTION_",Gm.ctop="TOP_ENTITY_TYPE_",Gm.yt_vst="VIDEO_STREAM_TYPE_",Gm),Im="all_vc ap aq c cbr cbrand cbrver cmodel cos cosver cplatform ctheme cver ei l_an l_mm plid srt yt_fss yt_li vpst vpni2 vpil2 icrc icrt pa GetAccountOverview_rid GetHistory_rid cmt d_vpct d_vpnfi d_vpni nsru pc pfa pfeh pftr pnc prerender psc rc start tcrt tcrc ssr vpr vps yt_abt yt_fn yt_fs yt_pft yt_pre yt_pt yt_pvis ytu_pvis yt_ref yt_sts tds".split(" ");
function Jm(a){return!!F("FORCE_CSI_ON_GEL",!1)||O("csi_on_gel")||O("enable_csi_on_gel")||O("unplugged_tvhtml5_csi_on_gel")||!!sm(a).useGel}
function Km(a,b,c){var d=Lm(c);d.gelTicks&&(d.gelTicks["tick_"+a]=!0);c||b||Q();if(Jm(c)){ym(c||"").tick[a]=b||Q();d=um(c);var e=sm(c).cttAuthInfo;"_start"===a?(a=Bm(),Cm(a,"baseline_"+d)||Rk("latencyActionBaselined",{clientActionNonce:d},{timestamp:b,cttAuthInfo:e})):Bm().tick(a,d,b,e);vm(c);return!0}return!1}
function Mm(a,b,c){c=Lm(c);if(c.gelInfos)c.gelInfos["info_"+a]=!0;else{var d={};c.gelInfos=(d["info_"+a]=!0,d)}if(a.match("_rid")){var e=a.split("_rid")[0];a="REQUEST_ID"}if(a in Em){c=Em[a];0<=Wa(Fm,c)&&(b=!!b);a in Hm&&"string"===typeof b&&(b=Hm[a]+b.toUpperCase());a=b;b=c.split(".");for(var f=d={},g=0;g<b.length-1;g++){var h=b[g];f[h]={};f=f[h]}f[b[b.length-1]]="requestIds"===c?[{id:a,endpoint:e}]:a;return am({},d)}0<=Wa(Im,a)||jl(new ji("Unknown label logged with GEL CSI",a))}
function Lm(a){a=sm(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function Nm(a){a=Lm(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
;function Om(a,b,c){null!==b&&(tm(c)[a]=b,Jm(c)?(a=Mm(a,b,c))&&Jm(c)&&(b=ym(c||""),am(b.info,a),am(Nm(c),a),b=um(c),c=sm(c).cttAuthInfo,Bm().info(a,b,c)):ym(c||"").info[a]=b)}
function Z(a,b,c){var d=om(c);if(!b&&"_"!==a[0]){var e=a;W.mark&&(0==e.lastIndexOf("mark_",0)||(e="mark_"+e),c&&(e+=" ("+c+")"),W.mark(e))}e=b||Q();d[a]=e;Km(a,b,c)||c||(Pm(),ym("").tick[a]=b||Q());return d[a]}
function Qm(){var a=um(void 0);requestAnimationFrame(function(){setTimeout(function(){a===um(void 0)&&Z("ol",void 0,void 0)},0)})}
function Pm(){if(!C("yt.timing.pingSent_")){var a=F("TIMING_ACTION",void 0),b=om();if(a=!!C("ytglobal.timingready_")&&a)a="_start"in om(void 0);if(a&&nm()){vm();a=!0;var c=F("TIMING_WAIT",[]);if(c.length)for(var d=0,e=c.length;d<e;++d)if(!(c[d]in b)){a=!1;break}if(a&&!Jm()){c=om();d=tm();e=c._start;var f=F("CSI_SERVICE_NAME","youtube");a={v:2,s:f,action:F("TIMING_ACTION",void 0)};b=d.srt;void 0!==c.srt&&delete d.srt;c.aft=nm();var g=om(void 0),h=g.pbr,k=g.vc;g=g.pbs;h&&k&&g&&h<k&&k<g&&tm(void 0).yt_pvis&&
"youtube"===f&&(Om("yt_lt","hot_bg"),f=c.vc,h=c.pbs,delete c.aft,d.aft=Math.round(h-f));for(var l in d)"_"!==l.charAt(0)&&(a[l]=d[l]);c.ps=Q();l={};f=[];for(var n in c)"_"!==n.charAt(0)&&(h=Math.round(c[n]-e),l[n]=h,f.push(n+"."+h));a.rt=f.join(",");n=!!d.ap;c="";for(var p in a)a.hasOwnProperty(p)&&(c+="&"+p+"="+a[p]);p="/csi_204?"+c.substring(1);window.navigator&&n?ch(p):$g(p);z("yt.timing.pingSent_",!0,void 0);Jj(im,new gm(l.aft+(Number(b)||0)))}}}}
function Rm(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=Tf+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function Sm(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;"SCRIPT"===d?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):"LINK"===d&&(c=a.href);Zb()&&a.setAttribute("nonce",Zb());return c?(a=W.getEntriesByName(c))&&a[0]&&(a=a[0],c=rm(),Z("rsf_"+b,c+Math.round(a.fetchStart)),Z("rse_"+b,c+Math.round(a.responseEnd)),void 0!==a.transferSize&&0===a.transferSize)?!0:!1:!1}
function Tm(){var a=window.location.protocol,b=W.getEntriesByType("resource");b=Xa(b,function(c){return 0===c.name.indexOf(a+"//fonts.gstatic.com/s/")});
(b=Za(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&0<b.startTime&&0<b.responseEnd&&(Z("wffs",qm(b.startTime)),Z("wffe",qm(b.responseEnd)))}
var Um=window;Um.ytcsi&&(Um.ytcsi.info=Om,Um.ytcsi.tick=Z);function Vm(){this.A=[];this.u=[];this.h=[];this.l=[];this.m=[];this.i=new Set;this.B=new Map}
function Wm(a,b,c){c=void 0===c?0:c;b.then(function(d){var e,f;a.i.has(c)&&a.j&&a.j();var g=Pl(c),h=Nl(c);g&&h&&((null===(e=d.response)||void 0===e?0:e.trackingParams)&&Yl(a.client,g,h,[Jl(d.response.trackingParams)]),(null===(f=d.playerResponse)||void 0===f?0:f.trackingParams)&&Yl(a.client,g,h,[Jl(d.playerResponse.trackingParams)]))})}
function Xm(a,b,c,d){d=void 0===d?0:d;if(a.i.has(d))a.A.push([b,c]);else{var e=Pl(d);c=c||Nl(d);e&&c&&Yl(a.client,e,c,[b])}}
Vm.prototype.clickCommand=function(a,b,c){a=a.clickTrackingParams;c=void 0===c?0:c;if(a)if(c=Pl(void 0===c?0:c)){var d=this.client;var e="INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK";a={csn:c,ve:Jl(a).getAsJson(),gestureType:e};b&&(a.clientData=b);b={cttAuthInfo:Rl(c),aa:c};"UNDEFINED_CSN"==c?Zl("visualElementGestured",a,b):d?Jh("visualElementGestured",a,d,b):Rk("visualElementGestured",a,b);b=!0}else b=!1;else b=!1;return b};
function Ym(a,b,c){c=void 0===c?{}:c;a.i.add(c.layer||0);a.j=function(){Zm(a,b,c);var f=Nl(c.layer);if(f){for(var g=u(a.A),h=g.next();!h.done;h=g.next())h=h.value,Xm(a,h[0],h[1]||f,c.layer);f=u(a.u);for(g=f.next();!g.done;g=f.next()){var k=g.value;g=void 0;g=void 0===g?0:g;h=Pl(g);var l=k[0]||Nl(g);h&&l&&(g=a.client,k=k[1],k={csn:h,ve:l.getAsJson(),clientData:k},l={cttAuthInfo:Rl(h),aa:h},"UNDEFINED_CSN"==h?Zl("visualElementStateChanged",k,l):g?Jh("visualElementStateChanged",k,g,l):Rk("visualElementStateChanged",
k,l))}}};
Pl(c.layer)||a.j();if(c.Va)for(var d=u(c.Va),e=d.next();!e.done;e=d.next())Wm(a,e.value,c.layer);else kl(Error("Delayed screen needs a data promise."))}
function Zm(a,b,c){c=void 0===c?{}:c;c.layer||(c.layer=0);var d=void 0!==c.Hb?c.Hb:c.layer;var e=Pl(d);d=Nl(d);var f;d&&(void 0!==c.parentCsn?f={clientScreenNonce:c.parentCsn,visualElement:d}:e&&"UNDEFINED_CSN"!==e&&(f={clientScreenNonce:e,visualElement:d}));var g,h=F("EVENT_ID");"UNDEFINED_CSN"===e&&h&&(g={servletData:{serializedServletEventId:h}});try{var k=a.client;h=f;var l=c.Ua,n=c.cttAuthInfo,p=c.Em,q=Wl(),r={csn:q,pageVe:(new Il({veType:b,youtubeData:g})).getAsJson()};h&&h.visualElement?(r.implicitGesture=
{parentCsn:h.clientScreenNonce,gesturedVe:h.visualElement.getAsJson()},p&&(r.implicitGesture.gestureType=p)):h&&jl(new ji("newScreen() parent element does not have a VE - rootVe",b));l&&(r.cloneCsn=l);l={cttAuthInfo:n,aa:q};k?Jh("screenCreated",r,k,l):Rk("screenCreated",r,l);Jj(Mj,new Tl(q));var A=q}catch(B){ll(B,{Jm:b,rootVe:d,parentVisualElement:void 0,Dm:e,Im:f,Ua:c.Ua});kl(B);return}Sl(A,b,c.layer,c.cttAuthInfo);if((b=e&&"UNDEFINED_CSN"!==e&&d)&&!(b=O("screen_manager_skip_hide_killswitch"))){a:{b=
u(Object.values(Hl));for(f=b.next();!f.done;f=b.next())if(Pl(f.value)==e){b=!0;break a}b=!1}b=!b}b&&(b=a.client,f=!0,k=(f=void 0===f?!1:f)?16:8,d={csn:e,ve:d.getAsJson(),eventType:k},f={cttAuthInfo:Rl(e),aa:e,ub:f},"UNDEFINED_CSN"==e?Zl("visualElementHidden",d,f):b?Jh("visualElementHidden",d,b,f):Rk("visualElementHidden",d,f));a.h[a.h.length-1]&&!a.h[a.h.length-1].csn&&(a.h[a.h.length-1].csn=A||"");Om("csn",A);$l.getInstance().clear();d=Nl(c.layer);e&&"UNDEFINED_CSN"!==e&&d&&(O("web_mark_root_visible")||
O("music_web_mark_root_visible"))&&(e=A,A={csn:e,ve:d.getAsJson(),eventType:1},b={cttAuthInfo:Rl(e),aa:e},"UNDEFINED_CSN"==e?Zl("visualElementShown",A,b):Rk("visualElementShown",A,b));a.i.delete(c.layer||0);a.j=void 0;e=u(a.B);for(A=e.next();!A.done;A=e.next())b=u(A.value),A=b.next().value,b=b.next().value,b.has(c.layer)&&d&&Xm(a,A,d,c.layer);for(c=0;c<a.l.length;c++){e=a.l[c];try{e()}catch(B){kl(B)}}for(c=a.l.length=0;c<a.m.length;c++){e=a.m[c];try{e()}catch(B){kl(B)}}}
;function $m(a){a&&(a.dataset?a.dataset[an("loaded")]="true":a.setAttribute("data-loaded","true"))}
function bn(a,b){return a?a.dataset?a.dataset[an(b)]:a.getAttribute("data-"+b):null}
var cn={};function an(a){return cn[a]||(cn[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;var dn=/\.vflset|-vfl[a-zA-Z0-9_+=-]+/,en=/-[a-zA-Z]{2,3}_[a-zA-Z]{2,3}(?=(\/|$))/;function fn(a,b,c){c=void 0===c?null:c;if(window.spf&&spf.script){c="";if(a){var d=a.indexOf("jsbin/"),e=a.lastIndexOf(".js"),f=d+6;-1<d&&-1<e&&e>f&&(c=a.substring(f,e),c=c.replace(dn,""),c=c.replace(en,""),c=c.replace("debug-",""),c=c.replace("tracing-",""))}spf.script.load(a,c,b)}else gn(a,b,c)}
function gn(a,b,c){c=void 0===c?null:c;var d=hn(a),e=document.getElementById(d),f=e&&bn(e,"loaded"),g=e&&!f;f?b&&b():(b&&(f=hh(d,b),b=""+Ja(b),jn[b]=f),g||(e=kn(a,d,function(){bn(e,"loaded")||($m(e),kh(d),cg(Qa(lh,d),0))},c)))}
function kn(a,b,c,d){d=void 0===d?null:d;var e=Vc(document,"SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);Oc(e,Me(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function ln(a){a=hn(a);var b=document.getElementById(a);b&&(lh(a),b.parentNode.removeChild(b))}
function mn(a,b){a&&b&&(a=""+Ja(b),(a=jn[a])&&jh(a))}
function hn(a){var b=document.createElement("a");Wb(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+ac(a)}
var jn={};var nn=[],on=!1;function pn(){if(!O("disable_biscotti_fetch_for_ad_blocker_detection")&&!O("disable_biscotti_fetch_entirely_for_all_web_clients")&&ul()&&"1"!=ib()){var a=function(){on=!0;"google_ad_status"in window?N("DCLKSTAT",1):N("DCLKSTAT",2)};
try{fn("//static.doubleclick.net/instream/ad_status.js",a)}catch(b){}nn.push(ig(function(){if(!(on||"google_ad_status"in window)){try{mn("//static.doubleclick.net/instream/ad_status.js",a)}catch(b){}on=!0;N("DCLKSTAT",3)}},5E3))}}
function qn(){var a=Number(F("DCLKSTAT",0));return isNaN(a)?0:a}
;function rn(){this.i=!1;this.h=null}
rn.prototype.initialize=function(a,b,c,d){d=void 0===d?!1:d;var e,f;if(a.program){var g=null!==(e=a.interpreterScript)&&void 0!==e?e:null,h=null!==(f=a.interpreterUrl)&&void 0!==f?f:null;if(a.interpreterSafeScript){g=a.interpreterSafeScript;sb("From proto message. b/166824318");g=g.privateDoNotAccessOrElseSafeScriptWrappedValue||"";var k=pb();g=k?k.createScript(g):g;g=(new ub(g)).toString()}a.interpreterSafeUrl&&(h=a.interpreterSafeUrl,sb("From proto message. b/166824318"),h=yb(h.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue||
"").toString());sn(this,g,h,a.program,b,c,d)}else jl(Error("Cannot initialize botguard without program"))};
function sn(a,b,c,d,e,f,g){g=void 0===g?!1:g;c?(a.i=!0,fn(c,function(){a.i=!1;var h=0<=c.indexOf("/th/");(h?window.trayride:window.botguard)?tn(a,d,!!g,h,e):(ln(c),jl(new ji("Unable to load Botguard","from "+c)))},f)):b&&(f=Vc(document,"SCRIPT"),f.textContent=b,f.nonce=Zb(),document.head.appendChild(f),document.head.removeChild(f),((b=b.includes("trayride"))?window.trayride:window.botguard)?tn(a,d,!!g,b,e):jl(Error("Unable to load Botguard from JS")))}
function tn(a,b,c,d,e){var f,g;if(d=d?null===(f=window.trayride)||void 0===f?void 0:f.ad:null===(g=window.botguard)||void 0===g?void 0:g.bg)if(c)try{un(a,new d(b,e?function(){return e(b)}:Ea))}catch(h){h instanceof Error&&jl(h)}else{try{un(a,new d(b))}catch(h){h instanceof Error&&jl(h)}e&&e(b)}else jl(Error("Failed to finish initializing VM"))}
rn.prototype.invoke=function(a){a=void 0===a?{}:a;return this.h?this.h.hasOwnProperty("hot")?this.h.hot(void 0,void 0,a):this.h.invoke(void 0,void 0,a):null};
rn.prototype.dispose=function(){this.h=null};
function un(a,b){a.h=b}
;var vn=new rn;function wn(){return!!vn.h}
function xn(a){a=void 0===a?{}:a;return vn.invoke(a)}
;var yn=window,zn=/[A-Za-z]+\/[0-9.]+/g;function An(a,b){if(a.replace(zn,"")!==b.replace(zn,""))return!1;a=a.match(zn);b=b.match(zn);if(a.length!==b.length)return!1;for(var c=0;c<a.length;c++){var d=a[c],e=b[c];if(!d.startsWith(e)&&!e.startsWith(d))return!1}return!0}
function Bn(){var a=yn.uaChPolyfill.state;if(0===a.type)Rk("clientHintsPolyfillEvent",{clientHintsSupported:!1});else{var b=navigator.userAgent,c=void 0!==a.syntheticUa&&An(a.syntheticUa,b),d={clientHintsSupported:!0,uaAccessedBeforePolyfill:a.didAccessUaBeforePolyfillAvailable,syntheticUaMatches:c};a.didAccessUaBeforePolyfillAvailable&&(d.uaAccessBeforePolyfillCount=a.uaAccessBeforePolyfillCount,a.firstAccessUaError&&(d.firstUaAccessStack=String(a.firstAccessUaError.stack).replace(/\n/g,""),kl(a.firstAccessUaError)),
d.polyfillAvailabilityDelayMs=a.polyfillAvailabilityDelay);Rk("clientHintsPolyfillEvent",d);c||(b={syntheticUa:a.syntheticUa,ua:b},b.brand=a.data.brands.map(function(e){return'"'+e.brand+'"; v="'+e.version+'"'}),b.mobileness=a.data.mobile,a=a.data.values,a.architecture&&(b.platformArchitecture=a.architecture),a.model&&(b.model=a.model),a.platform&&(b.platformBrand=a.platform),a.platformVersion&&(b.platformVersion=a.platformVersion),a.uaFullVersion&&(b.fullVersion=a.uaFullVersion),Rk("clientHintsPolyfillDiagnostics",
b))}}
var Cn=!1;function Dn(){var a;1===(null===(a=yn.uaChPolyfill)||void 0===a?void 0:a.state.type)?Cn||(yn.uaChPolyfill.onReady=Dn,Cn=!0):yn.uaChPolyfill&&Bn()}
;function En(a,b,c){L.call(this);var d=this;c=c||F("POST_MESSAGE_ORIGIN",void 0)||window.document.location.protocol+"//"+window.document.location.hostname;this.j=b||null;this.C="*";this.l=c;this.sessionId=null;this.channel="widget";this.J=!!a;this.B=function(e){a:if(!("*"!=d.l&&e.origin!=d.l||d.j&&e.source!=d.j||"string"!==typeof e.data)){try{var f=JSON.parse(e.data)}catch(g){break a}if(!(null==f||d.J&&(d.sessionId&&d.sessionId!=f.id||d.channel&&d.channel!=f.channel))&&f)switch(f.event){case "listening":"null"!=
e.origin&&(d.l=d.C=e.origin);d.j=e.source;d.sessionId=f.id;d.i&&(d.i(),d.i=null);break;case "command":d.m&&(!d.u||0<=Wa(d.u,f.func))&&d.m(f.func,f.args,e.origin)}}};
this.u=this.i=this.m=null;window.addEventListener("message",this.B)}
v(En,L);En.prototype.sendMessage=function(a,b){if(b=b||this.j){this.sessionId&&(a.id=this.sessionId);this.channel&&(a.channel=this.channel);try{var c=JSON.stringify(a);b.postMessage(c,this.C)}catch(d){Nf(d)}}};
En.prototype.D=function(){window.removeEventListener("message",this.B);L.prototype.D.call(this)};function Fn(){this.i=[];this.isReady=!1;this.j={};var a=this.h=new En(!!F("WIDGET_ID_ENFORCE")),b=this.Jb.bind(this);a.m=b;a.u=null;this.h.channel="widget";if(a=F("WIDGET_ID"))this.h.sessionId=a}
m=Fn.prototype;m.Jb=function(a,b,c){"addEventListener"===a&&b?(a=b[0],this.j[a]||"onReady"===a||(this.addEventListener(a,Gn(this,a)),this.j[a]=!0)):this.Pa(a,b,c)};
m.Pa=function(){};
function Gn(a,b){return function(c){return a.sendMessage(b,c)}}
m.addEventListener=function(){};
m.vb=function(){this.isReady=!0;this.sendMessage("initialDelivery",this.Fa());this.sendMessage("onReady");E(this.i,this.kb,this);this.i=[]};
m.Fa=function(){return null};
function Hn(a,b){a.sendMessage("infoDelivery",b)}
m.kb=function(a){this.isReady?this.h.sendMessage(a):this.i.push(a)};
m.sendMessage=function(a,b){this.kb({event:a,info:void 0===b?null:b})};
m.dispose=function(){this.h=null};function In(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function Jn(a,b,c){if("string"===typeof a)return{videoId:a,startSeconds:b,suggestedQuality:c};b=["endSeconds","startSeconds","mediaContentUrl","suggestedQuality","videoId"];c={};for(var d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}
function Kn(a,b,c,d){if(Ia(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};"string"===typeof a&&16===a.length?b.list="PL"+a:b.playlist=a;return b}
;function Ln(a){Fn.call(this);this.listeners=[];this.api=a;this.addEventListener("onReady",this.onReady.bind(this));this.addEventListener("onVideoProgress",this.Qb.bind(this));this.addEventListener("onVolumeChange",this.Rb.bind(this));this.addEventListener("onApiChange",this.Lb.bind(this));this.addEventListener("onPlaybackQualityChange",this.Nb.bind(this));this.addEventListener("onPlaybackRateChange",this.Ob.bind(this));this.addEventListener("onStateChange",this.Pb.bind(this));this.addEventListener("onWebglSettingsChanged",
this.Sb.bind(this))}
v(Ln,Fn);m=Ln.prototype;
m.Pa=function(a,b,c){if(this.api.isExternalMethodAvailable(a,c)){b=b||[];if(0<b.length&&In(a)){var d=b;if(Ia(d[0])&&!Array.isArray(d[0]))var e=d[0];else switch(e={},a){case "loadVideoById":case "cueVideoById":e=Jn(d[0],void 0!==d[1]?Number(d[1]):void 0,d[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":e=d[0];"string"===typeof e&&(e={mediaContentUrl:e,startSeconds:void 0!==d[1]?Number(d[1]):void 0,suggestedQuality:d[2]});b:{if((d=e.mediaContentUrl)&&(d=/\/([ve]|embed)\/([^#?]+)/.exec(d))&&d[2]){d=
d[2];break b}d=null}e.videoId=d;e=Jn(e);break;case "loadPlaylist":case "cuePlaylist":e=Kn(d[0],d[1],d[2],d[3])}b.length=1;b[0]=e}this.api.handleExternalCall(a,b,c);In(a)&&Hn(this,this.Fa())}};
m.onReady=function(){var a=this.vb.bind(this);this.h.i=a};
m.addEventListener=function(a,b){this.listeners.push({eventType:a,listener:b});this.api.addEventListener(a,b)};
m.Fa=function(){if(!this.api)return null;var a=this.api.getApiInterface();ab(a,"getVideoData");for(var b={apiInterface:a},c=0,d=a.length;c<d;c++){var e=a[c];if(0===e.search("get")||0===e.search("is")){var f=0;0===e.search("get")?f=3:0===e.search("is")&&(f=2);f=e.charAt(f).toLowerCase()+e.substr(f+1);try{var g=this.api[e]();b[f]=g}catch(h){}}}b.videoData=this.api.getVideoData();b.currentTimeLastUpdated_=Date.now()/1E3;return b};
m.Pb=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&(a.storyboardFormat=this.api.getStoryboardFormat());Hn(this,a)};
m.Nb=function(a){Hn(this,{playbackQuality:a})};
m.Ob=function(a){Hn(this,{playbackRate:a})};
m.Lb=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],l=this.api.getOption(e,k);b[e][k]=l}}this.sendMessage("apiInfoDelivery",b)};
m.Rb=function(){Hn(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
m.Qb=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());Hn(this,a)};
m.Sb=function(){var a={sphericalProperties:this.api.getSphericalProperties()};Hn(this,a)};
m.dispose=function(){Fn.prototype.dispose.call(this);for(var a=0;a<this.listeners.length;a++){var b=this.listeners[a];this.api.removeEventListener(b.eventType,b.listener)}this.listeners=[]};function Mn(a){L.call(this);this.i={};this.started=!1;this.connection=a;this.connection.subscribe("command",this.gb,this)}
v(Mn,L);m=Mn.prototype;m.start=function(){this.started||this.h||(this.started=!0,this.connection.da("RECEIVING"))};
m.da=function(a,b){this.started&&!this.h&&this.connection.da(a,b)};
m.gb=function(a,b,c){if(this.started&&!this.h){var d=b||{};switch(a){case "addEventListener":"string"===typeof d.event&&this.addListener(d.event);break;case "removeEventListener":"string"===typeof d.event&&this.removeListener(d.event);break;default:this.api.isReady()&&this.api.isExternalMethodAvailable(a,c||null)&&(b=Nn(a,b||{}),c=this.api.handleExternalCall(a,b,c||null),(c=On(a,c))&&this.da(a,c))}}};
m.addListener=function(a){if(!(a in this.i)){var b=this.Mb.bind(this,a);this.i[a]=b;this.addEventListener(a,b)}};
m.Mb=function(a,b){this.started&&!this.h&&this.connection.da(a,this.Ea(a,b))};
m.Ea=function(a,b){if(null!=b)return{value:b}};
m.removeListener=function(a){a in this.i&&(this.removeEventListener(a,this.i[a]),delete this.i[a])};
m.D=function(){var a=this.connection;a.h||nf(a.i,"command",this.gb,this);this.connection=null;for(var b in this.i)this.i.hasOwnProperty(b)&&this.removeListener(b);L.prototype.D.call(this)};function Pn(a,b){Mn.call(this,b);this.api=a;this.start()}
v(Pn,Mn);Pn.prototype.addEventListener=function(a,b){this.api.addEventListener(a,b)};
Pn.prototype.removeEventListener=function(a,b){this.api.removeEventListener(a,b)};
function Nn(a,b){switch(a){case "loadVideoById":return a=Jn(b),[a];case "cueVideoById":return a=Jn(b),[a];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return a=Kn(b),[a];case "cuePlaylist":return a=Kn(b),[a];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];
case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function On(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
Pn.prototype.Ea=function(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}return Mn.prototype.Ea.call(this,a,b)};
Pn.prototype.D=function(){Mn.prototype.D.call(this);delete this.api};function Qn(a){a=void 0===a?!1:a;L.call(this);this.i=new M(a);Ud(this,Qa(Sd,this.i))}
D(Qn,L);Qn.prototype.subscribe=function(a,b,c){return this.h?0:this.i.subscribe(a,b,c)};
Qn.prototype.l=function(a,b){this.h||this.i.ca.apply(this.i,arguments)};function Rn(a,b,c){Qn.call(this);this.j=a;this.destination=b;this.id=c}
v(Rn,Qn);Rn.prototype.da=function(a,b){this.h||this.j.da(this.destination,this.id,a,b)};
Rn.prototype.D=function(){this.destination=this.j=null;Qn.prototype.D.call(this)};function Sn(a,b,c){L.call(this);this.destination=a;this.origin=c;this.i=$f(window,"message",this.j.bind(this));this.connection=new Rn(this,a,b);Ud(this,Qa(Sd,this.connection))}
v(Sn,L);Sn.prototype.da=function(a,b,c,d){this.h||a!==this.destination||(a={id:b,command:c},d&&(a.data=d),this.destination.postMessage(Oe(a),this.origin))};
Sn.prototype.j=function(a){var b;if(b=!this.h)if(b=a.origin===this.origin)a:{b=this.destination;do{b:{var c=a.source;do{if(c===b){c=!0;break b}if(c===c.parent)break;c=c.parent}while(null!=c);c=!1}if(c){b=!0;break a}b=b.opener}while(null!=b);b=!1}if(b&&(b=a.data,"string"===typeof b)){try{b=JSON.parse(b)}catch(d){return}b.command&&(c=this.connection,c.h||c.l("command",b.command,b.data,a.origin))}};
Sn.prototype.D=function(){ag(this.i);this.destination=null;L.prototype.D.call(this)};function Tn(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||kb(b);this.assets=a.assets||{};this.attrs=a.attrs||kb(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
Tn.prototype.clone=function(){var a=new Tn,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];"object"==Ga(c)?a[b]=kb(c):a[b]=c}return a};var Un=/cssbin\/(?:debug-)?([a-zA-Z0-9_-]+?)(?:-2x|-web|-rtl|-vfl|.css)/;function Vn(a){a=a||"";if(window.spf){var b=a.match(Un);spf.style.load(a,b?b[1]:"",void 0)}else Wn(a)}
function Wn(a){var b=Xn(a),c=document.getElementById(b),d=c&&bn(c,"loaded");d||c&&!d||(c=Yn(a,b,function(){bn(c,"loaded")||($m(c),kh(b),cg(Qa(lh,b),0))}))}
function Yn(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=Me(a);Xb(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function Xn(a){var b=Vc(document,"A");sb("This URL is never added to the DOM");Wb(b,new Hb(a,Ib));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+ac(a)}
;function Zn(){L.call(this);this.i=[]}
v(Zn,L);Zn.prototype.D=function(){for(;this.i.length;){var a=this.i.pop();a.target.removeEventListener(a.name,a.Ra,void 0)}L.prototype.D.call(this)};function $n(){Zn.apply(this,arguments)}
v($n,Zn);function ao(a,b,c,d){L.call(this);var e=this;this.J=b;this.webPlayerContextConfig=d;this.Aa=!1;this.api={};this.ga=this.m=null;this.L=new M;this.i={};this.T=this.ma=this.elementId=this.Ba=this.config=null;this.S=!1;this.l=this.B=null;this.na={};this.nb=["onReady"];this.lastError=null;this.Qa=NaN;this.C={};this.ob=new $n(this);this.fa=0;this.j=this.u=a;Ud(this,Qa(Sd,this.L));bo(this);co(this);Ud(this,Qa(Sd,this.ob));c?this.fa=cg(function(){e.loadNewVideoConfig(c)},0):d&&(eo(this),fo(this))}
v(ao,L);m=ao.prototype;m.getId=function(){return this.J};
m.loadNewVideoConfig=function(a){if(!this.h){this.fa&&(dg(this.fa),this.fa=0);var b=a||{};b instanceof Tn||(b=new Tn(b));this.config=b;this.setConfig(a);fo(this);this.isReady()&&go(this)}};
function eo(a){var b,c;a.webPlayerContextConfig?c=a.webPlayerContextConfig.rootElementId:c=a.config.attrs.id;a.elementId=c||a.elementId;"video-player"===a.elementId&&(a.elementId=a.J,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.J:a.config.attrs.id=a.J);(null===(b=a.j)||void 0===b?void 0:b.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
m.setConfig=function(a){var b;this.Ba=a;this.config=ho(a);eo(this);this.ma||(this.ma=io(this,(null===(b=this.config.args)||void 0===b?void 0:b.jsapicallback)||"onYouTubePlayerReady"));this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if(null===(c=this.config)||void 0===c?0:c.attrs)a=this.config.attrs,(c=a.width)&&this.j&&(this.j.style.width=fd(Number(c)||c)),(a=a.height)&&this.j&&(this.j.style.height=fd(Number(a)||a))};
function go(a){var b;a.config&&!0!==a.config.loaded&&(a.config.loaded=!0,!a.config.args||"0"!==a.config.args.autoplay&&0!==a.config.args.autoplay&&!1!==a.config.args.autoplay?a.api.loadVideoByPlayerVars(null!==(b=a.config.args)&&void 0!==b?b:null):a.api.cueVideoByPlayerVars(a.config.args))}
function jo(a){var b=!0,c=ko(a);c&&a.config&&(a=lo(a),b=bn(c,"version")===a);return b&&!!C("yt.player.Application.create")}
function fo(a){if(!a.h&&!a.S){var b=jo(a);if(b&&"html5"===(ko(a)?"html5":null))a.T="html5",a.isReady()||mo(a);else if(no(a),a.T="html5",b&&a.l&&a.u)a.u.appendChild(a.l),mo(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.B=function(){c=!0;var d=oo(a,"player_bootstrap_method")?C("yt.player.Application.createAlternate")||C("yt.player.Application.create"):C("yt.player.Application.create");var e=a.config?ho(a.config):void 0;d&&d(a.u,e,a.webPlayerContextConfig);mo(a)};
a.S=!0;b?a.B():(fn(lo(a),a.B),(b=po(a))&&Vn(b),qo(a)&&!c&&z("yt.player.Application.create",null,void 0))}}}
function ko(a){var b=Rc(a.elementId);!b&&a.j&&a.j.querySelector&&(b=a.j.querySelector("#"+a.elementId));return b}
function mo(a){var b;if(!a.h){var c=ko(a),d=!1;c&&c.getApiInterface&&c.getApiInterface()&&(d=!0);d?(a.S=!1,!oo(a,"html5_remove_not_servable_check_killswitch")&&(null===c||void 0===c?0:c.isNotServable)&&a.config&&(null===c||void 0===c?0:c.isNotServable(null===(b=a.config.args)||void 0===b?void 0:b.video_id))||ro(a)):a.Qa=cg(function(){mo(a)},50)}}
function ro(a){bo(a);a.Aa=!0;var b=ko(a);if(b){a.m=so(a,b,"addEventListener");a.ga=so(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=so(a,b,f))}}for(var g in a.i)a.i.hasOwnProperty(g)&&a.m&&a.m(g,a.i[g]);go(a);a.ma&&a.ma(a.api);a.L.ca("onReady",a.api)}
function so(a,b,c){var d=b[c];return function(e){for(var f=[],g=0;g<arguments.length;++g)f[g-0]=arguments[g];try{return a.lastError=null,d.apply(b,f)}catch(h){"sendAbandonmentPing"!==c&&(h.params=c,a.lastError=h,jl(h))}}}
function bo(a){a.Aa=!1;if(a.ga)for(var b in a.i)a.i.hasOwnProperty(b)&&a.ga(b,a.i[b]);for(var c in a.C)a.C.hasOwnProperty(c)&&dg(Number(c));a.C={};a.m=null;a.ga=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.Ba};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
m.isReady=function(){return this.Aa};
function co(a){a.addEventListener("WATCH_LATER_VIDEO_ADDED",function(b){kh("WATCH_LATER_VIDEO_ADDED",b)});
a.addEventListener("WATCH_LATER_VIDEO_REMOVED",function(b){kh("WATCH_LATER_VIDEO_REMOVED",b)});
a.addEventListener("onAdAnnounce",function(b){kh("a11y-announce",b)})}
m.addEventListener=function(a,b){var c=this,d=io(this,b);d&&(0<=Wa(this.nb,a)||this.i[a]||(b=to(this,a),this.m&&this.m(a,b)),this.L.subscribe(a,d),"onReady"===a&&this.isReady()&&cg(function(){d(c.api)},0))};
m.removeEventListener=function(a,b){this.h||(b=io(this,b))&&nf(this.L,a,b)};
function io(a,b){var c=b;if("string"===typeof b){if(a.na[b])return a.na[b];c=function(d){for(var e=[],f=0;f<arguments.length;++f)e[f-0]=arguments[f];if(f=C(b))try{f.apply(y,e)}catch(g){kl(g)}};
a.na[b]=c}return c?c:null}
function to(a,b){var c="ytPlayer"+b+a.J;a.i[b]=c;y[c]=function(d){var e=cg(function(){if(!a.h){a.L.ca(b,d);var f=a.C,g=String(e);g in f&&delete f[g]}},0);
hb(a.C,String(e))};
return c}
m.getPlayerType=function(){return this.T||(ko(this)?"html5":null)};
m.getLastError=function(){return this.lastError};
function no(a){a.cancel();bo(a);a.T=null;a.config&&(a.config.loaded=!1);var b=ko(a);b&&(jo(a)||!qo(a)?a.l=b:(b&&b.destroy&&b.destroy(),a.l=null));if(a.u)for(a=a.u;b=a.firstChild;)a.removeChild(b)}
m.cancel=function(){this.B&&mn(lo(this),this.B);dg(this.Qa);this.S=!1};
m.D=function(){no(this);if(this.l&&this.config&&this.l.destroy)try{this.l.destroy()}catch(b){kl(b)}this.na=null;for(var a in this.i)this.i.hasOwnProperty(a)&&(y[this.i[a]]=null);this.Ba=this.config=this.api=null;delete this.u;delete this.j;L.prototype.D.call(this)};
function qo(a){var b,c;a=null===(c=null===(b=a.config)||void 0===b?void 0:b.args)||void 0===c?void 0:c.fflags;return!!a&&-1!==a.indexOf("player_destroy_old_version=true")}
function lo(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function po(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function oo(a,b){var c;if(a.webPlayerContextConfig)var d=a.webPlayerContextConfig.serializedExperimentFlags;else if(null===(c=a.config)||void 0===c?0:c.args)d=a.config.args.fflags;return"true"===wg(d||"","&")[b]}
function ho(a){for(var b={},c=u(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]="object"===typeof e?kb(e):e}return b}
;var uo={},vo="player_uid_"+(1E9*Math.random()>>>0);function wo(a,b,c){var d="player";c=void 0===c?!0:c;d="string"===typeof d?Rc(d):d;var e=vo+"_"+Ja(d),f=uo[e];if(f&&c)return xo(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new ao(d,e,a,b);uo[e]=f;kh("player-added",f.api);Ud(f,function(){delete uo[f.getId()]});
return f.api}
function xo(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var yo=null,zo=null,Ao=null;function Bo(){var a=yo.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
;function Co(a,b,c){a="ST-"+ac(a).toString(36);b=b?fc(b):"";c=c||5;ul()&&Lh(a,b,c)}
;function Do(a,b,c){b=void 0===b?{}:b;c=void 0===c?!1:c;var d=F("EVENT_ID");d&&(b.ei||(b.ei=d));if(b){d=a;var e=void 0===e?!0:e;var f=F("VALID_SESSION_TEMPDATA_DOMAINS",[]),g=dc(window.location.href);g&&f.push(g);g=dc(d);if(0<=Wa(f,g)||!g&&0==d.lastIndexOf("/",0))if(O("autoescape_tempdata_url")&&(f=document.createElement("a"),Wb(f,d),d=f.href),d){g=d.match(bc);d=g[5];f=g[6];g=g[7];var h="";d&&(h+=d);f&&(h+="?"+f);g&&(h+="#"+g);d=h;f=d.indexOf("#");if(d=0>f?d:d.substr(0,f))if(e&&!b.csn&&(b.itct||b.ved)&&
(b=Object.assign({csn:Pl()},b)),k){var k=parseInt(k,10);isFinite(k)&&0<k&&Co(d,b,k)}else Co(d,b)}}if(c)return!1;if((window.ytspf||{}).enabled)spf.navigate(a);else{var l=void 0===l?{}:l;var n=void 0===n?"":n;var p=void 0===p?window:p;c=p.location;a=gc(a,l)+n;var q=void 0===q?ed:q;a:{q=void 0===q?ed:q;for(l=0;l<q.length;++l)if(n=q[l],n instanceof cd&&n.isValid(a)){q=new Lc(a,Jc);break a}q=void 0}c.href=Nc(q||Mc)}return!0}
;z("yt.setConfig",N,void 0);z("yt.config.set",N,void 0);z("yt.setMsg",Pf,void 0);z("yt.msgs.set",Pf,void 0);z("yt.logging.errors.log",kl,void 0);
z("writeEmbed",function(){var a=F("PLAYER_CONFIG",void 0);if(!a){var b=F("PLAYER_VARS",void 0);b&&(a={args:b})}Cl(!0);"gvn"===a.args.ps&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=F("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);O("embeds_js_api_set_1p_cookie")&&(c=Bg(),c.embedsTokenValue&&(a.args.embedsTokenValue=c.embedsTokenValue));N("FORCE_CSI_ON_GEL",!0);
c=["ol"];ym("").info.actionType="embed";c&&N("TIMING_AFT_KEYS",c);N("TIMING_ACTION","embed");c=F("TIMING_INFO",{});for(var d in c)c.hasOwnProperty(d)&&Om(d,c[d]);Om("is_nav",1);(d=Pl())&&Om("csn",d);(d=F("PREVIOUS_ACTION",void 0))&&!Jm()&&Om("pa",d);d=tm();c=F("CLIENT_PROTOCOL");var e=F("CLIENT_TRANSPORT");c&&Om("p",c);e&&Om("t",e);Om("yt_vis",Rm());Om("yt_lt","cold");c=pm();if(e=rm())Z("srt",c.responseStart),1!==d.prerender&&(Om("yt_sts","n",void 0),Z("_start",e,void 0));d=wm();0<d&&Z("fpt",d);d=
pm();d.isPerformanceNavigationTiming&&Om("pnt",1,void 0);Z("nreqs",d.requestStart,void 0);Z("nress",d.responseStart,void 0);Z("nrese",d.responseEnd,void 0);0<d.redirectEnd-d.redirectStart&&(Z("nrs",d.redirectStart,void 0),Z("nre",d.redirectEnd,void 0));0<d.domainLookupEnd-d.domainLookupStart&&(Z("ndnss",d.domainLookupStart,void 0),Z("ndnse",d.domainLookupEnd,void 0));0<d.connectEnd-d.connectStart&&(Z("ntcps",d.connectStart,void 0),Z("ntcpe",d.connectEnd,void 0));d.secureConnectionStart>=rm()&&0<d.connectEnd-
d.secureConnectionStart&&(Z("nstcps",d.secureConnectionStart,void 0),Z("ntcpe",d.connectEnd,void 0));W&&W.getEntriesByType&&Tm();d=[];if(document.querySelector&&W&&W.getEntriesByName)for(var f in mm)mm.hasOwnProperty(f)&&(c=mm[f],Sm(f,c)&&d.push(c));for(f=0;f<d.length;f++)Om("rc",d[f]);if(Jm(void 0)){f={actionType:Dm[F("TIMING_ACTION",void 0)]||"LATENCY_ACTION_UNKNOWN",previousAction:Dm[F("PREVIOUS_ACTION",void 0)]||"LATENCY_ACTION_UNKNOWN"};if(d=Pl())f.clientScreenNonce=d;d=um(void 0);c=sm(void 0).cttAuthInfo;
Bm().info(f,d,c)}f=tm();c=om();if("cold"===f.yt_lt&&(d=Lm(),e=d.gelTicks?d.gelTicks:d.gelTicks={},d=d.gelInfos?d.gelInfos:d.gelInfos={},Jm())){for(var g in c)"tick_"+g in e||Km(g,c[g]);g=Nm();c=um();e=sm().cttAuthInfo;var h={},k=!1,l;for(l in f)if(!("info_"+l in d)){var n=Mm(l,f[l]);n&&(am(g,n),am(h,n),k=!0)}k&&Bm().info(h,c,e)}z("ytglobal.timingready_",!0,void 0);Pm();(l=F("WEB_PLAYER_CONTEXT_CONFIGS",void 0))&&"WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER"in l?(l=l.WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER,
l.serializedForcedExperimentIds||(g=Bg(),g.forced_experiments&&(l.serializedForcedExperimentIds=g.forced_experiments)),yo=wo(a,l,!1)):yo=wo(a);yo.addEventListener("onVideoDataChange",Bo);a=F("POST_MESSAGE_ID","player");F("ENABLE_JS_API")?Ao=new Ln(yo):F("ENABLE_POST_API")&&"string"===typeof a&&"string"===typeof b&&(zo=new Sn(window.parent,a,b),Ao=new Pn(yo,zo.connection));pn();O("networkless_logging_web_embedded")&&(O("embeds_web_enable_new_nwl")?Pk():xk());O("embeds_enable_ua_ch_polyfill")&&Dn()},
void 0);
var Eo=Lf(function(){Qm();var a=Nh.getInstance(),b=!!((Qh("f"+(Math.floor(119/31)+1))||0)&67108864),c=1<window.devicePixelRatio;if(document.body&&Xd(document.body,"exp-invert-logo"))if(c&&!Xd(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!Xd(d,"inverted-hdpi")){var e=Vd(d);Wd(d,e+(0<e.length?" inverted-hdpi":"inverted-hdpi"))}}else!c&&Xd(document.body,"inverted-hdpi")&&Yd();if(b!=c){b="f"+(Math.floor(119/31)+1);d=Qh(b)||0;d=c?d|67108864:
d&-67108865;0==d?delete Mh[b]:(c=d.toString(16),Mh[b]=c.toString());c=!0;O("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.h;d=[];for(var f in Mh)d.push(f+"="+encodeURIComponent(String(Mh[f])));Lh(b,d.join("&"),63072E3,a.i,c)}Vm.h||(Vm.h=new Vm);a=Vm.h;f=16623;var g=void 0===g?{}:g;Object.values(ml).includes(f)||(jl(new ji("createClientScreen() called with a non-page VE",f)),f=83769);g.isHistoryNavigation||a.h.push({rootVe:f,key:g.key||""});a.A=[];a.u=[];g.Va?Ym(a,f,g):Zm(a,f,g)}),Fo=Lf(function(){yo&&
yo.sendAbandonmentPing&&yo.sendAbandonmentPing();
F("PL_ATT")&&vn.dispose();for(var a=0,b=nn.length;a<b;a++)lg(nn[a]);nn.length=0;ln("//static.doubleclick.net/instream/ad_status.js");on=!1;N("DCLKSTAT",0);Td(Ao,zo);yo&&(yo.removeEventListener("onVideoDataChange",Bo),yo.destroy())});
window.addEventListener?(window.addEventListener("load",Eo),window.addEventListener("unload",Fo)):window.attachEvent&&(window.attachEvent("onload",Eo),window.attachEvent("onunload",Fo));Ra("yt.abuse.player.botguardInitialized",C("yt.abuse.player.botguardInitialized")||wn);Ra("yt.abuse.player.invokeBotguard",C("yt.abuse.player.invokeBotguard")||xn);Ra("yt.abuse.dclkstatus.checkDclkStatus",C("yt.abuse.dclkstatus.checkDclkStatus")||qn);
Ra("yt.player.exports.navigate",C("yt.player.exports.navigate")||Do);Ra("yt.util.activity.init",C("yt.util.activity.init")||ng);Ra("yt.util.activity.getTimeSinceActive",C("yt.util.activity.getTimeSinceActive")||qg);Ra("yt.util.activity.setTimestamp",C("yt.util.activity.setTimestamp")||og);}).call(this);
