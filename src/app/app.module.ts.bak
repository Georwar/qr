import { BrowserModule } from '@angular/platform-browser';
import { ErrorHandler, NgModule } from '@angular/core';
import { IonicApp, IonicErrorHandler, IonicModule } from 'ionic-angular';
import { SplashScreen } from '@ionic-native/splash-screen';
import { StatusBar } from '@ionic-native/status-bar';

import { MyApp } from './app.component';

import { GuardadosPage, HomePage, MapaPage, TabsPage } from "../pages/index.paginas";

import { BarcodeScanner } from '@ionic-native/barcode-scanner'
import { HistorialService } from '../providers/historial/historial';

import { InAppBrowser } from '@ionic-native/in-app-browser';

// Mapas
import { AgmCoreModule } from '@agm/core';



@NgModule({
  declarations: [
    MyApp,
    GuardadosPage,
    HomePage,
    MapaPage,
    TabsPage
  ],

  imports: [
    BrowserModule,
    IonicModule.forRoot(MyApp),
    AgmCoreModule.forRoot({
      apiKey: 'AIzaSyAlkY_NM790ueg2o12TGHQTp9T6EGO3a8E'
    })
  ],


  bootstrap: [IonicApp],

  entryComponents: [
    MyApp,
    GuardadosPage,
    HomePage,
    MapaPage,
    TabsPage
  ],

  providers: [
    StatusBar,
    SplashScreen,
    BarcodeScanner,
    {provide: ErrorHandler, useClass: IonicErrorHandler},
    InAppBrowser,
    HistorialService
    
  ]
  

})
export class AppModule {}
