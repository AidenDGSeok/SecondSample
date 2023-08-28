# Work29CM
ios 깃헙 리퍼지토리 관리 앱 (29CM 과제)

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
