==============
Component List
==============

/* Main Menu */
.main-menu
.main-menu__item




/* User Menu */
.user-menu
.user-menu__item

.user-menu__item--messages
.user-menu__item--notifications
.user-menu__item--settings


/* Main Section Generic List */
.list
.list__item


// Buttons
.u-button
.u-button--large
.u-button-circle


/* From */
/* each component should have [disabled] state */
.form
.form__textfield
.form__textarea
.form__select
.form__button {@extend .u-button}


/* Main Category Buttons */
.category-list
.category-list__item


/* Post Item */
.post-item
.post-item__author-picture
.post-item__author-name
.post-item__title
.post-item__text
.post-item__controls


/* Controls */
.controls
.controls__icon-button
.controls__show-more-button
.controls__answer-count


/* Contextual Messages (Toast) */
.toast
.toast__heading
.toast__text
.toast__close

.toast--green
.toast--yellow
.toast--red
.toast--gray

/* Search Main Content */
.search
.search__icon
.search__text

.category-filters
.category-filters__item
.category-filters__text

.filters
.filters__heading
.filters__item

/* Item for the Search Innovators List */
.person-item
.person-item__picture
.person-item__name
.person-item__job
.person-item__org
.person-item__tags
.person-item__controls

/* Category Tags */
.category-tag
.category-tag__main
.category-tag__sub

/* Steps */
.steps
.steps__item
.steps__item--completed



/* ======================= */
/* PANELS */
/* ======================= */

.u-base-panel
.u-base-panel__heading
.u-base-panel__text
.u-base-panel__action-button // Top right icon

.u-base-panel__action
.u-base-panel__action__title
.u-base-panel__action__button
.u-base-panel__action__button--active
.u-base-panel__large-icon
.u-base-panel__small-text


/* More Info */
.more-info-panel
.more-info-panel--expanded
.more-info-panel__heading
.more-info-panel__text
.more-info-panel__text--small
.more-info-panel__link


/* Question Panel */
.question-panel
@extend .u-base-panel
.question-panel__error

.question-panel--success
.question-panel--success__heading
.question-panel--success__icon


/* Profile Panel */
.profile-panel
@extend .u-base-panel

.profile-panel__picture
.profile-panel__name
.profile-panel__job
.profile-panel__org
.profile-panel__list
.profile-panel__list-item
.profile-panel__list--domains
.profile-panel__list--location
.profile-panel__list--lang
.profile-panel__expertise-panel


// Events Panel
.events-panel
@extend .u-base-panel
.events-panel__image


// Project Panel
.project-panel
.project-panel__heading
.project-panel__item

.project-item
.project-item__title
.project-item__link
.project-item__tags
.project-item__text

.project-item-add
.project-item-add__icon
.project-item-add__text

