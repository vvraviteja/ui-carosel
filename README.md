# ui-carosel

import { ModuleWithProviders } from '@angular/core';
import { Routes, RouterModule }   from '@angular/router';

import { AppComponent } from './app.component';
import { InfiniteCarouselComponent } from "./infinite-carousel/infinite-carousel.component";
import { CustomDotsComponent } from "./custom-dots/custom-dots.component";

const appRoutes: Routes = [
 
  { path:"coustome", component: CustomDotsComponent },
   { path:"infinete", component: InfiniteCarouselComponent },
 
   
 
 
];

export const appRoutingProviders: any[] = [];

export const routing = RouterModule.forRoot(appRoutes);
