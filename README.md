# Ag-grid-locale-fa
persian localization dictionary for Ag-Grid

set this object to the localeText options of ag-grid to localize your ag-grid.

Angular example:

<ag-grid-angular
  style="width: 100%; height: 500px"
  class="ag-theme-alpine"
  [columnDefs]="columnDefs"
  [defaultColDef]="defaultColDef"
  [rowData]="rowData$ | async"
  (gridReady)="onGridReady($event)"
  
  [localeText]="AG_GRID_LOCALE_FA"
></ag-grid-angular>
