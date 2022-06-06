<h1> Sofya Chernyaeva CV <h1>

![foto](https://github.com/Aute0/rsschool-cv/blob/gh-pages/foto.jpg)

<div id="Position">
<h2> Position: <h2>
<h3> Leading geophysicist in AARII <h3>
<hr>
<div id="Contacts">
<h3> Contacts:

    Phone: 8(951)688-53-13
    Email: sonya.a.chernyaeva@ya.ru
    Telegram: @sonya21che
    discord: Sofya Chernyaeva (Aute0)
<hr>
<div id="About Myself">
  <h3> About Myself: 
<h4>
Completed my postgraduate studies at St. Petersburg State University with a degree in Physics of Solar-Earth Relations. Engaged in scientific activities. Full cycle of satellite data preparation: search, download, cleaning, sorting and analysis. Has written several scientific articles in leading plasma physics journals. Mother of two litlle children. I am currently pursuing a degree in System and Business Analyst.
<hr>
<div id="Skills">
<h3> Skills: <h3>

Completed             | Now         | Future 
---------|--------------------------|--------
 Exel pro             | MySQL       |API
 Grapher              | Python      |NumpP,SciPy, Pandas, Matplotlib 
 Git, GitHub          | JS          |UML, SOAP, REST API, XML, XHTML
 Adobe Publisher      | PowerBI     | HTTP,TLS, Websockets, Firebase, HTTP/2, gRPC
 BPMN, IDEF           | DAX         |Kafka, rabbit MQ, ESB (Enterprise Service Bus)
 Waterfall, Scrum,etc |MongoDB, etc |Basic auth, API key, OAuth, OAuth flows, JWT, JWS, SSO, OpenId, SAML, Social login
 <hr>
 <div id="Code example">
 <h3> Code example: (student)

 ```matlab
 x=zeros(m,length(rx));
y=zeros(m,length(ry));
x(1,:)=0.75;
y(1,:)=0.75;

for n=1:(m-1)
    x(n+1,:)=rx.*x(n,:).*(1-x(n,:));
    y(n+1,:)=ry.*y(n,:).*(1-y(n,:));
end
for t=1:length(rx)
    p=corrcoef(x(:,t),y(:,t));
    k(t)=abs(p(2));    
end
subplot(2,1,1),plot(rx,k)
subplot(2,1,2),plot(rx,x(end-200:end,:),'b.','markersize',2) 
```
<hr>
<div id="Languages">
<h3> Languages:
    
    1. English - Advanced (b2)
  ![Eng](https://github.com/Aute0/rsschool-cv/blob/gh-pages/Eng.png) 

    2. Deutsch - Basic
    3. Russian - Native
<hr>
