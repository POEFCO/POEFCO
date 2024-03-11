

<!DOCTYPE html>
<html ng-app="defaultModule" lang='en' dir='ltr'>
<head><title>

</title>
<meta name='servername' content='WEBSERVER11' />
<meta http-equiv="X-UA-Compatible" content="IE=edge" /><meta name="viewport" content="width=device-width, initial-scale=1" />

    <link rel="stylesheet" href="https://cdn.k12net.net/CDN/html5/cardslider/css/cardslider.css?v=1.2.19">

    

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.1.1/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdn.k12net.net/CDN/html5/assets/css/spts.css?v=4.20.21">
    <link rel="stylesheet" href="https://cdn.k12net.net/CDN/html5/assets/css/themes/orange.css?v=1.2.19">

    

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/plyr/3.7.2/plyr.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/jqueryui/1.12.1/jquery-ui.min.css">

    <link rel="stylesheet" href="https://cdn.k12net.net/CDN/html5/google/css/oswald-roboto.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">

    

    <script src='/ControlLibraryJS/js/k12net.min.js?v=2024-02-13T09:04:40' type="text/javascript"></script>

    

    <script src='js/server-variables.aspx?v=2020-03-04T12:50:02' type="text/javascript"></script>
    
    <script src='/SPCore.Web/api/Settings/Global' type="text/javascript"></script>
    

    <script src='https://cdnjs.cloudflare.com/ajax/libs/jquery/1.11.2/jquery.min.js' type="text/javascript"></script>
    <script src='https://cdnjs.cloudflare.com/ajax/libs/jqueryui/1.11.4/jquery-ui.min.js' type="text/javascript"></script>
    <script src='https://cdnjs.cloudflare.com/ajax/libs/jqueryui/1.9.2/i18n/jquery-ui-i18n.min.js' type="text/javascript"></script>

    <script src='https://cdnjs.cloudflare.com/ajax/libs/angular.js/1.4.3/angular.min.js' type="text/javascript"></script>
    <script src='https://cdnjs.cloudflare.com/ajax/libs/angular.js/1.4.3/angular-route.min.js' type="text/javascript"></script>
    <script src='https://cdnjs.cloudflare.com/ajax/libs/angular-i18n/1.5.0/angular-locale_en.min.js' type="text/javascript"></script>
    <script src='https://cdnjs.cloudflare.com/ajax/libs/angular-messages/1.4.3/angular-messages.min.js' type="text/javascript"></script>


    

    <script src='js/k12net-sp.min.js?v=2024-03-06T15:26:27' type="text/javascript"></script>

    

    <script src='https://cdn.k12net.net/CDN/html5/angular-ui-bootstrap/3.0.5/ui-bootstrap-tpls.min.js' type="text/javascript"></script>
    <script src='https://cdnjs.cloudflare.com/ajax/libs/angular-ui-mask/1.8.7/mask.min.js' type="text/javascript"></script>

    <script src='https://cdnjs.cloudflare.com/ajax/libs/textAngular/1.5.16/textAngular-rangy.min.js' type="text/javascript"></script>
    <script src='https://cdnjs.cloudflare.com/ajax/libs/textAngular/1.5.16/textAngular-sanitize.min.js' type="text/javascript"></script>
    <script src='https://cdnjs.cloudflare.com/ajax/libs/textAngular/1.5.16/textAngular.min.js' type="text/javascript"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/textAngular/1.5.16/textAngular.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.0/css/all.min.css">

    
    <link href="https://cdnjs.cloudflare.com/ajax/libs/lightgallery/1.6.12/css/lightgallery.min.css" rel="stylesheet" type="text/css">
    <script src='https://cdnjs.cloudflare.com/ajax/libs/lightgallery/1.6.12/js/lightgallery-all.min.js' type="text/javascript"></script>
    <script src='https://cdnjs.cloudflare.com/ajax/libs/jquery-mousewheel/3.1.13/jquery.mousewheel.min.js' type="text/javascript"></script>

    

    <script src='/SPTS.Web/WebParts/Default/Controllers/default.js?v=2022-08-01T11:00:04' type="text/javascript"></script>
    <script src='/SPTS.Web/WebParts/Default/Controllers/menuController.js?v=2024-03-06T10:33:06' type="text/javascript"></script>
    <script src='/SPTS.Web/WebParts/Default/Controllers/notifications.js?v=2023-11-13T09:37:27' type="text/javascript"></script>
    <script src='/EPJS.Web/WebParts/Header/Controllers/notification-setting.js?v=2022-08-16T17:02:23' type="text/javascript"></script>
    <script src='/SPTS.Web/WebParts/Default/Controllers/list-calendar.js?v=2023-11-13T09:37:27' type="text/javascript"></script>
    <script src='/SPTS.Web/WebParts/Default/Controllers/impending-test.js?v=2021-04-06T17:45:18' type="text/javascript"></script>
    <script src='/ControlLibraryJS/js/atlas.html-controls.js?v=2024-01-02T08:23:09' type="text/javascript"></script>
    <script src='/ControlLibraryJS/js/resource-viewer.js?v=2023-03-20T17:00:04' type="text/javascript"></script>
    <script src='https://cdnjs.cloudflare.com/ajax/libs/html5-qrcode/2.1.6/html5-qrcode.min.js' type="text/javascript"></script>
    <script src='/ControlLibraryJS/js/qr-login.js?v=2022-01-26T20:43:15' type="text/javascript"></script>

    <script src='https://cdn.k12net.net/CDN/html5/google/js/charts/loader.js' type="text/javascript"></script>
    <script type="text/javascript">
        var DashboardChartManager = { IsLoaded: false, Queue: [] };

        google.charts.load('current', {
            callback: function () {
                DashboardChartManager.IsLoaded = true;
                DashboardChartManager.Queue.forEach(function (method) { method(); });

            }, packages: ['gauge', 'corechart', 'controls']
        });
    </script>

    

    <script src='/SPTS.Web/WebParts/Default/Controllers/dashboard.min.js?v=2024-03-11T16:18:35' type="text/javascript"></script>

    

    <script src='https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.1.1/js/bootstrap.bundle.min.js' type="text/javascript"></script>
    <script src='https://cdn.k12net.net/CDN/html5/cardslider/js/jquery.cardslider.min.js' type="text/javascript"></script>
    <script src='https://cdn.k12net.net/CDN/html5/assets/js/vendor/swiper.min.js' type="text/javascript"></script>
    <script src='https://cdnjs.cloudflare.com/ajax/libs/plyr/3.7.2/plyr.polyfilled.min.js' type="text/javascript"></script>

    <script src='/ControlLibraryJS/js/module-loader.js?v=2020-04-25T07:55:16' type="text/javascript"></script>
    <script src='https://cdn.k12net.net/CDN/html5/assets/js/site/main.js' type="text/javascript"></script>

</head>
<body>
    <script src='/ControlLibraryJS/js/common-directives.js?v=2024-01-02T08:22:20' type="text/javascript"></script>


    <div style="position: fixed; top: 0px; left: 0px; z-index: 100">
        <span class="device-xs d-block d-sm-none">&nbsp;</span>
        <span class="device-sm d-none d-sm-block d-md-none">&nbsp;</span>
        <span class="device-md d-none d-md-block d-lg-none">&nbsp;</span>
        <span class="device-lg d-none d-lg-block d-xl-none">&nbsp;</span>
        <span class="device-xl d-none d-xl-block">&nbsp;</span>
    </div>

    

    <loading ng-controller="topMenuController" ng-show="ViewModel.IsLoading"></loading>

    <div ng-controller="redirectionController">

        <div class="container" style="width: 50%;">
            <h3 ng-if="ViewModel.WebParts && !ViewModel.WebParts.length" ng-bind="ViewModel.Resources.NotAuthorizedStudent"></h3>
        </div>

        <list-notification view-model="ViewModel.NotificationViewModel"></list-notification>

        <force-polls></force-polls>
        <impending-test view-model="ViewModel.ImpendingTestViewModel"></impending-test>
        <list-calendar view-model="ViewModel.CalendarViewModel"></list-calendar>
        <qr-login view-model="ViewModel.QRLoginViewModel"></qr-login>
    </div>

    <!--desktop-->

    <div class="flex-column justify-content-between d-none d-md-flex" style="height: 100%">
        <header class="d-flex flex-row" ng-controller="topMenuController">

            <div style="position: fixed; top: 0px; left: 0px; z-index: 100">
                <span class="d-block d-sm-none"><span ng-if="ViewModel.GlobalSettings.debuggerIsAttached">XS</span></span>
                <span class="d-none d-sm-block d-md-none"><span ng-if=" ViewModel.GlobalSettings.debuggerIsAttached">SM</span></span>
                <span class="d-none d-md-block d-lg-none"><span ng-if="ViewModel.GlobalSettings.debuggerIsAttached">MD</span></span>
                <span class="d-none d-lg-block d-xl-none"><span ng-if="ViewModel.GlobalSettings.debuggerIsAttached">LG</span></span>
                <span class="d-none d-xl-block"><span ng-if="ViewModel.GlobalSettings.debuggerIsAttached">XL</span></span>
            </div>

            <div class="desktop-logo col-3">
                <div class="d-flex flex-row justify-content-around">
                    <button class="circle-icon js-dashboard-asideMenu mr-2 align-self-center d-block d-xl-none">
                        <i class="fas fa-bars"></i>
                    </button>
                    <span class="pt-1">
                        <img id="PartnerLogo" class="img-fluid" style="max-height: 60px" ng-src='{{ViewModel.StudentSchoolEnrollment.SchoolInfo.LocationInfo.LogoPath}}partner_logo.jpg' alt="">
                    </span>
                </div>
            </div>

            <div class="container-fluid pl-0">
                <div class="d-flex flex-row justify-content-end justify-content-md-between mt-1">
                    <div class="d-flex flex-row">
                        <button class="circle-icon js-dashboard-enrollment-info align-self-center d-block d-xl-none mx-3">
                            <img ng-src="{{ViewModel.GlobalSettings.pictureServerUrl + '/GetImage.aspx?Height=48&Width=48&mode=Fill&path=' + (ViewModel.StudentSchoolEnrollment.StudentPersonal.StudentPictures[0] ? ViewModel.StudentSchoolEnrollment.StudentPersonal.StudentPictures[0].Picture.Source : '/Pictures/NoPicture.png')}}" alt="">
                        </button>
                        <div class="dashboard-top-enrollment-info d-block d-xl-none d-flex flex-column" ng-if="ViewModel.StudentSchoolEnrollment">
                            <div>
                                <span class="name" ng-bind="ViewModel.StudentSchoolEnrollment.StudentPersonal.Base.Name.FullName" ng-style="{'font-size':ViewModel.StudentSchoolEnrollment.StudentPersonal.Base.Name.FullName.split(' ').length>3?'12px':'16px'}"></span>
                                <span ng-bind="ViewModel.StudentSchoolEnrollment.HomeroomInfo.Number"></span>
                            </div>
                            <div class="btn-group" id="enrollmentChoser2">
                                <button ng-disabled="ViewModel.IsBusy" class="btn btn-light btn-sm dropdown-toggle" type="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                    <span ng-bind="ViewModel.StudentSchoolEnrollment.SchoolYear.Description"></span>
                                </button>
                                <div class="dropdown-menu">
                                    <a class="dropdown-item" ng-class="ViewModel.IsBusy ? 'disabled' : enrollment == ViewModel.StudentSchoolEnrollment ? 'active': ''" ng-repeat="enrollment in ViewModel.StudentSchoolEnrollments"
                                        ng-click="ViewModel.ChangeEnrollment(enrollment)" href>
                                        <span ng-bind="enrollment.SchoolYear.Description"></span>
                                    </a>
                                </div>
                            </div>
                        </div>
                        <ul class="nav mt-3 d-none d-md-flex">
                            <li class="nav-item desktop-nav-left-item" ng-repeat="menuItem in ViewModel.TopMenuItems">
                                <a class="nav-link pr-1" href ng-click="menuItem.navigate()">
                                    <div class="d-flex">
                                        <i ng-class="menuItem.Icon" class="mr-1 fa-lg" ng-if="menuItem.Icon"></i>
                                        <span id="TopMenuItemName" ng-bind="menuItem.Title" class="d-none d-lg-block" style="line-height: 125%"></span>
                                    </div>
                                </a>
                            </li>
                        </ul>
                    </div>
                    <ul class="nav mt-3">
                        <li class="nav-item desktop-nav-right-item d-none d-sm-flex" ng-repeat="menuItem in ViewModel.TopRightMenuItems" ng-if="['WebParts/Message','WebParts/Calendar'].indexOf(menuItem.Path) < 0">
                            <a class="nav-link px-1" href ng-click="menuItem.navigate()">
                                <div class="d-flex">
                                    <span ng-class="menuItem.Icon" class="badged-menu-item mr-2 fa-lg" ng-if="menuItem.Icon">
                                        <span class="count" ng-show="menuItem.hasBadge()" ng-bind="menuItem.BadgeCount"></span>
                                    </span>
                                    <span id="RightSideTopMenuItemName" ng-bind="menuItem.Title" class="d-none d-xl-block mr-1" style="line-height: 125%"></span>
                                </div>
                            </a>
                        </li>

                        <li class="nav-item mr-1">
                            <div class="btn-group dropleft">
                                <button id="BtnSettings" type="button" class="settings-button dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                    <i class="fas fa-cogs fa-lg"></i>
                                </button>
                                <div class="dropdown-menu">
                                    <a href class="dropdown-item" ng-click="menuItem.navigate()" ng-repeat="menuItem in ViewModel.SettingsMenuItems">
                                        <div class="d-flex">
                                            <i ng-class="menuItem.Icon" class=" fa-lg mr-2" ng-if="menuItem.Icon"></i>
                                            <span id="BtnSettingsItem" ng-bind="menuItem.Title" style="line-height: 125%"></span>
                                        </div>
                                    </a>
                                    <div class="dropdown-divider" ng-if="ViewModel.StudentSchoolEnrollment.MembershipTypeID == '3f300086-7c19-dd11-88a1-0019d1638957'"></div>
                                    <a href class="dropdown-item" ng-click="ViewModel.ExitFromSchool()" ng-if="ViewModel.StudentSchoolEnrollment.MembershipTypeID == '3f300086-7c19-dd11-88a1-0019d1638957'">
                                        <div class="d-flex">
                                            <i class="fas fa-times fa-lg mr-2 text-danger"></i>
                                            <span ng-bind="ViewModel.Resources.ExitFromSchool" style="line-height: 125%"></span>
                                        </div>
                                    </a>
                                </div>
                            </div>
                        </li>

                        <li class="nav-item grow mr-1">
                            <button id="BtnHelp" class="help-button" ng-if="ViewModel.CanRedirectToHelpUrl()" ng-click="ViewModel.Navigate('Help', true)">
                                <i class="fas fa-question-circle fa-lg"></i>
                            </button>
                        </li>

                        <li class="nav-item grow">
                            <button class="logout-button" ng-click="ViewModel.Navigate('/Logout.aspx')">
                                <i class="fas fa-power-off fa-lg"></i>
                            </button>
                        </li>

                    </ul>
                </div>
            </div>
        </header>

        <main>
            <div class="d-flex flex-row" style="height: 100%">
                <aside class="dashboard-leftsection pt-3 col-3" style="overflow: hidden" ng-controller="topMenuController">
                    <a class="text-center" href="{{'WebParts/Student/#/link'.toUriWithSearchPath()}}" ng-if="!ViewModel.HasMultipleStudents && ViewModel.CanLinkStudent">
                        <h6 ng-bind="ViewModel.Resources.LinkExistingStudent"></h6>
                    </a>
                    <div class="student mb-1 p-1" ng-if="ViewModel.IsParent" style="border: solid orangered">
                        <div class="d-flex flex-column align-items-center">
                            <span ng-bind="ViewModel.User.Name" style="text-align: center;"></span>
                        </div>
                    </div>
                    <div class="student">
                        <div class="settings" ng-if="ViewModel.HasMultipleStudents">
                            <a href="{{'WebParts/Student/'.toUriWithSearchPath()}}"><i class="fas fa-exchange-alt"></i></a>
                        </div>
                        <div class="photo-wp" ng-if="ViewModel.StudentSchoolEnrollment">
                            <div class="photo">
                                <img ng-src="{{ViewModel.GlobalSettings.pictureServerUrl + '/GetImage.aspx?Height=128&Width=128&mode=Fill&path=' + (ViewModel.StudentSchoolEnrollment.StudentPersonal.StudentPictures[0] ? ViewModel.StudentSchoolEnrollment.StudentPersonal.StudentPictures[0].Picture.Source : '/Pictures/NoPicture.png')}}" alt="">
                            </div>
                        </div>
                        <div class="student-notification student-action-round white">
                            <a href class="btn btn-sm icon" ng-click="ViewModel.NotificationViewModel.Load();ViewModel.NotificationViewModel.ShowListNotification()" ng-class="{shake: ViewModel.NotificationViewModel.ItemCount > 0}">
                                <i class="fa fa-bell badged-menu-item mr-2"><span class="count" ng-bind="ViewModel.NotificationViewModel.ItemCount"></span></i>
                            </a>
                        </div>
                        <div class="info" ng-if="ViewModel.StudentSchoolEnrollment">
                            <div class="id" ng-bind="ViewModel.StudentSchoolEnrollment.LocalId"></div>
                            <div class="name" ng-bind="ViewModel.StudentSchoolEnrollment.StudentPersonal.Base.Name.FullName" ng-style="{'font-size':ViewModel.StudentSchoolEnrollment.StudentPersonal.Base.Name.FullName.split(' ').length>3?'12px':'16px'}"></div>
                            <div class="btn-group" id="enrollmentChoser1">
                                <button ng-disabled="ViewModel.IsBusy" class="btn btn-light btn-sm dropdown-toggle" type="button" style="font-size: 12px;" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                    <span ng-bind="ViewModel.StudentSchoolEnrollment.SchoolYear.Description"></span>
                                    <span ng-bind="ViewModel.StudentSchoolEnrollment.HomeroomInfo.Number"></span>
                                </button>
                                <div class="dropdown-menu">
                                    <a style="font-size: small" class="dropdown-item p-1" ng-class="ViewModel.IsBusy ? 'disabled' : enrollment == ViewModel.StudentSchoolEnrollment ? 'active': ''" ng-repeat="enrollment in ViewModel.StudentSchoolEnrollments"
                                        ng-click="ViewModel.ChangeEnrollment(enrollment)" href>
                                        <span ng-bind="enrollment.SchoolYear.Description"></span>
                                        <span ng-bind="enrollment.HomeroomInfo.Number"></span>
                                    </a>
                                </div>
                            </div>
                            <div ng-if="ViewModel.Houses.length">
                                <img ng-repeat="entityDocument in ViewModel.Houses[0].StudentActivityInfo.EntityDocuments" ng-if="entityDocument.Document.IsDeleted==false" ng-src="{{ViewModel.GetDocumentPath(entityDocument.Document)}}" alt="..." style="max-height: 50px;" />
                                <div>
                                    <span ng-bind="ViewModel.Houses[0].StudentActivityInfo.StudentActivityType.Code.Description"></span>:
                                    <span ng-repeat="house in ViewModel.Houses">
                                        <b ng-bind="house.StudentActivityInfo.Title" title="{{house.StudentActivityInfo.Description}}"></b>
                                        <span ng-if="!$last" ng-bind="' | '"></span>
                                    </span>
                                </div>
                            </div>                            
                            <div ng-if="ViewModel.IsAllowed('AllowWalletBalanceIcon')">
                                <a ng-if="ViewModel.User['$$$WalletBalance'] != null && ViewModel.User['$$$WalletBalance'] !== '' && ViewModel.User['$$$WalletBalance'] !== '0' && ViewModel.User['$$$WalletBalance'] !== '0,00' && ViewModel.User['$$$WalletBalance'] !== '0.00'" href="{{ViewModel.OnlineStoreLink}}" target="_blank" style="font-size:small" class="btn btn-success mt-2">
                                    <span ng-bind="ViewModel.Resources.CurrentBalance"></span>
                                    <span class="badge badge-light mx-1">
                                        <span ng-bind="ViewModel.User['$$$WalletBalance']"></span>
                                        <i class="{{ViewModel.User['$$$WalletCurrencyIcon']}}" ng-bind="ViewModel.User['$$$WalletCurrencyIcon'].indexOf('fas ') >= 0 ? '' : ViewModel.User['$$$WalletCurrencyIcon']"></i>
                                    </span>
                                </a>
                            </div>
                        </div>
                    </div>
                    <div class="teacher-info">
                        <div class="advisor teacher" ng-if="ViewModel.StudentSchoolEnrollment.Advisor && ViewModel.IsAllowed('AllowToViewAdvisingTeachersEntryID')">
                            <b ng-bind="ViewModel.Resources['StudentSchoolEnrollment.Advisor']"></b>
                            <span ng-bind="ViewModel.StudentSchoolEnrollment.Advisor.Base.Name.FullName"></span>
                        </div>
                        <div class="guide teacher" ng-if="ViewModel.StudentSchoolEnrollment.Counselor && ViewModel.IsAllowed('AllowToViewAdvisingTeachersEntryID')">
                            <b ng-bind="ViewModel.Resources['StudentSchoolEnrollment.Counselor']"></b>
                            <span ng-bind="ViewModel.StudentSchoolEnrollment.Counselor.Base.Name.FullName"></span>
                        </div>
                        <div class="homeroom teacher" ng-if="ViewModel.StudentSchoolEnrollment.HomeroomInfo.HomeroomTeacher && ViewModel.IsAllowed('AllowToViewAdvisingTeachersEntryID')">
                            <b ng-bind="ViewModel.Resources['HomeroomInfo.HomeroomTeacher']"></b>
                            <span ng-bind="ViewModel.StudentSchoolEnrollment.HomeroomInfo.HomeroomTeacher.Base.Name.FullName"></span>
                        </div>
                    </div>

                    <div class="announcement" ng-if="ViewModel.NotificationViewModel.HasAnyAnnouncement">
                        
                        <div class="cardslider">
                            <ul>
                                <li ng-repeat="announcement in ViewModel.NotificationViewModel.AnnouncementViewModel.Announcements">
                                    <div class="wrapper">
                                        <div class="title" ng-bind="announcement.Subject"></div>
                                        <div class="content" ng-bind="ViewModel.NotificationViewModel.AnnouncementViewModel.GetBodyShortText(announcement)"></div>

                                        <div class="controller count" ng-bind="'{0}/{1}'.format($index+1, ViewModel.NotificationViewModel.AnnouncementViewModel.Announcements.length)"></div>
                                        
                                        <a ng-if="ViewModel.NotificationViewModel.AnnouncementViewModel.Announcements.length > 1" class="controller next" href ng-click="ViewModel.NotificationViewModel.AnnouncementViewModel.NextAnnouncement(1)">
                                            <i class="fas fa-arrow-right"></i>
                                        </a>
                                        <a ng-if="ViewModel.NotificationViewModel.AnnouncementViewModel.Announcements.length > 1" class="controller prev" href ng-click="ViewModel.NotificationViewModel.AnnouncementViewModel.NextAnnouncement(-1)">
                                            <i class="fas fa-arrow-left"></i>
                                        </a>
                                    </div>
                                </li>
                            </ul>
                        </div>
                    </div>


                    <div class="school">
                        <span class="close-icon">
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="4387.812 701.312 38.27 38.27">
                                <defs>
                                    <style>
                                        .cls-1 {
                                            opacity: 0.976;
                                        }

                                        .cls-2 {
                                            fill: #f49d56;
                                        }
                                    </style>
                                </defs>
                                <g id="çarpı" class="cls-1" transform="translate(4020 628)">
                                    <rect id="Rectangle_3" data-name="Rectangle 3" class="cls-2" width="12.117" height="42.005" transform="translate(397.514 73.312) rotate(45)" />
                                    <rect id="Rectangle_4" data-name="Rectangle 4" class="cls-2" width="12.117" height="42.005" transform="translate(367.812 81.88) rotate(-45)" />
                                </g>
                            </svg>
                        </span>
                        <span ng-bind="ViewModel.StudentSchoolEnrollment.SchoolInfo.LocationInfo.Name"></span>
                    </div>
                    <div class="bg">
                        <div class="asideBackground js-asideBackground"></div>
                    </div>
                </aside>
                <div class="container-fluid">
                    <section class="dashboard-mainsection d-flex flex-column justify-content-between" style="height: 100%">
                        <div class="row flex-fill" ng-controller="dashboardController">
                            <div class="col-3">
                                <div class="mainsection-wrapper left d-flex align-content-stretch flex-wrap">
                                    <div class="box my-1" ng-repeat="dashboardItem in ViewModel.DashboardItemsLeft" ng-attr-data-id="{{dashboardItem.TagName}}" ng-class="dashboardItem.TagName" ng-click="ViewModel.NavigateTo(dashboardItem)">
                                        <div class="box-hack">
                                            <div class="title badged-menu-item">
                                                <span id="LeftMenuItemText" ng-bind="dashboardItem.MenuItem.Title"></span>
                                                <div class="info count" style="font-size: 12px;" ng-show="dashboardItem.MenuItem.hasBadge()" ng-bind="dashboardItem.MenuItem.BadgeCount"></div>
                                            </div>
                                            <div id="LeftMenuItemName" class="icon" ng-if="dashboardItem.MenuItem.Icon">
                                                <i ng-class="dashboardItem.MenuItem.Icon"></i>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="col-6 p-0">
                                <div class="mainsection-centerwrapper py-1">
                                    <div class="main-box" id="mainBox" infinitescroll>
                                    </div>
                                </div>
                            </div>
                            <div class="col-3">
                                <div class="mainsection-wrapper right d-flex align-content-stretch flex-wrap">
                                    <div class="box my-1" ng-repeat="dashboardItem in ViewModel.DashboardItemsRight" ng-attr-data-id="{{dashboardItem.TagName}}" ng-class="dashboardItem.TagName" ng-click="ViewModel.NavigateTo(dashboardItem)">
                                        <div class="box-hack">
                                            <div class="title badged-menu-item">
                                                <span id="RightMenuItemText" ng-bind="dashboardItem.MenuItem.Title"></span>
                                                <div class="info count" style="font-size: 12px;" ng-show="dashboardItem.MenuItem.hasBadge()" ng-bind="dashboardItem.MenuItem.BadgeCount"></div>
                                            </div>
                                            <div id="RightMenuItemName" class="icon" ng-if="dashboardItem.MenuItem.Icon">
                                                <i ng-class="dashboardItem.MenuItem.Icon"></i>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <ul class="footer-menu mt-1 p-0" ng-controller="bottomMenuController">
                            <li class="grow" ng-repeat="menuItem in ViewModel.BottomMenuItems">
                                <a href ng-click="menuItem.navigate()">
                                    <div class="footer-menu-wrapper">
                                        <div id="FooterMenuItem" class="icon" ng-if="menuItem.Icon || menuItem.ImagePath">
                                            <i ng-class="menuItem.Icon" ng-if="!menuItem.ImagePath"></i>
                                            <img ng-src="{{menuItem.ImagePath}}" ng-if="menuItem.ImagePath" style="height: inherit; margin-top: -8px;" />
                                        </div>
                                        <span class="d-none d-md-block" ng-bind="menuItem.Title"></span>
                                    </div>
                                </a>
                            </li>
                        </ul>
                    </section>
                </div>
            </div>
        </main>
    </div>

    <!--end of desktop-->
    <!--mobile-->
    <div class="flex-column justify-content-between d-flex d-md-none" style="height: 100%">
        <header class="m-header" ng-controller="xsMenuController">

            <div style="position: fixed; top: 0px; left: 0px; z-index: 100">
                <span class="d-block d-sm-none"><span ng-if="ViewModel.GlobalSettings.debuggerIsAttached">XS</span></span>
                <span class="d-none d-sm-block d-md-none"><span ng-if="ViewModel.GlobalSettings.debuggerIsAttached">SM</span></span>
                <span class="d-none d-md-block d-lg-none"><span ng-if="ViewModel.GlobalSettings.debuggerIsAttached">MD</span></span>
                <span class="d-none d-lg-block d-xl-none"><span ng-if="ViewModel.GlobalSettings.debuggerIsAttached">LG</span></span>
                <span class="d-none d-xl-block"><span ng-if="ViewModel.GlobalSettings.debuggerIsAttached">XL</span></span>
            </div>

            <div class="container">
                <div class="row">
                    <div class="col-3">
                        <button class="m-header-icon icon-menu" ng-click="ViewModel.Navigate(''.toUriWithSearchPath())">
                            <div class="photo" ng-if="ViewModel.StudentSchoolEnrollment">
                                <img ng-src="{{ViewModel.GlobalSettings.pictureServerUrl + '/GetImage.aspx?Height=48&Width=48&mode=Fill&path=' + (ViewModel.StudentSchoolEnrollment.StudentPersonal.StudentPictures[0] ? ViewModel.StudentSchoolEnrollment.StudentPersonal.StudentPictures[0].Picture.Source : '/Pictures/NoPicture.png')}}" alt="">
                            </div>
                        </button>
                    </div>
                    <div class="col-6">
                        <span class="text-white" ng-bind="ViewModel.User.Name" style="font-size: 12px; position: fixed; left: 10px" ng-if="ViewModel.IsParent && !ViewModel.IsRTL"></span>
                        <span class="text-white" ng-bind="ViewModel.User.Name" style="font-size: 12px; position: fixed; right: 10px" ng-if="ViewModel.IsParent && ViewModel.IsRTL"></span>
                        <div class="logo">
                            <a ng-href="{{''.toUriWithSearchPath()}}">
                                <img ng-src='{{ViewModel.StudentSchoolEnrollment.SchoolInfo.LocationInfo.LogoPath}}partner_logo.jpg' alt="">
                            </a>
                        </div>
                    </div>
                    <div class="col-3">
                        <button class="m-header-icon icon-menu js-mobile-dashboard-menu"><i class="fas fa-bars"></i></button>
                    </div>
                </div>
            </div>
        </header>

        <main class="m-main js-mobile-main" infinitescroll ng-controller="dashboardController">
            <div class="swiper-container">
                <div class="swiper-wrapper">
                </div>
            </div>
            <list-web-part view-model="ViewModel.StartWebPartViewModel"></list-web-part>
        </main>

        <footer class="m-footer" ng-controller="dashboardController">
            <ul>
                <li ng-repeat="dashboardItem in ViewModel.DashboardItems">
                    <button ng-disabled="!dashboardItem.IsLinked" class="js-footer-mobilelink" ng-attr-data-id="{{dashboardItem.TagName}}" ng-click="ViewModel.NavigateTo(dashboardItem)">
                        <div class="icon">
                            <i ng-class="dashboardItem.MenuItem.Icon" ng-if="dashboardItem.MenuItem.Icon"></i>
                        </div>
                        <span class="count" ng-show="dashboardItem.MenuItem.hasBadge()" ng-bind="dashboardItem.MenuItem.BadgeCount"></span>
                    </button>
                </li>
            </ul>
        </footer>
    </div>

    <div class="dashboard-menu-topright js-dashboard-menu-topright hide d-block d-md-none" ng-controller="topMenuController">
        <header class="m-header login">
            <div class="container">
                <div class="row">
                    <div class="col-3">
                        <button class="m-header-signout" ng-click="ViewModel.Navigate('/Logout.aspx')"><i class="fa fa-power-off"></i></button>
                    </div>
                    <div class="col-6">
                        <span class="text-white" ng-bind="ViewModel.User.Name" style="font-size: 12px; position: fixed; left: 10px" ng-if="ViewModel.IsParent && !ViewModel.IsRTL"></span>
                        <span class="text-white" ng-bind="ViewModel.User.Name" style="font-size: 12px; position: fixed; right: 10px" ng-if="ViewModel.IsParent && ViewModel.IsRTL"></span>
                        <div class="logo">
                            <a href="{{''.toUriWithSearchPath()}}">
                                <img ng-src='{{ViewModel.StudentSchoolEnrollment.SchoolInfo.LocationInfo.LogoPath}}partner_logo.jpg' alt="">
                            </a>
                        </div>
                    </div>
                    <div class="col-3">
                        <button class="m-header-icon icon-close js-mobile-dashboard-close"><i class="fa fa-times"></i></button>
                    </div>
                </div>
            </div>
        </header>
        <div class="m-main-top">
            <div class="m-top-menu">
                <button ng-repeat="menuItem in ViewModel.XSTopSmallMenuItems" ng-click="menuItem.navigate()">
                    <i class="fa-lg badged-menu-item" ng-class="menuItem.Icon" ng-if="menuItem.Icon">
                        <span class="count" ng-show="menuItem.hasBadge()" ng-bind="menuItem.BadgeCount"></span>
                    </i>
                </button>
                <button ng-click="ViewModel.ShowQRLogin()" ng-if="ViewModel.XSTopSmallMenuItems.length">
                    <i class="fa-lg fas fa-qrcode badged-menu-item"></i>
                </button>
            </div>
        </div>
        <div class="m-main-content">
            <div class="mobile-content-dashboardmenu">
                <ul class="dashboard-menu-list">
                    <li ng-repeat="menuItem in ViewModel.XSTopMenuItems" ng-class="{'active':menuItem.isActive()}">
                        <a href="#" ng-click="menuItem.navigate()">
                            <div class="dashbboard-list-wrapper">
                                <div class="icon" ng-if="menuItem.Icon || menuItem.ImagePath">
                                    <i ng-class="menuItem.Icon" class="badged-menu-item" ng-if="!menuItem.ImagePath">
                                        <span class="count" ng-show="menuItem.hasBadge()" ng-bind="menuItem.BadgeCount"></span>
                                    </i>
                                    <img ng-src="{{menuItem.ImagePath}}" ng-if="menuItem.ImagePath" style="max-height: 40px" />
                                </div>
                                <span ng-bind="menuItem.Title" id="BackgroundItemTitle"></span>
                            </div>
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </div>

    <!--end of mobile-->



    

</body>
</html>
