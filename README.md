기초 개념은 렌코차트 트래디셔널로 블록 사이즈를 설정하고 슈퍼트렌드를 사용하여 아래의 백테스트를 진행
렌코차트를 이용한 이유는 가장 간단, 적은량의 정보만을 필요로해서 계산량이 줄고 오히려 더 명확하게 할 수 있을거라 기대함.
수수료 0.05프로를 주고 아래 백테스트를 진행함 기간은 365일
class 목록
BotConfig: 설정값 고정	
ExchangeClient: 거래소 API 받아오기	
	fetch_ohlcv_df: OHLCV를 가져와 Dataframe으로 변환
Portfolio: 내 정보 (진입가 현재가 포지션 정보)	
StrategyState: 전략,신호 플래그/ 슈퍼트랜드 플래그	
RenkoEngine: 렌코차트 생성 및 업데이트	
IndicatorEngine: 인디케이터	
ExecutionService: 포지션 / 잔고 / 주문 실행	
StrategyEngine: 렌코 업데이트 실행함수 / 진입 청산 판단 /웹훅 처리	
WebhookServer: Flask 서버 처리	
SchedulerService: 스케줄러 관리	
BotOrchestrator: 실행은 여기서	





<img width="1402" height="401" alt="image" src="https://github.com/user-attachments/assets/4ec156d6-6498-4a20-aed3-5a03fa2a2f87" /># SuperTrend
Renko, SuperTrend
<img width="1757" height="112" alt="image" src="https://github.com/user-attachments/assets/456ae1c8-e528-49a4-b07d-92e37ecbf73c" />
<img width="1775" height="407" alt="image" src="https://github.com/user-attachments/assets/9b86428b-9704-4881-ab64-f13ec26d7be5" />
<img width="1722" height="368" alt="image" src="https://github.com/user-attachments/assets/d112480b-6d9b-4c17-8b47-6c0e7361a2cf" />
<img width="1402" height="401" alt="image" src="https://github.com/user-attachments/assets/1141065f-0d23-4321-afc0-fedc8b0baae4" />
<img width="1697" height="318" alt="image" src="https://github.com/user-attachments/assets/b6c559a1-21ae-4a24-bb05-e4a4410eaca3" />
<img width="1417" height="395" alt="image" src="https://github.com/user-attachments/assets/db7ef15e-4e9a-4cd9-abd7-34494bbcd13c" />
<img width="1402" height="348" alt="image" src="https://github.com/user-attachments/assets/dca8fd56-23aa-4ead-8945-90c94cd8761a" />
