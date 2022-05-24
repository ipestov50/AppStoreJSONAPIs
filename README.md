# AppStoreJSONAPIs

Аналог AppStore, организованный с помощью UITabBarController включающий в себя три ViewController: 'Today', 'Apps', 'Search' 

В проекте использован MVC + фреймворк 'SDWebImage'

<img width="383" alt="Снимок экрана 2022-05-24 в 14 45 33" src="https://user-images.githubusercontent.com/105271727/170027333-a51a9fd2-f70d-4662-be35-f5943aa3a7a6.png">

<img width="385" alt="Снимок экрана 2022-05-24 в 14 46 59" src="https://user-images.githubusercontent.com/105271727/170027511-f8da023d-2bc8-4d72-91fa-f80e628c4aa3.png">

<img width="378" alt="Снимок экрана 2022-05-24 в 14 47 49" src="https://user-images.githubusercontent.com/105271727/170027656-a7fcd6f0-faf1-4635-b249-c2eb00c524b3.png">

Из основного...

# На экране 'Today' использовано: 

- UIViewController
- UITableView
- Animation
- UIImageView
- UIStackView

# На экране 'Apps' использовано: 

- UIViewController
- UIActivityIndicatorView
- UICollectionViewController
- UIPanGestureRecognizer
- Animation(constraints) 
- DispatchGroup
- Custom Cells 
- UIVisualEffectView
- Networking 

Пример анимации кнопки выполненной по аналогии с AppStore

<img width="386" alt="Снимок экрана 2022-05-24 в 15 12 11" src="https://user-images.githubusercontent.com/105271727/170031848-876ff660-3616-4f46-b315-4ff352e58d43.png">



# На экране 'Search' использовано 

- UISearchController
- UICollectionViewController ( reusable -> BaseListController ) 
- UILabel
- Timer in SearchBar ( таймер позволяет указать интервал времени за который будет отображена ячейка с введенным приложением )

Поиск 

<img width="318" alt="Снимок экрана 2022-05-24 в 15 07 15" src="https://user-images.githubusercontent.com/105271727/170030998-16ed7c7d-8d5f-4704-a6e1-2db42b1d8170.png">

После того как мы перешли на приложение, которое искали в Search Bar 

<img width="312" alt="Снимок экрана 2022-05-24 в 15 10 22" src="https://user-images.githubusercontent.com/105271727/170031502-6c457691-f523-4951-894a-7df55b73421a.png">




