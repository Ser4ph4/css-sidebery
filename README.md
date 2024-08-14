#root.root {--bookmarks-sub-panel-height: p;}
#root.root {--tabs-activated-shadow: 0 1px 4px -1px rgba(0,0,0,0.282), inset 0 0 0 1px rgba(255,255,244,0.031);}
#root.root {--ctx-menu-opt-border-radius: calc(4px - 2px + 1px);}
#root.root {--ctx-menu-border-radius: calc(4px + 1px);}
# css-sidebery
CSS backup Sidebery


#root.root {--padding-left-tab: 74px;}
#root.root {--link-color-active: #8d35e2;}
#root.root {--status-active: #47cfff;}
#root.root {--status-ok: #64df64;}
#root.root {--d-fast: 0.26s;}

#root.root {--scroll-progress-height: 18px;}
#root.root {--ctx-menu-separator: #3a5876ff;}
#root.root {--ctx-menu-font: 0.975rem sans-serif;}

#root.root {--ctx-menu-opt-padding: 4px;}
#root.root {--ctx-menu-text-opt-height: 26px;}
#root.root {--history-item-padding-right: 5px;}
#root.root {--history-item-border-radius: 4px;}

#root.root {--tabs-activated-bg: #42414dff;}
#root.root {--tabs-activated-fg: rgb(251,251,254);}
#root.root {--tabs-pinned-height: 30px;}
#root.root {--tabs-progress-bg: #0ca907ff;}
#root.root {--tabs-pinned-width: 30px;}
#root.root {--tabs-height: 30px;}
#root.root {--tabs-close-btn-margin: 2px;}
#root.root {--tabs-activated-color-layer-opacity: 0.3;}
#root.root {--tabs-lvl-opacity: 0.16;}
#root.root {--nav-btn-accent: #b7152eff;}
#root.root {--nav-btn-len-margin: 0px;}
#root.root {--history-item-margin: 2px;}

#root.root {--history-item-padding-left: 1px;}
#root.root {--tabs-margin: 1px;}
#root.root {--tabs-indent: 10px;}
#root.root {--tabs-font: 0.9999rem sans-serif;}
#root.root {--tabs-border-radius: 3px;}
#root.root {--tabs-inner-gap: 9px;}
#root.root {--tabs-audio-btn-width: 12px;}
#root.root {--tabs-color-layer-opacity: 0.2;}
#root.root {--nav-btn-width: 30px;}
#root.root {--nav-btn-height: 10px;}
#root.root {--nav-btn-margin: 1px;}
#root.root {--nav-delimiter-size: 6px;}
#root.root {--nav-btn-border-radius: 5px;}
#root.root {--nav-hidden-btn-border-radius: 1px;}
#root.root {--nav-hidden-panels-popup-margin: 1px;}
#root.root {--toolbar-height-personal: 28px;}
#root.root {--general-border-radius: 5px;}
#root.root {--general-margin: 1px;}
:root {
  --ctp-rosewater: #f4dbd6;
  --ctp-flamingo: #f0c6c6;
  --ctp-pink: #f5bde6;
  --ctp-mauve: #c6a0f6;
  --ctp-red: #ed8796;
  --ctp-maroon: #ee99a0;
  --ctp-peach: #f5a97f;
  --ctp-yellow: #eed49f;
  --ctp-green: #a6da95;
  --ctp-teal: #8bd5ca;
  --ctp-sky: #91d7e3;
  --ctp-sapphire: #7dc4e4;
  --ctp-blue: #8aadf4;
  --ctp-lavender: #b7bdf8;
  --ctp-text: #c5cff5;
  --ctp-subtext1: #b3bce0;
  --ctp-subtext0: #a1aacb;
  --ctp-overlay2: #8f97b7;
  --ctp-overlay1: #7d84a2;
  --ctp-overlay0: #6c728d;
  --ctp-surface2: #5a5f78;
  --ctp-surface1: #484c64;
  --ctp-surface0: #363a4f;
  --ctp-base: #24273a;
  --ctp-mantle: #1e2030;
  --ctp-crust: #181926;
}

/*tab close button*/
.Tab .close > svg {
  fill: var(--ctp-maroon);
}

.Tab .close:hover > svg {
  fill: var(--ctp-red);
}

/*containers*/
#root[data-style="auto"] {
  --container-fg: var(--ctp-text);
  --active-container-fg: var(--ctp-text);
}

/*bookmarks*/
#root[data-style="auto"] {
  --bookmarks-node-title-fg: var(--ctp-subtext0);
  --bookmarks-node-title-fg-hover: var(--ctp-subtext1);
  --bookmarks-node-title-fg-active: var(--ctp-text);
  --bookmarks-node-bg-hover: var(--ctp-crust);
  --bookmarks-node-bg-active: var(--ctp-mantle);
  --bookmarks-folder-closed-fg: var(--ctp-surface2);
  --bookmarks-folder-closed-fg-hover: var(--ctp-sky);
  --bookmarks-folder-closed-fg-active: var(--ctp-sky);
  --bookmarks-folder-expanded-fg: var(--ctp-blue);
  --bookmarks-folder-expanded-fg-hover: var(--ctp-blue);
  --bookmarks-folder-expanded-fg-active: var(--ctp-blue);
  --bookmarks-folder-empty-fg: var(--ctp-surface0);
  --bookmarks-open-bookmark-fg: var(--ctp-blue);
}

/*tabs*/
#root[data-style="auto"] {
  --tabs-fg: var(--ctp-subtext0);
  --tabs-fg-hover: var(--ctp-subtext1);
  --tabs-fg-active: var(--ctp-rosewater);
  --tabs-bg-hover: var(--ctp-crust);
  --tabs-bg-active: var(--ctp-mantle);
  --tabs-activated-bg: var(--ctp-mantle);
  --tabs-activated-fg: var(--ctp-text);
  --tabs-selected-bg: var(--ctp-blue);
  --tabs-selected-fg: var(--ctp-crust);
  --tabs-loading-fg: var(--ctp-blue);
  --tabs-update-badge-bg: var(--ctp-blue);
  --tabs-lvl-indicator-bg: var(--ctp-surface0);
}

/*navbar button*/
#root[data-style="auto"] {
  --nav-btn-fg: var(--ctp-text);
  --nav-btn-bg-focus: var(--ctp-overlay0);
  --nav-btn-activated-bg: var(--ctp-mantle);
  /*(shadow not styled yet)*/
  --nav-btn-update-badge-bg: var(--ctp-blue);
}

/*context menu*/
#root[data-style="auto"] {
  --ctx-menu-bg: var(--ctp-surface0);
  --ctx-menu-bg-hover: var(--ctp-base);
  --ctx-menu-warn-bg-hover: var(--ctp-maroon);
  --ctx-menu-fg: var(--ctp-text);
  --ctx-menu-warn-fg: var(--ctp-maroon);
  /*(shadow not styled yet)*/
}

/*buttons*/
#root[data-style="auto"] {
  --btn-bg: var(--ctp-blue);
  --btn-bg-hover: var(--ctp-sapphire);
  --btn-bg-active: var(--ctp-sky);
}

/*base*/
#root[data-style="auto"] {
  --bg: var(--ctp-base);
  --title-fg: var(--ctp-text);
  --sub-title-fg: var(--ctp-text);
  --label-fg: var(--ctp-subtext0);
  --label-fg-hover: var(--ctp-subtext1);
  --label-fg-active: var(--ctp-text);
  --info-fg: var(--ctp-sapphire);
  --true-fg: var(--ctp-green);
  --false-fg: var(--ctp-red);
  --false-bg: var(--ctp-crust);
  --active-fg: var(--ctp-blue);
  --inactive-fg: var(--ctp-surface2);
  --notice-fg: var(--ctp-sky);
  --favicons-placeholder-bg: var(--ctp-surface0);
  --border-fg: var(--ctp-crust);
  --border-active-fg: var(--ctp-crust);
  --border-flare-fg: var(--ctp-mantle);
  --progress-fg: var(--ctp-sky);
  --progress-bg: var(--ctp-surface0);
}
