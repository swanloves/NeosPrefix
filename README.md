# MibPrefix

- A plugin of PocketMine-MP that supports prefix (rank) system on your server
- You *must* apply the EconomyAPI made by Onebone
- I wrote how to use this plugin in English, but please forgive me for my bad English ;d
- 칭호 기능을 지원하는 PocketMine-MP의 플러그인입니다
- 원본님의 EconomyAPI 적용을 필수로 합니다


# Command

- /칭호 - Open Prefix System UI

- 칭호 설정 <유저> <칭호> | Set <유저>'s prefix to <칭호>
- 칭호 추가 <유저> <칭호> | Add <칭호> in <유저>'s prefix slot
- 칭호 제거 <유저> <칭호> | Remove <칭호> from <유저>'s prefix slot
- 칭호 목록 <유저> | Check the list of <유저>'s prefix list
- 칭호 한닉 <유저> <닉네임> | Change <유저>'s nickname to <닉네임>
- 칭호 티켓 <칭호> | Make prefix (<칭호>) ticket
- 칭호 상점추가 <가격> <칭호> | Add <칭호> in prefix shop (the price is <가격>)
- 칭호 상점제거 <칭호> | Remove <칭호> from prefix shop


# 명령어

- /칭호 - 칭호 UI를 엽니다

- 칭호 설정 <유저> <칭호> | 유저의 칭호를 설정합니다
- 칭호 추가 <유저> <칭호> | 유저에게 칭호를 추가합니다
- 칭호 제거 <유저> <칭호> | 유저의 칭호를 제거합니다
- 칭호 목록 <유저> | 유저의 칭호 목록을 확인합니다
- 칭호 한닉 <유저> <닉네임> | 유저의 닉네임을 변경합니다
- 칭호 티켓 <칭호> | 칭호 티켓을 생성합니다
- 칭호 상점추가 <가격> <칭호> | 칭호 상점을 추가합니다
- 칭호 상점제거 <칭호> | 칭호상점을 제거합니다


# How to make Sign Prefix Shop

- you can use it where the point of something like contents (like jumpmaps)

- 1st. Place a sign
- 2nd. Type '[칭호상점]' in 1st line.
- 3rd. Type the prefix that you want to make in 2nd line.
- 4th. Type the price that you want to make in 3rd line.

- When you remove the shop, just break the sign
- if you want to buy the prefix from the sign shop, sneak and touch it


# 칭호상점 만드는 방법

- UI 칭호상점에 추가하고 싶지 않은 곳 (이스터에그라던가 컨텐츠 도착 지점에) 에 표지판 상점을 만들 수 있습니다

- 첫번째. 표지판을 설치한다
- 두번째. '[칭호상점]'을 첫째 줄에 적습니다
- 세번째. 칭호와 가격을 각각 2, 3번째 줄에 적습니다

- 부수면 칭호상점에 제거되고 웅크린채로 상점을 터치하면 칭호를 구매하실 수 있습니다


# Changelog [Before Version : Master - Beta 1]

- Now, I made it more tidy ;d
- NEW functions: ['/칭호 제거', SignPrefixShop]


# 체인지로그 [지난 버전 : Master - Beta 1 ]

- 우선 지금까지 많은 서버에서 이 플러그인을 사용해주셔서 감사합니다 ;d 앞으로 업데이트를 통해 더 많은 기능을 구현하겠습니다
- 여러분이 그렇게 원하시던 (?) /칭호 제거 기능이 추가되었습니다
- 다시 보니까 소스가 엮겨워서 거의 처음부터 다시 만들었습니다
- 한 db 파일에 묵었었는데, 콘피그를 분할했습니다 (?
- 표지판 상점 기능이 추가되었습니다 ><
- 앞으로도 많은 관심 부탁드립니다