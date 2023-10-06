# WorkYogiyo
ios 매장 찜 하기 앱 (요기요 과제)

# Requirements
+ iOS 14.0

# SPM
1.Alamofire <br>
2.RxSwift <br>
3.RxDataSource <br>
4.Snapkit <br>
5.Kingfisher <br>
6.SkeletonView <br>

# Design Pattern
+ MVVM (Entity, Repository, Service, ViewModel, View)
+ UIKit, CodeBased UI

# Source 구조 
+ Extension: extension으로 유틸성 공통 처리
+ LocalData: UserDefault, Singleton 사용
+ Common/Font: cusom font 사용 (default - Pretendard) / Custom Color Palette
+ Network: API 처리 (entity, repository)
+ Logic: 로직처리 (model, service, viewModel)
+ UI: 화면처리 (View)

# 요구사항 외 추가기능
+ Splash: 앱 시작시 splash animation 추가
+ Localization: 영어 / 한국어 지원
+ Font, Color System: 폰트, 컬러 시스템화 정리 사용
+ Skeletion: 리스트 Skeleton 및 pull to refresh 적용
+ Favorite: 찜 리스트에서 찜 삭제 기능 적용
