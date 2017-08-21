# suricata_rule  
  
현재까지의 진행 상황: HTTPS에 대한 검증을 하지 않았으나 대다수가 작동하지 않는 것 같음.  HTTP에 대해서는 검증을 끝낸 상태.  전체적인 수정만 남음.   
  
PS.  모든 사이트들의 링크에 약간 수정을 가했습니다.    
  
hxxp://hitomi. la/ : 자동으로 hxxps 연결을 사용하도록 리디렉션.  불가능.   
hxxp://kass. org. kp/ : 성공  
hxxp://kcna. kp/ : 성공  
hxxp://kitribob. wiki/wiki/ : 성공  
hxxp://ks8282. com/ : 성공  
hxxp://linoit. com/users/men1212/canvases/19%EA%B8%88%20 : 성공  
hxxp://naevr. com/ : 성공  
hxxp://named. com/game/ladder/v2_index. php : 성공  
hxxp://naver6. com/ : 성공  
hxxp://onaratv. com/ : 실패.  서버를 찾을 수 없음.   
hxxp://pornpros. com/ : 성공  
hxxp://rodong. rep. kr/ : 성공  
hxxp://snoopspy. com/download/ : 성공  
hxxp://test. gilgli. net/streaming/test. mp4 : 일단은 성공.  스트리밍 잡아야  
hxxp://uriminzokkiri. com/ : 성공  
hxxp://www. 4shared. com/ : 성공  
hxxp://www. bamwar25. com/ : 성공  
hxxp://www. faa25. com/ : 성공  
hxxp://www. ilbe. com/ilbe : 실패.  확인 요  
hxxp://www. kimmadam. net/ : 성공  
hxxp://www. minjok. com/ : 성공  
hxxp://www. narutoxxx. com/ : 성공  
hxxp://www. naver. cm/ : 성공  
hxxp://www. ryomyong. com/ : 성공  
hxxp://www. sedisk. com/ : 성공  
hxxp://www. sk386. com/ : 성공  
hxxp://www. tcosc. net/ : 성공  
hxxp://www. torenzoa. net/ : 성공  
hxxp://www. umj262. com/ : 성공  
hxxp://www. winclub88. net/my/4D. html : 실패.  확인 요  
hxxps://graphgame. net/ : 실패.  
hxxps://mujige53770. wixsite. com/ : 실패.   
hxxps://sex. com/ : 성공  
hxxps://torrenthaja. com/ : 실패.  
hxxps://torrentkim10. net/ : 실패.  
hxxps://webtoon. bamtoki. com/ : 실패.  
hxxps://www. facebook. com/profile. php?id=100019007882633 : 불가능.  서브디렉토리 존재.   
hxxps://www. mtbucks. com/ : 실패.  
hxxps://www. opioids. com/offshorepharmacy/index. html : 불가능.  서브디렉토리 존재.   
hxxps://www. phishtank. com/ : 실패.  
hxxps://yobit. net/en/dice: 불가능.  서브디렉토리 존재.   
  
왜 HTTP의 일부 subdirectory는 필터링이 불가능한지 의문이 들었음. 또한, 규칙이 대다수의 HTTPS 연결을 감지하지 못하여 wireshark로 패킷을 캡쳐해보았는데, TLS 패킷을 보내지 않는 경우가 거의 대다수였음. 왜 이런 차이가 났던 것이며, 이 경우들까지 감지할 수 있는 방법은 있는지 궁금함.

Opt.  Search Keyword: suricata tls  
