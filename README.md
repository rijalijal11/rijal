<ion-header>
  <ion-navbar color="Teal">
    <ion-title>tambah</ion-title>
  </ion-navbar>
</ion-header>
<ion-content>
  <ion-list>
    <ion-item>
      <ion-label stacked>judul Kajian</ion-label>
      <ion-input type="tempat" [(ngModel)]="kajian"></ion-input>
    </ion-item>
    <ion-item>
      <ion-label stacked>Ust/pemateri</ion-label>
      <ion-input type="Pemateri" [(ngModel)]="ust"></ion-input>
    </ion-item>
    <ion-item>
      <ion-label stacked>Cari Lokasi</ion-label>
      <ion-input type="lokasi" [(ngModel)]="lokasi"></ion-input>
      
    </ion-item>
    <ion-item>
      <ion-label stacked>Hari/Bulan/Tahun</ion-label>
      <ion-datetime displayFormat="MMM/DD/YYYY"[(ngModel)]="Date"></ion-datetime>
    </ion-item>
    <ion-item>
      <ion-label stacked>Start Time</ion-label>
      <ion-datetime displayFormat="HH:mm"[(ngModel)]="time"></ion-datetime>
    </ion-item>
    <br><div padding>
      <button ion-button color="teal" (click)="tambah()">Tambah Kajian</button>
    </div>
  </ion-list> 
