## API Report File for "components-srcs"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { AfterViewInit } from '@angular/core';
import { ElementRef } from '@angular/core';
import { FocusOrigin } from '@angular/cdk/a11y';
import * as i0 from '@angular/core';
import * as i1 from '@angular/material/core';
import { InjectionToken } from '@angular/core';
import { MatRippleLoader } from '@angular/material/core';
import { NgZone } from '@angular/core';
import { OnDestroy } from '@angular/core';
import { OnInit } from '@angular/core';
import { ThemePalette } from '@angular/material/core';

// @public
export const MAT_BUTTON_CONFIG: InjectionToken<MatButtonConfig>;

// @public
export const MAT_FAB_DEFAULT_OPTIONS: InjectionToken<MatFabDefaultOptions>;

// @public
export function MAT_FAB_DEFAULT_OPTIONS_FACTORY(): MatFabDefaultOptions;

// @public
export class MatAnchor extends MatAnchorBase {
    // (undocumented)
    static ɵcmp: i0.ɵɵComponentDeclaration<MatAnchor, "a[mat-button], a[mat-raised-button], a[mat-flat-button], a[mat-stroked-button]", ["matButton", "matAnchor"], {}, {}, never, [".material-icons:not([iconPositionEnd]), mat-icon:not([iconPositionEnd]), [matButtonIcon]:not([iconPositionEnd])", "*", ".material-icons[iconPositionEnd], mat-icon[iconPositionEnd], [matButtonIcon][iconPositionEnd]"], true, never>;
    // (undocumented)
    static ɵfac: i0.ɵɵFactoryDeclaration<MatAnchor, never>;
}

// @public
export class MatButton extends MatButtonBase {
    // (undocumented)
    static ɵcmp: i0.ɵɵComponentDeclaration<MatButton, "    button[mat-button], button[mat-raised-button], button[mat-flat-button],    button[mat-stroked-button]  ", ["matButton"], {}, {}, never, [".material-icons:not([iconPositionEnd]), mat-icon:not([iconPositionEnd]), [matButtonIcon]:not([iconPositionEnd])", "*", ".material-icons[iconPositionEnd], mat-icon[iconPositionEnd], [matButtonIcon][iconPositionEnd]"], true, never>;
    // (undocumented)
    static ɵfac: i0.ɵɵFactoryDeclaration<MatButton, never>;
}

// @public
export interface MatButtonConfig {
    color?: ThemePalette;
    disabledInteractive?: boolean;
}

// @public (undocumented)
export class MatButtonModule {
    // (undocumented)
    static ɵfac: i0.ɵɵFactoryDeclaration<MatButtonModule, never>;
    // (undocumented)
    static ɵinj: i0.ɵɵInjectorDeclaration<MatButtonModule>;
    // (undocumented)
    static ɵmod: i0.ɵɵNgModuleDeclaration<MatButtonModule, never, [typeof i1.MatCommonModule, typeof i1.MatRippleModule, typeof i2.MatAnchor, typeof i2.MatButton, typeof i3.MatIconAnchor, typeof i4.MatMiniFabAnchor, typeof i4.MatMiniFabButton, typeof i3.MatIconButton, typeof i4.MatFabAnchor, typeof i4.MatFabButton], [typeof i2.MatAnchor, typeof i2.MatButton, typeof i3.MatIconAnchor, typeof i3.MatIconButton, typeof i4.MatMiniFabAnchor, typeof i4.MatMiniFabButton, typeof i4.MatFabAnchor, typeof i4.MatFabButton, typeof i1.MatCommonModule]>;
}

// @public
export class MatFabAnchor extends MatAnchor {
    constructor(...args: unknown[]);
    // (undocumented)
    extended: boolean;
    // (undocumented)
    _isFab: boolean;
    // (undocumented)
    static ngAcceptInputType_extended: unknown;
    // (undocumented)
    static ɵcmp: i0.ɵɵComponentDeclaration<MatFabAnchor, "a[mat-fab]", ["matButton", "matAnchor"], { "extended": { "alias": "extended"; "required": false; }; }, {}, never, [".material-icons:not([iconPositionEnd]), mat-icon:not([iconPositionEnd]), [matButtonIcon]:not([iconPositionEnd])", "*", ".material-icons[iconPositionEnd], mat-icon[iconPositionEnd], [matButtonIcon][iconPositionEnd]"], true, never>;
    // (undocumented)
    static ɵfac: i0.ɵɵFactoryDeclaration<MatFabAnchor, never>;
}

// @public
export class MatFabButton extends MatButtonBase {
    constructor(...args: unknown[]);
    // (undocumented)
    extended: boolean;
    // (undocumented)
    _isFab: boolean;
    // (undocumented)
    static ngAcceptInputType_extended: unknown;
    // (undocumented)
    static ɵcmp: i0.ɵɵComponentDeclaration<MatFabButton, "button[mat-fab]", ["matButton"], { "extended": { "alias": "extended"; "required": false; }; }, {}, never, [".material-icons:not([iconPositionEnd]), mat-icon:not([iconPositionEnd]), [matButtonIcon]:not([iconPositionEnd])", "*", ".material-icons[iconPositionEnd], mat-icon[iconPositionEnd], [matButtonIcon][iconPositionEnd]"], true, never>;
    // (undocumented)
    static ɵfac: i0.ɵɵFactoryDeclaration<MatFabButton, never>;
}

// @public
export interface MatFabDefaultOptions {
    color?: ThemePalette;
}

// @public
export class MatIconAnchor extends MatAnchorBase {
    // (undocumented)
    static ɵcmp: i0.ɵɵComponentDeclaration<MatIconAnchor, "a[mat-icon-button]", ["matButton", "matAnchor"], {}, {}, never, ["*"], true, never>;
    // (undocumented)
    static ɵfac: i0.ɵɵFactoryDeclaration<MatIconAnchor, never>;
}

// @public
export class MatIconButton extends MatButtonBase {
    constructor(...args: unknown[]);
    // (undocumented)
    static ɵcmp: i0.ɵɵComponentDeclaration<MatIconButton, "button[mat-icon-button]", ["matButton"], {}, {}, never, ["*"], true, never>;
    // (undocumented)
    static ɵfac: i0.ɵɵFactoryDeclaration<MatIconButton, never>;
}

// @public
export class MatMiniFabAnchor extends MatAnchor {
    constructor(...args: unknown[]);
    // (undocumented)
    _isFab: boolean;
    // (undocumented)
    static ɵcmp: i0.ɵɵComponentDeclaration<MatMiniFabAnchor, "a[mat-mini-fab]", ["matButton", "matAnchor"], {}, {}, never, [".material-icons:not([iconPositionEnd]), mat-icon:not([iconPositionEnd]), [matButtonIcon]:not([iconPositionEnd])", "*", ".material-icons[iconPositionEnd], mat-icon[iconPositionEnd], [matButtonIcon][iconPositionEnd]"], true, never>;
    // (undocumented)
    static ɵfac: i0.ɵɵFactoryDeclaration<MatMiniFabAnchor, never>;
}

// @public
export class MatMiniFabButton extends MatButtonBase {
    constructor(...args: unknown[]);
    // (undocumented)
    _isFab: boolean;
    // (undocumented)
    static ɵcmp: i0.ɵɵComponentDeclaration<MatMiniFabButton, "button[mat-mini-fab]", ["matButton"], {}, {}, never, [".material-icons:not([iconPositionEnd]), mat-icon:not([iconPositionEnd]), [matButtonIcon]:not([iconPositionEnd])", "*", ".material-icons[iconPositionEnd], mat-icon[iconPositionEnd], [matButtonIcon][iconPositionEnd]"], true, never>;
    // (undocumented)
    static ɵfac: i0.ɵɵFactoryDeclaration<MatMiniFabButton, never>;
}

// (No @packageDocumentation comment for this package)

```
