### IP ( Internet Protocol )  주소 - 호스트에 대한 식별자

#### IPv4: 32비트 주소 체계 ( 대략 43억개 조금 안됨 )
  - ex) 192.168.60.14  : '.' 기준으로 8비트 (0~255) 단위로 나누어져 있음 8비트 * 4 = 32비트
  - 앞 세개는 네트워크 ID ( 길이 24 ), 뒤는 호스트 ID( 길이 32 - 24 = 8 )
  - 192 → 1100 0000(2)

#### IPv6: 128비트 주소 체계 

#### 서브넷 마스크: IP 주소에서 네트워크 ID의 길이를 나타내는 것
  - IP와 서브넷 마스크를 AND 연산 하면 네트워크 ID가 나옴
  - ex) 255.255.255.0


참고자료
```
https://www.youtube.com/watch?v=gOMljj6K2V0&t=29s
```

