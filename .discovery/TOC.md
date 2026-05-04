# Codebase Discovery — Table of Contents

**Project:** opencode
**Generated:** 2026-05-04 02:45:04Z
**Total source files:** 2670
**Mapped:** 2670
**Coverage:** 100%

---

## Phase 0: Entry Points

| Package | package.json | Bin | Main |
|---------|-------------|-----|------|
| `opencode` | `package.json` | - | `` |
| `github` | `github/package.json` | - | `` |
| `@opencode-ai/ui` | `packages/ui/package.json` | - | `` |
| `@opencode-ai/desktop-electron` | `packages/desktop-electron/package.json` | - | `./out/main/index.js` |
| `@opencode-ai/storybook` | `packages/storybook/package.json` | - | `` |
| `@opencode-ai/core` | `packages/core/package.json` | `opencode` → `./bin/opencode` | `` |
| `@opencode-ai/app` | `packages/app/package.json` | - | `` |
| `@opencode-ai/enterprise` | `packages/enterprise/package.json` | - | `` |
| `@opencode-ai/web` | `packages/web/package.json` | - | `` |
| `@opencode-ai/plugin` | `packages/plugin/package.json` | - | `` |
| `@opencode-ai/desktop` | `packages/desktop/package.json` | - | `` |
| `@opencode-ai/function` | `packages/function/package.json` | - | `` |
| `@opencode-ai/script` | `packages/script/package.json` | - | `` |
| `@opencode-ai/slack` | `packages/slack/package.json` | - | `` |
| `opencode` | `packages/opencode/package.json` | `opencode` → `./bin/opencode` | `` |
| `@opencode-ai/console-core` | `packages/console/core/package.json` | - | `` |
| `@opencode-ai/console-app` | `packages/console/app/package.json` | - | `` |
| `@opencode-ai/console-mail` | `packages/console/mail/package.json` | - | `` |
| `@opencode-ai/console-function` | `packages/console/function/package.json` | - | `` |
| `@opencode-ai/console-resource` | `packages/console/resource/package.json` | - | `` |
| `@opencode-ai/sdk` | `packages/sdk/js/package.json` | - | `` |
| `opencode` | `sdks/vscode/package.json` | - | `./dist/extension.js` |

---

## Phase 1.5: Master File Tracking Table

> **CRITICAL:** EVERY file in the project MUST appear in this table.
> NO file is "not interesting" — every file has a purpose.

| File | Mapped | Purpose | Lines | Primary Export |
|------|--------|---------|-------|----------------|
| `.github/pull_request_template.md` | ✅ | docs | 29 |  |
| `.gitignore` | ✅ | config | 31 |  |
| `.oxlintrc.json` | ✅ | source | 51 |  |
| `.vscode/launch.example.json` | ✅ | source | 11 |  |
| `.vscode/settings.example.json` | ✅ | source | 5 |  |
| `.zed/settings.json` | ✅ | source | 9 |  |
| `AGENTS.md` | ✅ | docs | 103 |  |
| `CONTRIBUTING.md` | ✅ | docs | 311 |  |
| `README.ar.md` | ✅ | docs | 141 |  |
| `README.bn.md` | ✅ | docs | 141 |  |
| `README.br.md` | ✅ | docs | 141 |  |
| `README.bs.md` | ✅ | docs | 141 |  |
| `README.da.md` | ✅ | docs | 141 |  |
| `README.de.md` | ✅ | docs | 141 |  |
| `README.es.md` | ✅ | docs | 141 |  |
| `README.fr.md` | ✅ | docs | 141 |  |
| `README.gr.md` | ✅ | docs | 141 |  |
| `README.it.md` | ✅ | docs | 141 |  |
| `README.ja.md` | ✅ | docs | 141 |  |
| `README.ko.md` | ✅ | docs | 141 |  |
| `README.md` | ✅ | docs | 141 |  |
| `README.no.md` | ✅ | docs | 141 |  |
| `README.pl.md` | ✅ | docs | 141 |  |
| `README.ru.md` | ✅ | docs | 141 |  |
| `README.th.md` | ✅ | docs | 141 |  |
| `README.tr.md` | ✅ | docs | 141 |  |
| `README.uk.md` | ✅ | docs | 142 |  |
| `README.vi.md` | ✅ | docs | 141 |  |
| `README.zh.md` | ✅ | docs | 140 |  |
| `README.zht.md` | ✅ | docs | 140 |  |
| `SECURITY.md` | ✅ | docs | 47 |  |
| `STATS.md` | ✅ | docs | 217 |  |
| `bunfig.toml` | ✅ | source | 6 |  |
| `github/.gitignore` | ✅ | source | 34 |  |
| `github/README.md` | ✅ | docs | 166 |  |
| `github/index.ts` | ✅ | source | 1052 |  |
| `github/package.json` | ✅ | source | 20 |  |
| `github/sst-env.d.ts` | ✅ | source | 10 |  |
| `github/tsconfig.json` | ✅ | config | 29 |  |
| `infra/app.ts` | ✅ | source | 68 | EMAILOCTOPUS_API_KEY |
| `infra/console.ts` | ✅ | source | 290 | database |
| `infra/enterprise.ts` | ✅ | source | 17 |  |
| `infra/secret.ts` | ✅ | source | 4 | SECRET |
| `infra/stage.ts` | ✅ | source | 19 | domain |
| `nix/hashes.json` | ✅ | source | 8 |  |
| `nix/scripts/canonicalize-node-modules.ts` | ✅ | source | 101 |  |
| `nix/scripts/normalize-bun-binaries.ts` | ✅ | source | 130 |  |
| `package.json` | ✅ | config | 137 |  |
| `packages/app/.gitignore` | ✅ | source | 3 |  |
| `packages/app/AGENTS.md` | ✅ | docs | 30 |  |
| `packages/app/README.md` | ✅ | docs | 50 |  |
| `packages/app/bunfig.toml` | ✅ | source | 3 |  |
| `packages/app/create-effect-simplification-spec.md` | ✅ | docs | 515 |  |
| `packages/app/e2e/todo.spec.ts` | ✅ | test | 11 |  |
| `packages/app/e2e/tsconfig.json` | ✅ | config | 9 |  |
| `packages/app/happydom.ts` | ✅ | source | 75 |  |
| `packages/app/package.json` | ✅ | source | 79 |  |
| `packages/app/playwright.config.ts` | ✅ | config | 50 |  |
| `packages/app/public/oc-theme-preload.js` | ✅ | source | 35 |  |
| `packages/app/src/addons/serialize.test.ts` | ✅ | test | 319 |  |
| `packages/app/src/addons/serialize.ts` | ✅ | source | 634 | StringSerializeHandler |
| `packages/app/src/app.tsx` | ✅ | source | 330 | AppBaseProviders |
| `packages/app/src/components/debug-bar.tsx` | ✅ | source | 443 | DebugBar |
| `packages/app/src/components/dialog-connect-provider.tsx` | ✅ | source | 654 | DialogConnectProvider |
| `packages/app/src/components/dialog-custom-provider-form.ts` | ✅ | source | 158 | validateCustomProvider |
| `packages/app/src/components/dialog-custom-provider.test.ts` | ✅ | test | 80 |  |
| `packages/app/src/components/dialog-custom-provider.tsx` | ✅ | source | 329 | DialogCustomProvider |
| `packages/app/src/components/dialog-edit-project.tsx` | ✅ | source | 265 | DialogEditProject |
| `packages/app/src/components/dialog-fork.tsx` | ✅ | source | 108 | DialogFork |
| `packages/app/src/components/dialog-manage-models.tsx` | ✅ | source | 101 | DialogManageModels |
| `packages/app/src/components/dialog-release-notes.tsx` | ✅ | source | 144 | DialogReleaseNotes |
| `packages/app/src/components/dialog-select-directory.tsx` | ✅ | source | 392 | DialogSelectDirectory |
| `packages/app/src/components/dialog-select-file.tsx` | ✅ | source | 466 | DialogSelectFile |
| `packages/app/src/components/dialog-select-mcp.tsx` | ✅ | source | 103 | DialogSelectMcp |
| `packages/app/src/components/dialog-select-model-unpaid.tsx` | ✅ | source | 145 | DialogSelectModelUnpaid |
| `packages/app/src/components/dialog-select-model.tsx` | ✅ | source | 230 | ModelSelectorPopover |
| `packages/app/src/components/dialog-select-provider.tsx` | ✅ | source | 86 | DialogSelectProvider |
| `packages/app/src/components/dialog-select-server.tsx` | ✅ | source | 649 | DialogSelectServer |
| `packages/app/src/components/dialog-settings.tsx` | ✅ | source | 73 | DialogSettings |
| `packages/app/src/components/file-tree.test.ts` | ✅ | test | 78 |  |
| `packages/app/src/components/file-tree.tsx` | ✅ | source | 506 | shouldListRoot |
| `packages/app/src/components/link.tsx` | ✅ | source | 26 | Link |
| `packages/app/src/components/model-tooltip.tsx` | ✅ | source | 91 | ModelTooltip |
| `packages/app/src/components/prompt-input.tsx` | ✅ | source | 1615 | PromptInput |
| `packages/app/src/components/prompt-input/attachments.test.ts` | ✅ | test | 44 |  |
| `packages/app/src/components/prompt-input/attachments.ts` | ✅ | source | 196 | createPromptAttachments |
| `packages/app/src/components/prompt-input/build-request-parts.test.ts` | ✅ | test | 336 |  |
| `packages/app/src/components/prompt-input/build-request-parts.ts` | ✅ | source | 201 | buildRequestParts |
| `packages/app/src/components/prompt-input/context-items.tsx` | ✅ | source | 88 | PromptContextItems |
| `packages/app/src/components/prompt-input/drag-overlay.tsx` | ✅ | source | 25 | PromptDragOverlay |
| `packages/app/src/components/prompt-input/editor-dom.test.ts` | ✅ | test | 99 |  |
| `packages/app/src/components/prompt-input/editor-dom.ts` | ✅ | source | 148 | createTextFragment |
| `packages/app/src/components/prompt-input/files.ts` | ✅ | source | 66 | attachmentMime |
| `packages/app/src/components/prompt-input/history.test.ts` | ✅ | test | 153 |  |
| `packages/app/src/components/prompt-input/history.ts` | ✅ | source | 256 | canNavigateHistoryAtCursor |
| `packages/app/src/components/prompt-input/image-attachments.tsx` | ✅ | source | 61 | PromptImageAttachments |
| `packages/app/src/components/prompt-input/paste.ts` | ✅ | source | 24 | normalizePaste |
| `packages/app/src/components/prompt-input/placeholder.test.ts` | ✅ | test | 48 |  |
| `packages/app/src/components/prompt-input/placeholder.ts` | ✅ | source | 15 | promptPlaceholder |
| `packages/app/src/components/prompt-input/slash-popover.tsx` | ✅ | source | 141 | PromptPopover |
| `packages/app/src/components/prompt-input/submit.test.ts` | ✅ | test | 345 |  |
| `packages/app/src/components/prompt-input/submit.ts` | ✅ | source | 584 | sendFollowupDraft |
| `packages/app/src/components/server/server-row.tsx` | ✅ | source | 127 | ServerRow |
| `packages/app/src/components/session-context-usage.tsx` | ✅ | source | 124 | SessionContextUsage |
| `packages/app/src/components/session/index.ts` | ✅ | source | 5 |  |
| `packages/app/src/components/session/session-context-breakdown.test.ts` | ✅ | test | 61 |  |
| `packages/app/src/components/session/session-context-breakdown.ts` | ✅ | source | 132 | estimateSessionContextBreakdown |
| `packages/app/src/components/session/session-context-format.ts` | ✅ | source | 20 | createSessionContextFormatter |
| `packages/app/src/components/session/session-context-metrics.test.ts` | ✅ | test | 101 |  |
| `packages/app/src/components/session/session-context-metrics.ts` | ✅ | source | 82 | getSessionContextMetrics |
| `packages/app/src/components/session/session-context-tab.tsx` | ✅ | source | 341 | SessionContextTab |
| `packages/app/src/components/session/session-header.tsx` | ✅ | source | 503 | SessionHeader |
| `packages/app/src/components/session/session-new-view.tsx` | ✅ | source | 91 | NewSessionView |
| `packages/app/src/components/session/session-sortable-tab.tsx` | ✅ | source | 70 | FileVisual |
| `packages/app/src/components/session/session-sortable-terminal-tab.tsx` | ✅ | source | 193 | SortableTerminalTab |
| `packages/app/src/components/settings-general.tsx` | ✅ | source | 802 | SettingsGeneral |
| `packages/app/src/components/settings-keybinds.tsx` | ✅ | source | 453 | SettingsKeybinds |
| `packages/app/src/components/settings-list.tsx` | ✅ | source | 5 | SettingsList |
| `packages/app/src/components/settings-models.tsx` | ✅ | source | 137 | SettingsModels |
| `packages/app/src/components/settings-providers.tsx` | ✅ | source | 251 | SettingsProviders |
| `packages/app/src/components/status-popover-body.tsx` | ✅ | source | 404 | StatusPopoverBody |
| `packages/app/src/components/status-popover.tsx` | ✅ | source | 66 | StatusPopover |
| `packages/app/src/components/terminal.tsx` | ✅ | source | 645 | Terminal |
| `packages/app/src/components/titlebar-history.test.ts` | ✅ | test | 63 |  |
| `packages/app/src/components/titlebar-history.ts` | ✅ | source | 57 | applyPath |
| `packages/app/src/components/titlebar.tsx` | ✅ | source | 321 | Titlebar |
| `packages/app/src/constants/file-picker.ts` | ✅ | source | 89 | filePickerFilters |
| `packages/app/src/context/command-keybind.test.ts` | ✅ | test | 69 |  |
| `packages/app/src/context/command.test.ts` | ✅ | test | 25 |  |
| `packages/app/src/context/command.tsx` | ✅ | source | 434 | upsertCommandRegistration |
| `packages/app/src/context/comments.test.ts` | ✅ | test | 186 |  |
| `packages/app/src/context/comments.tsx` | ✅ | source | 243 | createCommentSessionForTest |
| `packages/app/src/context/file-content-eviction-accounting.test.ts` | ✅ | test | 65 |  |
| `packages/app/src/context/file.tsx` | ✅ | source | 280 |  |
| `packages/app/src/context/file/content-cache.ts` | ✅ | source | 88 | approxBytes |
| `packages/app/src/context/file/path.test.ts` | ✅ | test | 360 |  |
| `packages/app/src/context/file/path.ts` | ✅ | source | 151 | stripFileProtocol |
| `packages/app/src/context/file/tree-store.ts` | ✅ | source | 170 | createFileTreeStore |
| `packages/app/src/context/file/types.ts` | ✅ | source | 41 | selectionFromLines |
| `packages/app/src/context/file/view-cache.ts` | ✅ | source | 146 | createFileViewCache |
| `packages/app/src/context/file/watcher.test.ts` | ✅ | test | 149 |  |
| `packages/app/src/context/file/watcher.ts` | ✅ | source | 53 | invalidateFromWatcher |
| `packages/app/src/context/global-sdk.tsx` | ✅ | source | 256 |  |
| `packages/app/src/context/global-sync.test.ts` | ✅ | test | 122 |  |
| `packages/app/src/context/global-sync.tsx` | ✅ | source | 443 | GlobalSyncProvider |
| `packages/app/src/context/global-sync/bootstrap.ts` | ✅ | source | 378 | clearProviderRev |
| `packages/app/src/context/global-sync/child-store.test.ts` | ✅ | test | 40 |  |
| `packages/app/src/context/global-sync/child-store.ts` | ✅ | source | 337 | createChildStoreManager |
| `packages/app/src/context/global-sync/event-reducer.test.ts` | ✅ | test | 554 |  |
| `packages/app/src/context/global-sync/event-reducer.ts` | ✅ | source | 364 | applyGlobalEvent |
| `packages/app/src/context/global-sync/eviction.ts` | ✅ | source | 28 | pickDirectoriesToEvict |
| `packages/app/src/context/global-sync/queue.test.ts` | ✅ | test | 46 |  |
| `packages/app/src/context/global-sync/queue.ts` | ✅ | source | 87 | createRefreshQueue |
| `packages/app/src/context/global-sync/session-cache.test.ts` | ✅ | test | 102 |  |
| `packages/app/src/context/global-sync/session-cache.ts` | ✅ | source | 62 | dropSessionCaches |
| `packages/app/src/context/global-sync/session-load.ts` | ✅ | source | 25 | loadRootSessionsWithFallback |
| `packages/app/src/context/global-sync/session-prefetch.test.ts` | ✅ | test | 96 |  |
| `packages/app/src/context/global-sync/session-prefetch.ts` | ✅ | source | 100 | shouldSkipSessionPrefetch |
| `packages/app/src/context/global-sync/session-trim.test.ts` | ✅ | test | 59 |  |
| `packages/app/src/context/global-sync/session-trim.ts` | ✅ | source | 56 | sessionUpdatedAt |
| `packages/app/src/context/global-sync/types.ts` | ✅ | source | 135 | MAX_DIR_STORES |
| `packages/app/src/context/global-sync/utils.test.ts` | ✅ | test | 52 |  |
| `packages/app/src/context/global-sync/utils.ts` | ✅ | source | 40 | normalizeAgentList |
| `packages/app/src/context/highlights.tsx` | ✅ | source | 233 |  |
| `packages/app/src/context/language.tsx` | ✅ | source | 236 | loadLocaleDict |
| `packages/app/src/context/layout-scroll.test.ts` | ✅ | test | 64 |  |
| `packages/app/src/context/layout-scroll.ts` | ✅ | source | 126 | createScrollPersistence |
| `packages/app/src/context/layout.test.ts` | ✅ | test | 69 |  |
| `packages/app/src/context/layout.tsx` | ✅ | source | 928 | getAvatarColors |
| `packages/app/src/context/local.tsx` | ✅ | source | 392 |  |
| `packages/app/src/context/model-variant.test.ts` | ✅ | test | 86 |  |
| `packages/app/src/context/model-variant.ts` | ✅ | source | 52 | getConfiguredAgentVariant |
| `packages/app/src/context/models.tsx` | ✅ | source | 163 |  |
| `packages/app/src/context/notification.tsx` | ✅ | source | 373 |  |
| `packages/app/src/context/permission-auto-respond.test.ts` | ✅ | test | 102 |  |
| `packages/app/src/context/permission-auto-respond.ts` | ✅ | source | 51 | acceptKey |
| `packages/app/src/context/permission.tsx` | ✅ | source | 277 |  |
| `packages/app/src/context/platform.tsx` | ✅ | source | 99 |  |
| `packages/app/src/context/prompt.tsx` | ✅ | source | 297 | isPromptEqual |
| `packages/app/src/context/sdk.tsx` | ✅ | source | 49 |  |
| `packages/app/src/context/server.tsx` | ✅ | source | 303 | normalizeServerUrl |
| `packages/app/src/context/settings.tsx` | ✅ | source | 332 | monoInput |
| `packages/app/src/context/sync-optimistic.test.ts` | ✅ | test | 123 |  |
| `packages/app/src/context/sync.tsx` | ✅ | source | 619 | mergeOptimisticPage |
| `packages/app/src/context/terminal-title.ts` | ✅ | source | 24 | defaultTitle |
| `packages/app/src/context/terminal.test.ts` | ✅ | test | 82 |  |
| `packages/app/src/context/terminal.tsx` | ✅ | source | 437 | migrateTerminalState |
| `packages/app/src/entry.tsx` | ✅ | source | 164 |  |
| `packages/app/src/env.d.ts` | ✅ | source | 21 |  |
| `packages/app/src/hooks/use-providers.ts` | ✅ | source | 44 | useProviders |
| `packages/app/src/i18n/ar.ts` | ✅ | source | 846 | dict |
| `packages/app/src/i18n/br.ts` | ✅ | source | 859 | dict |
| `packages/app/src/i18n/bs.ts` | ✅ | source | 935 | dict |
| `packages/app/src/i18n/da.ts` | ✅ | source | 929 | dict |
| `packages/app/src/i18n/de.ts` | ✅ | source | 871 | dict |
| `packages/app/src/i18n/en.ts` | ✅ | source | 960 | dict |
| `packages/app/src/i18n/es.ts` | ✅ | source | 942 | dict |
| `packages/app/src/i18n/fr.ts` | ✅ | source | 870 | dict |
| `packages/app/src/i18n/ja.ts` | ✅ | source | 853 | dict |
| `packages/app/src/i18n/ko.ts` | ✅ | source | 848 | dict |
| `packages/app/src/i18n/no.ts` | ✅ | source | 936 | dict |
| `packages/app/src/i18n/parity.test.ts` | ✅ | test | 32 |  |
| `packages/app/src/i18n/pl.ts` | ✅ | source | 857 | dict |
| `packages/app/src/i18n/ru.ts` | ✅ | source | 938 | dict |
| `packages/app/src/i18n/th.ts` | ✅ | source | 925 | dict |
| `packages/app/src/i18n/tr.ts` | ✅ | source | 944 | dict |
| `packages/app/src/i18n/zh.ts` | ✅ | source | 920 | dict |
| `packages/app/src/i18n/zht.ts` | ✅ | source | 916 | dict |
| `packages/app/src/index.css` | ✅ | style | 85 |  |
| `packages/app/src/index.ts` | ✅ | source | 7 |  |
| `packages/app/src/pages/directory-layout.tsx` | ✅ | source | 82 |  |
| `packages/app/src/pages/error.tsx` | ✅ | source | 336 | ErrorPage |
| `packages/app/src/pages/home.tsx` | ✅ | source | 139 |  |
| `packages/app/src/pages/layout.tsx` | ✅ | source | 2504 |  |
| `packages/app/src/pages/layout/deep-links.ts` | ✅ | source | 50 | deepLinkEvent |
| `packages/app/src/pages/layout/helpers.test.ts` | ✅ | test | 225 |  |
| `packages/app/src/pages/layout/helpers.ts` | ✅ | source | 90 | hasProjectPermissions |
| `packages/app/src/pages/layout/inline-editor.tsx` | ✅ | source | 126 | createInlineEditorController |
| `packages/app/src/pages/layout/sidebar-items.tsx` | ✅ | source | 335 | getProjectAvatarSource |
| `packages/app/src/pages/layout/sidebar-project.tsx` | ✅ | source | 367 | ProjectDragOverlay |
| `packages/app/src/pages/layout/sidebar-shell.tsx` | ✅ | source | 125 | SidebarContent |
| `packages/app/src/pages/layout/sidebar-workspace.tsx` | ✅ | source | 483 | WorkspaceDragOverlay |
| `packages/app/src/pages/session.tsx` | ✅ | source | 1972 |  |
| `packages/app/src/pages/session/composer/index.ts` | ✅ | source | 2 |  |
| `packages/app/src/pages/session/composer/session-composer-region.tsx` | ✅ | source | 289 | SessionComposerRegion |
| `packages/app/src/pages/session/composer/session-composer-state.test.ts` | ✅ | test | 128 |  |
| `packages/app/src/pages/session/composer/session-composer-state.ts` | ✅ | source | 198 | createSessionComposerState |
| `packages/app/src/pages/session/composer/session-followup-dock.tsx` | ✅ | source | 109 | SessionFollowupDock |
| `packages/app/src/pages/session/composer/session-permission-dock.tsx` | ✅ | source | 74 | SessionPermissionDock |
| `packages/app/src/pages/session/composer/session-question-dock.tsx` | ✅ | source | 568 | SessionQuestionDock |
| `packages/app/src/pages/session/composer/session-request-tree.ts` | ✅ | source | 52 | sessionPermissionRequest |
| `packages/app/src/pages/session/composer/session-revert-dock.tsx` | ✅ | source | 99 | SessionRevertDock |
| `packages/app/src/pages/session/composer/session-todo-dock.tsx` | ✅ | source | 258 | SessionTodoDock |
| `packages/app/src/pages/session/file-tab-scroll.test.ts` | ✅ | test | 40 |  |
| `packages/app/src/pages/session/file-tab-scroll.ts` | ✅ | source | 67 | nextTabListScrollLeft |
| `packages/app/src/pages/session/file-tabs.tsx` | ✅ | source | 456 | FileTabContent |
| `packages/app/src/pages/session/handoff.ts` | ✅ | source | 36 | setSessionHandoff |
| `packages/app/src/pages/session/helpers.test.ts` | ✅ | test | 181 |  |
| `packages/app/src/pages/session/helpers.ts` | ✅ | source | 194 | getSessionKey |
| `packages/app/src/pages/session/message-gesture.test.ts` | ✅ | test | 62 |  |
| `packages/app/src/pages/session/message-gesture.ts` | ✅ | source | 21 | normalizeWheelDelta |
| `packages/app/src/pages/session/message-id-from-hash.ts` | ✅ | source | 6 | messageIdFromHash |
| `packages/app/src/pages/session/message-timeline.tsx` | ✅ | source | 1118 | MessageTimeline |
| `packages/app/src/pages/session/review-tab.tsx` | ✅ | source | 170 | SessionReviewTab |
| `packages/app/src/pages/session/session-layout.ts` | ✅ | source | 20 | useSessionKey |
| `packages/app/src/pages/session/session-model-helpers.test.ts` | ✅ | test | 52 |  |
| `packages/app/src/pages/session/session-model-helpers.ts` | ✅ | source | 16 | resetSessionModel |
| `packages/app/src/pages/session/session-side-panel.tsx` | ✅ | source | 453 | SessionSidePanel |
| `packages/app/src/pages/session/terminal-label.ts` | ✅ | source | 16 | terminalTabLabel |
| `packages/app/src/pages/session/terminal-panel.test.ts` | ✅ | test | 25 |  |
| `packages/app/src/pages/session/terminal-panel.tsx` | ✅ | source | 317 | TerminalPanel |
| `packages/app/src/pages/session/use-session-commands.tsx` | ✅ | source | 587 | useSessionCommands |
| `packages/app/src/pages/session/use-session-hash-scroll.test.ts` | ✅ | test | 16 |  |
| `packages/app/src/pages/session/use-session-hash-scroll.ts` | ✅ | source | 215 | useSessionHashScroll |
| `packages/app/src/sst-env.d.ts` | ✅ | source | 12 |  |
| `packages/app/src/theme-preload.test.ts` | ✅ | test | 46 |  |
| `packages/app/src/utils/agent.ts` | ✅ | source | 44 | agentColor |
| `packages/app/src/utils/aim.ts` | ✅ | source | 138 | createAim |
| `packages/app/src/utils/base64.ts` | ✅ | source | 10 | decode64 |
| `packages/app/src/utils/comment-note.ts` | ✅ | source | 88 | createCommentMetadata |
| `packages/app/src/utils/diffs.test.ts` | ✅ | test | 74 |  |
| `packages/app/src/utils/diffs.ts` | ✅ | source | 49 | diffs |
| `packages/app/src/utils/id.ts` | ✅ | source | 99 |  |
| `packages/app/src/utils/notification-click.test.ts` | ✅ | test | 27 |  |
| `packages/app/src/utils/notification-click.ts` | ✅ | source | 13 | setNavigate |
| `packages/app/src/utils/path-key.ts` | ✅ | source | 24 | pathKey |
| `packages/app/src/utils/persist.test.ts` | ✅ | test | 167 |  |
| `packages/app/src/utils/persist.ts` | ✅ | source | 611 | removePersisted |
| `packages/app/src/utils/prompt.test.ts` | ✅ | test | 44 |  |
| `packages/app/src/utils/prompt.ts` | ✅ | source | 203 | extractPromptFromParts |
| `packages/app/src/utils/runtime-adapters.test.ts` | ✅ | test | 64 |  |
| `packages/app/src/utils/runtime-adapters.ts` | ✅ | source | 39 | isDisposable |
| `packages/app/src/utils/same.ts` | ✅ | source | 6 | same |
| `packages/app/src/utils/scoped-cache.test.ts` | ✅ | test | 69 |  |
| `packages/app/src/utils/scoped-cache.ts` | ✅ | source | 104 | createScopedCache |
| `packages/app/src/utils/server-errors.test.ts` | ✅ | test | 131 |  |
| `packages/app/src/utils/server-errors.ts` | ✅ | source | 80 | formatServerError |
| `packages/app/src/utils/server-health.test.ts` | ✅ | test | 123 |  |
| `packages/app/src/utils/server-health.ts` | ✅ | source | 113 | checkServerHealth |
| `packages/app/src/utils/server.ts` | ✅ | source | 25 | createSdkForServer |
| `packages/app/src/utils/session-title.ts` | ✅ | source | 7 | sessionTitle |
| `packages/app/src/utils/solid-dnd.tsx` | ✅ | source | 49 | getDraggableId |
| `packages/app/src/utils/sound.ts` | ✅ | source | 102 | soundSrc |
| `packages/app/src/utils/terminal-writer.test.ts` | ✅ | test | 64 |  |
| `packages/app/src/utils/terminal-writer.ts` | ✅ | source | 65 | terminalWriter |
| `packages/app/src/utils/time.ts` | ✅ | source | 22 | getRelativeTime |
| `packages/app/src/utils/uuid.test.ts` | ✅ | test | 78 |  |
| `packages/app/src/utils/uuid.ts` | ✅ | source | 12 | uuid |
| `packages/app/src/utils/worktree.test.ts` | ✅ | test | 46 |  |
| `packages/app/src/utils/worktree.ts` | ✅ | source | 73 | Worktree |
| `packages/app/sst-env.d.ts` | ✅ | source | 10 |  |
| `packages/app/tsconfig.json` | ✅ | config | 26 |  |
| `packages/app/vite.config.ts` | ✅ | config | 33 |  |
| `packages/app/vite.js` | ✅ | source | 38 |  |
| `packages/console/app/.gitignore` | ✅ | source | 30 |  |
| `packages/console/app/README.md` | ✅ | docs | 32 |  |
| `packages/console/app/package.json` | ✅ | source | 46 |  |
| `packages/console/app/public/theme.json` | ✅ | source | 182 |  |
| `packages/console/app/script/generate-sitemap.ts` | ✅ | source | 108 |  |
| `packages/console/app/src/app.css` | ✅ | style | 1 |  |
| `packages/console/app/src/app.tsx` | ✅ | source | 44 |  |
| `packages/console/app/src/component/dropdown.css` | ✅ | style | 80 |  |
| `packages/console/app/src/component/dropdown.tsx` | ✅ | source | 79 | Dropdown |
| `packages/console/app/src/component/email-signup.tsx` | ✅ | source | 47 | EmailSignup |
| `packages/console/app/src/component/faq.tsx` | ✅ | source | 33 | Faq |
| `packages/console/app/src/component/footer.tsx` | ✅ | source | 48 | Footer |
| `packages/console/app/src/component/header-context-menu.css` | ✅ | style | 63 |  |
| `packages/console/app/src/component/header.tsx` | ✅ | source | 293 | Header |
| `packages/console/app/src/component/icon.tsx` | ✅ | source | 286 | IconZen |
| `packages/console/app/src/component/language-picker.css` | ✅ | style | 135 |  |
| `packages/console/app/src/component/language-picker.tsx` | ✅ | source | 40 | LanguagePicker |
| `packages/console/app/src/component/legal.tsx` | ✅ | source | 28 | Legal |
| `packages/console/app/src/component/locale-links.tsx` | ✅ | source | 36 | LocaleLinks |
| `packages/console/app/src/component/modal.css` | ✅ | style | 67 |  |
| `packages/console/app/src/component/modal.tsx` | ✅ | source | 24 | Modal |
| `packages/console/app/src/component/spotlight.css` | ✅ | style | 15 |  |
| `packages/console/app/src/component/spotlight.tsx` | ✅ | source | 820 | defaultConfig |
| `packages/console/app/src/config.ts` | ✅ | config | 29 |  |
| `packages/console/app/src/context/auth.session.ts` | ✅ | source | 1 |  |
| `packages/console/app/src/context/auth.ts` | ✅ | source | 116 | useAuthSession |
| `packages/console/app/src/context/auth.withActor.ts` | ✅ | source | 7 | withActor |
| `packages/console/app/src/context/i18n.tsx` | ✅ | source | 27 |  |
| `packages/console/app/src/context/language.tsx` | ✅ | source | 72 |  |
| `packages/console/app/src/entry-client.tsx` | ✅ | source | 4 |  |
| `packages/console/app/src/entry-server.tsx` | ✅ | source | 37 |  |
| `packages/console/app/src/global.d.ts` | ✅ | source | 5 |  |
| `packages/console/app/src/i18n/ar.ts` | ✅ | source | 779 | dict |
| `packages/console/app/src/i18n/br.ts` | ✅ | source | 791 | dict |
| `packages/console/app/src/i18n/da.ts` | ✅ | source | 785 | dict |
| `packages/console/app/src/i18n/de.ts` | ✅ | source | 790 | dict |
| `packages/console/app/src/i18n/en.ts` | ✅ | source | 784 | dict |
| `packages/console/app/src/i18n/es.ts` | ✅ | source | 790 | dict |
| `packages/console/app/src/i18n/fr.ts` | ✅ | source | 797 | dict |
| `packages/console/app/src/i18n/index.ts` | ✅ | source | 43 | i18n |
| `packages/console/app/src/i18n/it.ts` | ✅ | source | 787 | dict |
| `packages/console/app/src/i18n/ja.ts` | ✅ | source | 788 | dict |
| `packages/console/app/src/i18n/ko.ts` | ✅ | source | 779 | dict |
| `packages/console/app/src/i18n/no.ts` | ✅ | source | 786 | dict |
| `packages/console/app/src/i18n/pl.ts` | ✅ | source | 792 | dict |
| `packages/console/app/src/i18n/ru.ts` | ✅ | source | 794 | dict |
| `packages/console/app/src/i18n/th.ts` | ✅ | source | 782 | dict |
| `packages/console/app/src/i18n/tr.ts` | ✅ | source | 791 | dict |
| `packages/console/app/src/i18n/zh.ts` | ✅ | source | 761 | dict |
| `packages/console/app/src/i18n/zht.ts` | ✅ | source | 760 | dict |
| `packages/console/app/src/lib/changelog.ts` | ✅ | source | 146 | loadChangelog |
| `packages/console/app/src/lib/form-error.ts` | ✅ | source | 86 | formErrorReloadAmountMin |
| `packages/console/app/src/lib/github.ts` | ✅ | source | 38 | github |
| `packages/console/app/src/lib/language.ts` | ✅ | source | 324 | docs |
| `packages/console/app/src/lib/salesforce.ts` | ✅ | source | 81 | createLead |
| `packages/console/app/src/middleware.ts` | ✅ | source | 16 |  |
| `packages/console/app/src/routes/[...404].css` | ✅ | style | 130 |  |
| `packages/console/app/src/routes/[...404].tsx` | ✅ | source | 42 |  |
| `packages/console/app/src/routes/api/enterprise.ts` | ✅ | source | 129 | POST |
| `packages/console/app/src/routes/auth/[...callback].ts` | ✅ | source | 46 | GET |
| `packages/console/app/src/routes/auth/authorize.ts` | ✅ | source | 10 | GET |
| `packages/console/app/src/routes/auth/index.ts` | ✅ | source | 14 | GET |
| `packages/console/app/src/routes/auth/logout.ts` | ✅ | source | 17 | GET |
| `packages/console/app/src/routes/auth/status.ts` | ✅ | source | 7 | GET |
| `packages/console/app/src/routes/bench/[id].tsx` | ✅ | source | 375 |  |
| `packages/console/app/src/routes/bench/index.tsx` | ✅ | source | 88 |  |
| `packages/console/app/src/routes/bench/submission.ts` | ✅ | source | 32 | POST |
| `packages/console/app/src/routes/black.css` | ✅ | style | 841 |  |
| `packages/console/app/src/routes/black.tsx` | ✅ | source | 283 |  |
| `packages/console/app/src/routes/black/common.tsx` | ✅ | source | 65 | PlanIcon |
| `packages/console/app/src/routes/black/index.tsx` | ✅ | source | 125 |  |
| `packages/console/app/src/routes/black/subscribe/[plan].tsx` | ✅ | source | 484 |  |
| `packages/console/app/src/routes/black/workspace.css` | ✅ | style | 214 |  |
| `packages/console/app/src/routes/black/workspace.tsx` | ✅ | source | 238 |  |
| `packages/console/app/src/routes/brand/index.css` | ✅ | style | 556 |  |
| `packages/console/app/src/routes/brand/index.tsx` | ✅ | source | 315 |  |
| `packages/console/app/src/routes/changelog.json.ts` | ✅ | source | 30 | GET |
| `packages/console/app/src/routes/changelog/index.css` | ✅ | style | 604 |  |
| `packages/console/app/src/routes/changelog/index.tsx` | ✅ | source | 176 |  |
| `packages/console/app/src/routes/debug/index.ts` | ✅ | source | 13 | GET |
| `packages/console/app/src/routes/desktop-feedback.ts` | ✅ | source | 5 | GET |
| `packages/console/app/src/routes/discord.ts` | ✅ | source | 5 | GET |
| `packages/console/app/src/routes/docs/[...path].ts` | ✅ | source | 30 | GET |
| `packages/console/app/src/routes/docs/index.ts` | ✅ | source | 30 | GET |
| `packages/console/app/src/routes/download/[channel]/[platform].ts` | ✅ | source | 50 | GET |
| `packages/console/app/src/routes/download/index.css` | ✅ | style | 752 |  |
| `packages/console/app/src/routes/download/index.tsx` | ✅ | source | 486 |  |
| `packages/console/app/src/routes/download/types.ts` | ✅ | source | 4 |  |
| `packages/console/app/src/routes/enterprise/index.css` | ✅ | style | 588 |  |
| `packages/console/app/src/routes/enterprise/index.tsx` | ✅ | source | 284 |  |
| `packages/console/app/src/routes/feishu.ts` | ✅ | source | 7 | GET |
| `packages/console/app/src/routes/go/index.css` | ✅ | style | 1195 |  |
| `packages/console/app/src/routes/go/index.tsx` | ✅ | source | 528 |  |
| `packages/console/app/src/routes/index.css` | ✅ | style | 1254 |  |
| `packages/console/app/src/routes/index.tsx` | ✅ | source | 837 |  |
| `packages/console/app/src/routes/legal/privacy-policy/index.css` | ✅ | style | 343 |  |
| `packages/console/app/src/routes/legal/privacy-policy/index.tsx` | ✅ | source | 1516 |  |
| `packages/console/app/src/routes/legal/terms-of-service/index.css` | ✅ | style | 254 |  |
| `packages/console/app/src/routes/legal/terms-of-service/index.tsx` | ✅ | source | 518 |  |
| `packages/console/app/src/routes/openapi.json.ts` | ✅ | source | 7 | GET |
| `packages/console/app/src/routes/s/[id].ts` | ✅ | source | 30 | GET |
| `packages/console/app/src/routes/stripe/webhook.ts` | ✅ | source | 371 | POST |
| `packages/console/app/src/routes/t/[...path].tsx` | ✅ | source | 26 | GET |
| `packages/console/app/src/routes/temp.tsx` | ✅ | source | 179 |  |
| `packages/console/app/src/routes/user-menu.css` | ✅ | style | 18 |  |
| `packages/console/app/src/routes/user-menu.tsx` | ✅ | source | 36 | UserMenu |
| `packages/console/app/src/routes/workspace-picker.css` | ✅ | style | 74 |  |
| `packages/console/app/src/routes/workspace-picker.tsx` | ✅ | source | 124 | WorkspacePicker |
| `packages/console/app/src/routes/workspace.css` | ✅ | style | 107 |  |
| `packages/console/app/src/routes/workspace.tsx` | ✅ | source | 40 |  |
| `packages/console/app/src/routes/workspace/[id].css` | ✅ | style | 337 |  |
| `packages/console/app/src/routes/workspace/[id].tsx` | ✅ | source | 80 |  |
| `packages/console/app/src/routes/workspace/[id]/billing/billing-section.module.css` | ✅ | style | 185 |  |
| `packages/console/app/src/routes/workspace/[id]/billing/billing-section.tsx` | ✅ | source | 266 | BillingSection |
| `packages/console/app/src/routes/workspace/[id]/billing/black-section.module.css` | ✅ | style | 142 |  |
| `packages/console/app/src/routes/workspace/[id]/billing/black-section.tsx` | ✅ | source | 290 | BlackSection |
| `packages/console/app/src/routes/workspace/[id]/billing/black-waitlist-section.module.css` | ✅ | style | 23 |  |
| `packages/console/app/src/routes/workspace/[id]/billing/index.tsx` | ✅ | source | 35 |  |
| `packages/console/app/src/routes/workspace/[id]/billing/monthly-limit-section.module.css` | ✅ | style | 96 |  |
| `packages/console/app/src/routes/workspace/[id]/billing/monthly-limit-section.tsx` | ✅ | source | 145 | MonthlyLimitSection |
| `packages/console/app/src/routes/workspace/[id]/billing/payment-section.module.css` | ✅ | style | 93 |  |
| `packages/console/app/src/routes/workspace/[id]/billing/payment-section.tsx` | ✅ | source | 141 | PaymentSection |
| `packages/console/app/src/routes/workspace/[id]/billing/redeem-section.module.css` | ✅ | style | 61 |  |
| `packages/console/app/src/routes/workspace/[id]/billing/redeem-section.tsx` | ✅ | source | 71 | RedeemSection |
| `packages/console/app/src/routes/workspace/[id]/billing/reload-section.module.css` | ✅ | style | 261 |  |
| `packages/console/app/src/routes/workspace/[id]/billing/reload-section.tsx` | ✅ | source | 220 | ReloadSection |
| `packages/console/app/src/routes/workspace/[id]/go/index.tsx` | ✅ | source | 30 |  |
| `packages/console/app/src/routes/workspace/[id]/go/lite-section.module.css` | ✅ | style | 232 |  |
| `packages/console/app/src/routes/workspace/[id]/go/lite-section.tsx` | ✅ | source | 366 | LiteSection |
| `packages/console/app/src/routes/workspace/[id]/index.tsx` | ✅ | source | 81 |  |
| `packages/console/app/src/routes/workspace/[id]/keys/index.tsx` | ✅ | source | 11 |  |
| `packages/console/app/src/routes/workspace/[id]/keys/key-section.module.css` | ✅ | style | 197 |  |
| `packages/console/app/src/routes/workspace/[id]/keys/key-section.tsx` | ✅ | source | 179 | KeySection |
| `packages/console/app/src/routes/workspace/[id]/members/index.tsx` | ✅ | source | 11 |  |
| `packages/console/app/src/routes/workspace/[id]/members/member-section.module.css` | ✅ | style | 249 |  |
| `packages/console/app/src/routes/workspace/[id]/members/member-section.tsx` | ✅ | source | 368 | MemberSection |
| `packages/console/app/src/routes/workspace/[id]/members/role-dropdown.css` | ✅ | style | 72 |  |
| `packages/console/app/src/routes/workspace/[id]/members/role-dropdown.tsx` | ✅ | source | 45 | RoleDropdown |
| `packages/console/app/src/routes/workspace/[id]/model-section.module.css` | ✅ | style | 173 |  |
| `packages/console/app/src/routes/workspace/[id]/model-section.tsx` | ✅ | source | 192 | ModelSection |
| `packages/console/app/src/routes/workspace/[id]/new-user-section.module.css` | ✅ | style | 143 |  |
| `packages/console/app/src/routes/workspace/[id]/new-user-section.tsx` | ✅ | source | 108 | NewUserSection |
| `packages/console/app/src/routes/workspace/[id]/provider-section.module.css` | ✅ | style | 138 |  |
| `packages/console/app/src/routes/workspace/[id]/provider-section.tsx` | ✅ | source | 199 | ProviderSection |
| `packages/console/app/src/routes/workspace/[id]/settings/index.tsx` | ✅ | source | 11 |  |
| `packages/console/app/src/routes/workspace/[id]/settings/settings-section.module.css` | ✅ | style | 94 |  |
| `packages/console/app/src/routes/workspace/[id]/settings/settings-section.tsx` | ✅ | source | 125 | SettingsSection |
| `packages/console/app/src/routes/workspace/[id]/usage/graph-section.module.css` | ✅ | style | 145 |  |
| `packages/console/app/src/routes/workspace/[id]/usage/graph-section.tsx` | ✅ | source | 556 | GraphSection |
| `packages/console/app/src/routes/workspace/[id]/usage/index.tsx` | ✅ | source | 21 |  |
| `packages/console/app/src/routes/workspace/[id]/usage/usage-section.module.css` | ✅ | style | 185 |  |
| `packages/console/app/src/routes/workspace/[id]/usage/usage-section.tsx` | ✅ | source | 217 | UsageSection |
| `packages/console/app/src/routes/workspace/common.tsx` | ✅ | source | 122 | formatDateForTable |
| `packages/console/app/src/routes/zen/go/v1/chat/completions.ts` | ✅ | source | 12 | POST |
| `packages/console/app/src/routes/zen/go/v1/messages.ts` | ✅ | source | 12 | POST |
| `packages/console/app/src/routes/zen/go/v1/models.ts` | ✅ | source | 12 | OPTIONS |
| `packages/console/app/src/routes/zen/index.css` | ✅ | style | 867 |  |
| `packages/console/app/src/routes/zen/index.tsx` | ✅ | source | 336 |  |
| `packages/console/app/src/routes/zen/util/dataDumper.ts` | ✅ | source | 44 | createDataDumper |
| `packages/console/app/src/routes/zen/util/error.ts` | ✅ | source | 16 | LimitError |
| `packages/console/app/src/routes/zen/util/handler.ts` | ✅ | source | 1104 | handler |
| `packages/console/app/src/routes/zen/util/ipRateLimiter.ts` | ✅ | source | 70 | createRateLimiter |
| `packages/console/app/src/routes/zen/util/keyRateLimiter.ts` | ✅ | source | 39 | createRateLimiter |
| `packages/console/app/src/routes/zen/util/logger.ts` | ✅ | source | 12 | logger |
| `packages/console/app/src/routes/zen/util/modelTpmLimiter.ts` | ✅ | source | 47 | createModelTpmLimiter |
| `packages/console/app/src/routes/zen/util/modelsHandler.ts` | ✅ | source | 31 | buildOptionsResponse |
| `packages/console/app/src/routes/zen/util/provider/anthropic.ts` | ✅ | source | 759 | fromAnthropicRequest |
| `packages/console/app/src/routes/zen/util/provider/google.ts` | ✅ | source | 75 | googleHelper |
| `packages/console/app/src/routes/zen/util/provider/openai-compatible.ts` | ✅ | source | 555 | fromOaCompatibleRequest |
| `packages/console/app/src/routes/zen/util/provider/openai.ts` | ✅ | source | 628 | fromOpenaiRequest |
| `packages/console/app/src/routes/zen/util/provider/provider.ts` | ✅ | source | 228 | buildCostChunk |
| `packages/console/app/src/routes/zen/util/stickyProviderTracker.ts` | ✅ | source | 16 | createStickyTracker |
| `packages/console/app/src/routes/zen/util/trialLimiter.ts` | ✅ | source | 46 | createTrialLimiter |
| `packages/console/app/src/routes/zen/v1/chat/completions.ts` | ✅ | source | 12 | POST |
| `packages/console/app/src/routes/zen/v1/messages.ts` | ✅ | source | 12 | POST |
| `packages/console/app/src/routes/zen/v1/models.ts` | ✅ | source | 34 | OPTIONS |
| `packages/console/app/src/routes/zen/v1/models/[model].ts` | ✅ | source | 14 | POST |
| `packages/console/app/src/routes/zen/v1/responses.ts` | ✅ | source | 12 | POST |
| `packages/console/app/src/style/base.css` | ✅ | style | 21 |  |
| `packages/console/app/src/style/component/button.css` | ✅ | style | 102 |  |
| `packages/console/app/src/style/index.css` | ✅ | style | 8 |  |
| `packages/console/app/src/style/reset.css` | ✅ | style | 76 |  |
| `packages/console/app/src/style/token/color.css` | ✅ | style | 91 |  |
| `packages/console/app/src/style/token/font.css` | ✅ | style | 21 |  |
| `packages/console/app/src/style/token/space.css` | ✅ | style | 46 |  |
| `packages/console/app/sst-env.d.ts` | ✅ | source | 10 |  |
| `packages/console/app/test/rateLimiter.test.ts` | ✅ | test | 19 |  |
| `packages/console/app/tsconfig.json` | ✅ | config | 21 |  |
| `packages/console/app/vite.config.ts` | ✅ | config | 27 |  |
| `packages/console/core/.gitignore` | ✅ | source | 1 |  |
| `packages/console/core/drizzle.config.ts` | ✅ | config | 20 |  |
| `packages/console/core/migrations/20250902065410_fluffy_raza/snapshot.json` | ✅ | source | 967 |  |
| `packages/console/core/migrations/20250903035359_serious_whistler/snapshot.json` | ✅ | source | 967 |  |
| `packages/console/core/migrations/20250911133331_violet_loners/snapshot.json` | ✅ | source | 981 |  |
| `packages/console/core/migrations/20250911141957_dusty_clint_barton/snapshot.json` | ✅ | source | 1001 |  |
| `packages/console/core/migrations/20250911214917_first_mockingbird/snapshot.json` | ✅ | source | 1015 |  |
| `packages/console/core/migrations/20250911231144_jazzy_skrulls/snapshot.json` | ✅ | source | 1015 |  |
| `packages/console/core/migrations/20250912021148_parallel_gauntlet/snapshot.json` | ✅ | source | 1043 |  |
| `packages/console/core/migrations/20250912161749_familiar_nightshade/snapshot.json` | ✅ | source | 1029 |  |
| `packages/console/core/migrations/20250914213824_eminent_ultimatum/snapshot.json` | ✅ | source | 1043 |  |
| `packages/console/core/migrations/20250914222302_redundant_piledriver/snapshot.json` | ✅ | source | 1057 |  |
| `packages/console/core/migrations/20250914232505_needy_sue_storm/snapshot.json` | ✅ | source | 1073 |  |
| `packages/console/core/migrations/20250915150801_freezing_phil_sheldon/snapshot.json` | ✅ | source | 1087 |  |
| `packages/console/core/migrations/20250915172014_bright_photon/snapshot.json` | ✅ | source | 1129 |  |
| `packages/console/core/migrations/20250915172258_absurd_hobgoblin/snapshot.json` | ✅ | source | 1129 |  |
| `packages/console/core/migrations/20250919135159_demonic_princess_powerful/snapshot.json` | ✅ | source | 1143 |  |
| `packages/console/core/migrations/20250921042124_cloudy_revanche/snapshot.json` | ✅ | source | 1129 |  |
| `packages/console/core/migrations/20250923213126_cold_la_nuit/snapshot.json` | ✅ | source | 1143 |  |
| `packages/console/core/migrations/20250924230623_woozy_thaddeus_ross/snapshot.json` | ✅ | source | 1157 |  |
| `packages/console/core/migrations/20250928163425_nervous_iron_lad/snapshot.json` | ✅ | source | 1185 |  |
| `packages/console/core/migrations/20250928235456_dazzling_cable/snapshot.json` | ✅ | source | 1185 |  |
| `packages/console/core/migrations/20250929181457_supreme_jack_power/snapshot.json` | ✅ | source | 1171 |  |
| `packages/console/core/migrations/20250929224703_flawless_clea/snapshot.json` | ✅ | source | 1185 |  |
| `packages/console/core/migrations/20251002175032_nice_dreadnoughts/snapshot.json` | ✅ | source | 1233 |  |
| `packages/console/core/migrations/20251002223020_optimal_paibok/snapshot.json` | ✅ | source | 1265 |  |
| `packages/console/core/migrations/20251003202205_early_black_crow/snapshot.json` | ✅ | source | 1237 |  |
| `packages/console/core/migrations/20251003210411_legal_joseph/snapshot.json` | ✅ | source | 1251 |  |
| `packages/console/core/migrations/20251004030300_numerous_prodigy/snapshot.json` | ✅ | source | 1231 |  |
| `packages/console/core/migrations/20251004045106_hot_wong/snapshot.json` | ✅ | source | 1203 |  |
| `packages/console/core/migrations/20251007024345_careful_cerise/snapshot.json` | ✅ | source | 1203 |  |
| `packages/console/core/migrations/20251007043715_panoramic_harrier/snapshot.json` | ✅ | source | 1245 |  |
| `packages/console/core/migrations/20251007230438_ordinary_ultragirl/snapshot.json` | ✅ | source | 1359 |  |
| `packages/console/core/migrations/20251008161718_outgoing_outlaw_kid/snapshot.json` | ✅ | source | 1487 |  |
| `packages/console/core/migrations/20251009021849_white_doctor_doom/snapshot.json` | ✅ | source | 1501 |  |
| `packages/console/core/migrations/20251016175624_cynical_jack_flag/snapshot.json` | ✅ | source | 1515 |  |
| `packages/console/core/migrations/20251016214520_short_bulldozer/snapshot.json` | ✅ | source | 1637 |  |
| `packages/console/core/migrations/20251017015733_narrow_blindfold/snapshot.json` | ✅ | source | 1623 |  |
| `packages/console/core/migrations/20251017024232_slimy_energizer/snapshot.json` | ✅ | source | 1635 |  |
| `packages/console/core/migrations/20251031163113_messy_jackal/snapshot.json` | ✅ | source | 1663 |  |
| `packages/console/core/migrations/20251125223403_famous_magik/snapshot.json` | ✅ | source | 1743 |  |
| `packages/console/core/migrations/20251228182259_striped_forge/snapshot.json` | ✅ | source | 1867 |  |
| `packages/console/core/migrations/20260105034337_broken_gamora/snapshot.json` | ✅ | source | 1887 |  |
| `packages/console/core/migrations/20260106204919_odd_misty_knight/snapshot.json` | ✅ | source | 1939 |  |
| `packages/console/core/migrations/20260107000117_flat_nightmare/snapshot.json` | ✅ | source | 2037 |  |
| `packages/console/core/migrations/20260107022356_lame_calypso/snapshot.json` | ✅ | source | 2037 |  |
| `packages/console/core/migrations/20260107041522_tiny_captain_midlands/snapshot.json` | ✅ | source | 2037 |  |
| `packages/console/core/migrations/20260107055817_cuddly_diamondback/snapshot.json` | ✅ | source | 2053 |  |
| `packages/console/core/migrations/20260108224422_charming_black_bolt/snapshot.json` | ✅ | source | 2203 |  |
| `packages/console/core/migrations/20260109000245_huge_omega_red/snapshot.json` | ✅ | source | 2153 |  |
| `packages/console/core/migrations/20260109001625_mean_frank_castle/snapshot.json` | ✅ | source | 2153 |  |
| `packages/console/core/migrations/20260109014234_noisy_domino/snapshot.json` | ✅ | source | 2167 |  |
| `packages/console/core/migrations/20260109040130_bumpy_mephistopheles/snapshot.json` | ✅ | source | 2181 |  |
| `packages/console/core/migrations/20260113215232_jazzy_green_goblin/snapshot.json` | ✅ | source | 2195 |  |
| `packages/console/core/migrations/20260113223840_aromatic_agent_zero/snapshot.json` | ✅ | source | 2209 |  |
| `packages/console/core/migrations/20260116213606_gigantic_hardball/snapshot.json` | ✅ | source | 2223 |  |
| `packages/console/core/migrations/20260116224745_numerous_annihilus/snapshot.json` | ✅ | source | 2209 |  |
| `packages/console/core/migrations/20260122190905_moaning_karnak/snapshot.json` | ✅ | source | 2223 |  |
| `packages/console/core/migrations/20260222233442_clever_toxin/snapshot.json` | ✅ | source | 2237 |  |
| `packages/console/core/migrations/20260224043338_nifty_starjammers/snapshot.json` | ✅ | source | 2463 |  |
| `packages/console/core/migrations/20260414235536_lame_wild_child/snapshot.json` | ✅ | source | 2515 |  |
| `packages/console/core/migrations/20260415002256_perpetual_karen_page/snapshot.json` | ✅ | source | 2515 |  |
| `packages/console/core/migrations/20260415002534_far_smasher/snapshot.json` | ✅ | source | 2515 |  |
| `packages/console/core/migrations/20260417071612_tidy_diamondback/snapshot.json` | ✅ | source | 2567 |  |
| `packages/console/core/migrations/20260418195905_shocking_marvel_zombies/snapshot.json` | ✅ | source | 2619 |  |
| `packages/console/core/migrations/20260420184535_aromatic_molten_man/snapshot.json` | ✅ | source | 2671 |  |
| `packages/console/core/migrations/20260420185813_supreme_roxanne_simpson/snapshot.json` | ✅ | source | 2657 |  |
| `packages/console/core/migrations/20260420191234_deep_scarecrow/snapshot.json` | ✅ | source | 2605 |  |
| `packages/console/core/migrations/20260421020842_bizarre_living_tribunal/snapshot.json` | ✅ | source | 2657 |  |
| `packages/console/core/migrations/20260421023950_nebulous_weapon_omega/snapshot.json` | ✅ | source | 2619 |  |
| `packages/console/core/migrations/20260427053132_smiling_puppet_master/snapshot.json` | ✅ | source | 2619 |  |
| `packages/console/core/package.json` | ✅ | source | 52 |  |
| `packages/console/core/script/black-cancel-waitlist.ts` | ✅ | source | 39 |  |
| `packages/console/core/script/black-gift.ts` | ✅ | source | 115 |  |
| `packages/console/core/script/black-onboard-waitlist.ts` | ✅ | source | 38 |  |
| `packages/console/core/script/black-select-workspaces.ts` | ✅ | source | 41 |  |
| `packages/console/core/script/black-stats.ts` | ✅ | source | 312 |  |
| `packages/console/core/script/black-transfer.ts` | ✅ | source | 163 |  |
| `packages/console/core/script/create-coupon.ts` | ✅ | source | 24 |  |
| `packages/console/core/script/credit-workspace.ts` | ✅ | source | 35 |  |
| `packages/console/core/script/disable-reload.ts` | ✅ | source | 34 |  |
| `packages/console/core/script/freeze-workspace.ts` | ✅ | source | 39 |  |
| `packages/console/core/script/lookup-user.ts` | ✅ | source | 386 |  |
| `packages/console/core/script/promote-limits.ts` | ✅ | source | 22 |  |
| `packages/console/core/script/promote-models.ts` | ✅ | source | 33 |  |
| `packages/console/core/script/pull-models.ts` | ✅ | source | 33 |  |
| `packages/console/core/script/reset-db.ts` | ✅ | source | 13 |  |
| `packages/console/core/script/update-limits.ts` | ✅ | source | 28 |  |
| `packages/console/core/script/update-models.ts` | ✅ | source | 43 |  |
| `packages/console/core/src/account.ts` | ✅ | source | 32 |  |
| `packages/console/core/src/actor.ts` | ✅ | source | 98 |  |
| `packages/console/core/src/aws.ts` | ✅ | source | 65 |  |
| `packages/console/core/src/billing.ts` | ✅ | source | 556 |  |
| `packages/console/core/src/black.ts` | ✅ | source | 40 |  |
| `packages/console/core/src/context.ts` | ✅ | source | 21 |  |
| `packages/console/core/src/drizzle/index.ts` | ✅ | source | 85 |  |
| `packages/console/core/src/drizzle/types.ts` | ✅ | source | 33 | ulid |
| `packages/console/core/src/identifier.ts` | ✅ | source | 32 |  |
| `packages/console/core/src/key.ts` | ✅ | source | 92 |  |
| `packages/console/core/src/lite.ts` | ✅ | source | 20 |  |
| `packages/console/core/src/model.ts` | ✅ | source | 228 |  |
| `packages/console/core/src/provider.ts` | ✅ | source | 57 |  |
| `packages/console/core/src/schema/account.sql.ts` | ✅ | source | 11 | AccountTable |
| `packages/console/core/src/schema/auth.sql.ts` | ✅ | source | 20 | AuthProvider |
| `packages/console/core/src/schema/benchmark.sql.ts` | ✅ | source | 14 | BenchmarkTable |
| `packages/console/core/src/schema/billing.sql.ts` | ✅ | source | 145 | BlackPlans |
| `packages/console/core/src/schema/ip.sql.ts` | ✅ | source | 42 | IpTable |
| `packages/console/core/src/schema/key.sql.ts` | ✅ | source | 16 | KeyTable |
| `packages/console/core/src/schema/model.sql.ts` | ✅ | source | 13 | ModelTable |
| `packages/console/core/src/schema/provider.sql.ts` | ✅ | source | 14 | ProviderTable |
| `packages/console/core/src/schema/user.sql.ts` | ✅ | source | 29 | UserRole |
| `packages/console/core/src/schema/workspace.sql.ts` | ✅ | source | 21 | workspaceIndexes |
| `packages/console/core/src/subscription.ts` | ✅ | source | 153 |  |
| `packages/console/core/src/user.ts` | ✅ | source | 226 |  |
| `packages/console/core/src/util/date.ts` | ✅ | source | 38 | getWeekBounds |
| `packages/console/core/src/util/env.cloudflare.ts` | ✅ | source | 1 |  |
| `packages/console/core/src/util/fn.ts` | ✅ | source | 11 | fn |
| `packages/console/core/src/util/log.ts` | ✅ | source | 55 |  |
| `packages/console/core/src/util/memo.ts` | ✅ | source | 18 | memo |
| `packages/console/core/src/util/price.ts` | ✅ | source | 7 | centsToMicroCents |
| `packages/console/core/src/workspace.ts` | ✅ | source | 76 |  |
| `packages/console/core/sst-env.d.ts` | ✅ | source | 299 |  |
| `packages/console/core/test/date.test.ts` | ✅ | test | 76 |  |
| `packages/console/core/test/subscription.test.ts` | ✅ | test | 106 |  |
| `packages/console/core/tsconfig.json` | ✅ | config | 11 |  |
| `packages/console/function/package.json` | ✅ | source | 31 |  |
| `packages/console/function/src/auth.ts` | ✅ | source | 223 | subjects |
| `packages/console/function/src/log-processor.ts` | ✅ | source | 64 |  |
| `packages/console/function/sst-env.d.ts` | ✅ | source | 299 |  |
| `packages/console/function/tsconfig.json` | ✅ | config | 11 |  |
| `packages/console/mail/emails/components.tsx` | ✅ | source | 72 | Text |
| `packages/console/mail/emails/styles.ts` | ✅ | source | 91 | unit |
| `packages/console/mail/emails/templates/InviteEmail.tsx` | ✅ | source | 82 | InviteEmail |
| `packages/console/mail/package.json` | ✅ | source | 22 |  |
| `packages/console/mail/sst-env.d.ts` | ✅ | source | 10 |  |
| `packages/console/resource/package.json` | ✅ | source | 22 |  |
| `packages/console/resource/resource.cloudflare.ts` | ✅ | source | 19 | Resource |
| `packages/console/resource/resource.node.ts` | ✅ | source | 70 | waitUntil |
| `packages/console/resource/sst-env.d.ts` | ✅ | source | 299 |  |
| `packages/console/resource/tsconfig.json` | ✅ | config | 9 |  |
| `packages/containers/README.md` | ✅ | docs | 38 |  |
| `packages/containers/base/Dockerfile` | ✅ | source | 18 |  |
| `packages/containers/bun-node/Dockerfile` | ✅ | source | 24 |  |
| `packages/containers/publish/Dockerfile` | ✅ | source | 10 |  |
| `packages/containers/rust/Dockerfile` | ✅ | source | 13 |  |
| `packages/containers/script/build.ts` | ✅ | source | 77 |  |
| `packages/containers/tauri-linux/Dockerfile` | ✅ | source | 12 |  |
| `packages/containers/tsconfig.json` | ✅ | config | 8 |  |
| `packages/core/package.json` | ✅ | source | 50 |  |
| `packages/core/src/cross-spawn-spawner.ts` | ✅ | source | 505 | make |
| `packages/core/src/effect/logger.ts` | ✅ | source | 73 | logger |
| `packages/core/src/effect/memo-map.ts` | ✅ | source | 3 | memoMap |
| `packages/core/src/effect/observability.ts` | ✅ | source | 107 | resource |
| `packages/core/src/effect/runtime.ts` | ✅ | source | 21 | makeRuntime |
| `packages/core/src/filesystem.ts` | ✅ | source | 236 |  |
| `packages/core/src/flag/flag.ts` | ✅ | source | 107 | Flag |
| `packages/core/src/global.ts` | ✅ | source | 80 | make |
| `packages/core/src/installation/version.ts` | ✅ | source | 8 | InstallationVersion |
| `packages/core/src/npm-config.ts` | ✅ | config | 40 |  |
| `packages/core/src/npm.ts` | ✅ | source | 271 | sanitize |
| `packages/core/src/util/array.ts` | ✅ | source | 10 | findLast |
| `packages/core/src/util/binary.ts` | ✅ | source | 41 |  |
| `packages/core/src/util/effect-flock.ts` | ✅ | source | 283 |  |
| `packages/core/src/util/encode.ts` | ✅ | source | 51 | base64Encode |
| `packages/core/src/util/error.ts` | ✅ | source | 60 |  |
| `packages/core/src/util/flock.ts` | ✅ | source | 358 |  |
| `packages/core/src/util/fn.ts` | ✅ | source | 11 | fn |
| `packages/core/src/util/glob.ts` | ✅ | source | 34 |  |
| `packages/core/src/util/hash.ts` | ✅ | source | 7 |  |
| `packages/core/src/util/identifier.ts` | ✅ | source | 48 |  |
| `packages/core/src/util/iife.ts` | ✅ | source | 3 | iife |
| `packages/core/src/util/lazy.ts` | ✅ | source | 11 | lazy |
| `packages/core/src/util/log.ts` | ✅ | source | 185 | file |
| `packages/core/src/util/module.ts` | ✅ | source | 10 |  |
| `packages/core/src/util/opencode-process.ts` | ✅ | source | 24 | ensureRunID |
| `packages/core/src/util/path.ts` | ✅ | source | 37 | getFilename |
| `packages/core/src/util/retry.ts` | ✅ | source | 42 | retry |
| `packages/core/src/util/slug.ts` | ✅ | source | 74 |  |
| `packages/core/sst-env.d.ts` | ✅ | source | 10 |  |
| `packages/core/test/effect/cross-spawn-spawner.test.ts` | ✅ | test | 423 |  |
| `packages/core/test/effect/observability.test.ts` | ✅ | test | 46 |  |
| `packages/core/test/filesystem/filesystem.test.ts` | ✅ | test | 338 |  |
| `packages/core/test/fixture/effect-flock-worker.ts` | ✅ | test | 60 |  |
| `packages/core/test/fixture/flock-worker.ts` | ✅ | test | 72 |  |
| `packages/core/test/fixture/tmpdir.ts` | ✅ | test | 13 |  |
| `packages/core/test/global.test.ts` | ✅ | test | 16 |  |
| `packages/core/test/lib/effect.ts` | ✅ | test | 53 |  |
| `packages/core/test/npm-config.test.ts` | ✅ | test | 51 |  |
| `packages/core/test/npm.test.ts` | ✅ | test | 91 |  |
| `packages/core/test/util/effect-flock.test.ts` | ✅ | test | 386 |  |
| `packages/core/test/util/flock.test.ts` | ✅ | test | 426 |  |
| `packages/core/tsconfig.json` | ✅ | config | 7 |  |
| `packages/desktop-electron/.gitignore` | ✅ | source | 28 |  |
| `packages/desktop-electron/AGENTS.md` | ✅ | docs | 4 |  |
| `packages/desktop-electron/README.md` | ✅ | docs | 32 |  |
| `packages/desktop-electron/electron-builder.config.ts` | ✅ | config | 116 |  |
| `packages/desktop-electron/electron.vite.config.ts` | ✅ | config | 98 |  |
| `packages/desktop-electron/icons/README.md` | ✅ | docs | 14 |  |
| `packages/desktop-electron/package.json` | ✅ | source | 68 |  |
| `packages/desktop-electron/scripts/copy-bundles.ts` | ✅ | source | 12 |  |
| `packages/desktop-electron/scripts/copy-icons.ts` | ✅ | source | 12 |  |
| `packages/desktop-electron/scripts/finalize-latest-yml.ts` | ✅ | test | 124 |  |
| `packages/desktop-electron/scripts/prebuild.ts` | ✅ | source | 9 |  |
| `packages/desktop-electron/scripts/predev.ts` | ✅ | source | 5 |  |
| `packages/desktop-electron/scripts/prepare.ts` | ✅ | source | 9 |  |
| `packages/desktop-electron/scripts/utils.ts` | ✅ | source | 77 | resolveChannel |
| `packages/desktop-electron/src/main/apps.ts` | ✅ | source | 148 | checkAppExists |
| `packages/desktop-electron/src/main/constants.ts` | ✅ | source | 10 | CHANNEL |
| `packages/desktop-electron/src/main/env.d.ts` | ✅ | source | 29 |  |
| `packages/desktop-electron/src/main/index.ts` | ✅ | source | 452 |  |
| `packages/desktop-electron/src/main/ipc.ts` | ✅ | source | 204 | registerIpcHandlers |
| `packages/desktop-electron/src/main/logging.ts` | ✅ | source | 40 | initLogging |
| `packages/desktop-electron/src/main/markdown.ts` | ✅ | source | 16 | parseMarkdown |
| `packages/desktop-electron/src/main/menu.ts` | ✅ | source | 136 | createMenu |
| `packages/desktop-electron/src/main/migrate.ts` | ✅ | source | 91 | migrate |
| `packages/desktop-electron/src/main/server.ts` | ✅ | source | 101 | getDefaultServerUrl |
| `packages/desktop-electron/src/main/shell-env.test.ts` | ✅ | test | 43 |  |
| `packages/desktop-electron/src/main/shell-env.ts` | ✅ | source | 88 | getUserShell |
| `packages/desktop-electron/src/main/store.ts` | ✅ | source | 17 | getStore |
| `packages/desktop-electron/src/main/windows.ts` | ✅ | source | 206 | setBackgroundColor |
| `packages/desktop-electron/src/preload/index.ts` | ✅ | source | 71 |  |
| `packages/desktop-electron/src/preload/types.ts` | ✅ | source | 79 |  |
| `packages/desktop-electron/src/renderer/cli.ts` | ✅ | source | 12 | installCli |
| `packages/desktop-electron/src/renderer/env.d.ts` | ✅ | source | 10 |  |
| `packages/desktop-electron/src/renderer/html.test.ts` | ✅ | test | 62 |  |
| `packages/desktop-electron/src/renderer/i18n/ar.ts` | ✅ | source | 26 | dict |
| `packages/desktop-electron/src/renderer/i18n/br.ts` | ✅ | source | 27 | dict |
| `packages/desktop-electron/src/renderer/i18n/bs.ts` | ✅ | source | 28 | dict |
| `packages/desktop-electron/src/renderer/i18n/da.ts` | ✅ | source | 28 | dict |
| `packages/desktop-electron/src/renderer/i18n/de.ts` | ✅ | source | 28 | dict |
| `packages/desktop-electron/src/renderer/i18n/en.ts` | ✅ | source | 27 | dict |
| `packages/desktop-electron/src/renderer/i18n/es.ts` | ✅ | source | 27 | dict |
| `packages/desktop-electron/src/renderer/i18n/fr.ts` | ✅ | source | 28 | dict |
| `packages/desktop-electron/src/renderer/i18n/index.ts` | ✅ | source | 188 | t |
| `packages/desktop-electron/src/renderer/i18n/ja.ts` | ✅ | source | 28 | dict |
| `packages/desktop-electron/src/renderer/i18n/ko.ts` | ✅ | source | 27 | dict |
| `packages/desktop-electron/src/renderer/i18n/no.ts` | ✅ | source | 28 | dict |
| `packages/desktop-electron/src/renderer/i18n/pl.ts` | ✅ | source | 28 | dict |
| `packages/desktop-electron/src/renderer/i18n/ru.ts` | ✅ | source | 27 | dict |
| `packages/desktop-electron/src/renderer/i18n/zh.ts` | ✅ | source | 26 | dict |
| `packages/desktop-electron/src/renderer/i18n/zht.ts` | ✅ | source | 26 | dict |
| `packages/desktop-electron/src/renderer/index.tsx` | ✅ | source | 377 |  |
| `packages/desktop-electron/src/renderer/loading.tsx` | ✅ | source | 83 |  |
| `packages/desktop-electron/src/renderer/styles.css` | ✅ | style | 0 |  |
| `packages/desktop-electron/src/renderer/updater.ts` | ✅ | source | 12 | runUpdater |
| `packages/desktop-electron/src/renderer/webview-zoom.ts` | ✅ | source | 38 |  |
| `packages/desktop-electron/sst-env.d.ts` | ✅ | source | 10 |  |
| `packages/desktop-electron/tsconfig.json` | ✅ | config | 23 |  |
| `packages/desktop/.gitignore` | ✅ | source | 24 |  |
| `packages/desktop/AGENTS.md` | ✅ | docs | 4 |  |
| `packages/desktop/README.md` | ✅ | docs | 32 |  |
| `packages/desktop/package.json` | ✅ | source | 46 |  |
| `packages/desktop/scripts/copy-bundles.ts` | ✅ | source | 12 |  |
| `packages/desktop/scripts/finalize-latest-json.ts` | ✅ | test | 164 |  |
| `packages/desktop/scripts/predev.ts` | ✅ | source | 15 |  |
| `packages/desktop/scripts/prepare.ts` | ✅ | source | 20 |  |
| `packages/desktop/scripts/utils.ts` | ✅ | source | 61 | getCurrentSidecar |
| `packages/desktop/src-tauri/.gitignore` | ✅ | source | 9 |  |
| `packages/desktop/src-tauri/Cargo.toml` | ✅ | source | 75 |  |
| `packages/desktop/src-tauri/build.rs` | ✅ | source | 3 |  |
| `packages/desktop/src-tauri/capabilities/default.json` | ✅ | source | 52 |  |
| `packages/desktop/src-tauri/icons/README.md` | ✅ | docs | 11 |  |
| `packages/desktop/src-tauri/src/cli.rs` | ✅ | source | 742 |  |
| `packages/desktop/src-tauri/src/constants.rs` | ✅ | source | 10 |  |
| `packages/desktop/src-tauri/src/lib.rs` | ✅ | source | 601 |  |
| `packages/desktop/src-tauri/src/linux_display.rs` | ✅ | source | 53 |  |
| `packages/desktop/src-tauri/src/linux_windowing.rs` | ✅ | source | 475 |  |
| `packages/desktop/src-tauri/src/logging.rs` | ✅ | source | 76 |  |
| `packages/desktop/src-tauri/src/main.rs` | ✅ | source | 78 |  |
| `packages/desktop/src-tauri/src/markdown.rs` | ✅ | source | 63 |  |
| `packages/desktop/src-tauri/src/os/mod.rs` | ✅ | source | 2 |  |
| `packages/desktop/src-tauri/src/os/windows.rs` | ✅ | source | 463 |  |
| `packages/desktop/src-tauri/src/server.rs` | ✅ | source | 170 |  |
| `packages/desktop/src-tauri/src/window_customizer.rs` | ✅ | source | 46 |  |
| `packages/desktop/src-tauri/src/windows.rs` | ✅ | source | 174 |  |
| `packages/desktop/src-tauri/tauri.beta.conf.json` | ✅ | source | 37 |  |
| `packages/desktop/src-tauri/tauri.conf.json` | ✅ | source | 67 |  |
| `packages/desktop/src-tauri/tauri.prod.conf.json` | ✅ | source | 42 |  |
| `packages/desktop/src/bindings.ts` | ✅ | source | 67 | commands |
| `packages/desktop/src/cli.ts` | ✅ | source | 43 | installCli |
| `packages/desktop/src/entry.tsx` | ✅ | source | 5 |  |
| `packages/desktop/src/env.d.ts` | ✅ | source | 9 |  |
| `packages/desktop/src/i18n/ar.ts` | ✅ | source | 59 | dict |
| `packages/desktop/src/i18n/br.ts` | ✅ | source | 61 | dict |
| `packages/desktop/src/i18n/bs.ts` | ✅ | source | 62 | dict |
| `packages/desktop/src/i18n/da.ts` | ✅ | source | 61 | dict |
| `packages/desktop/src/i18n/de.ts` | ✅ | source | 62 | dict |
| `packages/desktop/src/i18n/en.ts` | ✅ | source | 61 | dict |
| `packages/desktop/src/i18n/es.ts` | ✅ | source | 61 | dict |
| `packages/desktop/src/i18n/fr.ts` | ✅ | source | 62 | dict |
| `packages/desktop/src/i18n/index.ts` | ✅ | source | 192 | t |
| `packages/desktop/src/i18n/ja.ts` | ✅ | source | 62 | dict |
| `packages/desktop/src/i18n/ko.ts` | ✅ | source | 60 | dict |
| `packages/desktop/src/i18n/no.ts` | ✅ | source | 61 | dict |
| `packages/desktop/src/i18n/pl.ts` | ✅ | source | 62 | dict |
| `packages/desktop/src/i18n/ru.ts` | ✅ | source | 61 | dict |
| `packages/desktop/src/i18n/zh.ts` | ✅ | source | 59 | dict |
| `packages/desktop/src/i18n/zht.ts` | ✅ | source | 59 | dict |
| `packages/desktop/src/index.tsx` | ✅ | source | 505 |  |
| `packages/desktop/src/loading.tsx` | ✅ | source | 90 |  |
| `packages/desktop/src/menu.ts` | ✅ | source | 190 | createMenu |
| `packages/desktop/src/styles.css` | ✅ | style | 7 |  |
| `packages/desktop/src/updater.ts` | ✅ | source | 51 | runUpdater |
| `packages/desktop/src/webview-zoom.ts` | ✅ | source | 37 |  |
| `packages/desktop/sst-env.d.ts` | ✅ | source | 10 |  |
| `packages/desktop/tsconfig.json` | ✅ | config | 22 |  |
| `packages/desktop/vite.config.ts` | ✅ | config | 38 |  |
| `packages/docs/README.md` | ✅ | docs | 44 |  |
| `packages/docs/ai-tools/claude-code.mdx` | ✅ | docs | 83 |  |
| `packages/docs/ai-tools/cursor.mdx` | ✅ | docs | 423 |  |
| `packages/docs/ai-tools/windsurf.mdx` | ✅ | docs | 96 |  |
| `packages/docs/development.mdx` | ✅ | docs | 96 |  |
| `packages/docs/docs.json` | ✅ | source | 53 |  |
| `packages/docs/essentials/code.mdx` | ✅ | docs | 35 |  |
| `packages/docs/essentials/images.mdx` | ✅ | docs | 56 |  |
| `packages/docs/essentials/markdown.mdx` | ✅ | docs | 88 |  |
| `packages/docs/essentials/navigation.mdx` | ✅ | docs | 87 |  |
| `packages/docs/essentials/reusable-snippets.mdx` | ✅ | docs | 112 |  |
| `packages/docs/essentials/settings.mdx` | ✅ | docs | 316 |  |
| `packages/docs/index.mdx` | ✅ | docs | 56 |  |
| `packages/docs/quickstart.mdx` | ✅ | docs | 81 |  |
| `packages/docs/snippets/snippet-intro.mdx` | ✅ | docs | 4 |  |
| `packages/enterprise/.gitignore` | ✅ | source | 26 |  |
| `packages/enterprise/README.md` | ✅ | docs | 32 |  |
| `packages/enterprise/package.json` | ✅ | source | 43 |  |
| `packages/enterprise/script/scrap.ts` | ✅ | source | 15 |  |
| `packages/enterprise/src/app.css` | ✅ | style | 1 |  |
| `packages/enterprise/src/app.tsx` | ✅ | source | 94 |  |
| `packages/enterprise/src/core/share.ts` | ✅ | source | 223 |  |
| `packages/enterprise/src/core/storage.ts` | ✅ | source | 129 |  |
| `packages/enterprise/src/entry-client.tsx` | ✅ | source | 4 |  |
| `packages/enterprise/src/entry-server.tsx` | ✅ | source | 39 |  |
| `packages/enterprise/src/global.d.ts` | ✅ | source | 5 |  |
| `packages/enterprise/src/routes/[...404].tsx` | ✅ | source | 25 |  |
| `packages/enterprise/src/routes/api/[...path].ts` | ✅ | source | 155 | GET |
| `packages/enterprise/src/routes/index.tsx` | ✅ | source | 3 |  |
| `packages/enterprise/src/routes/share.tsx` | ✅ | source | 5 |  |
| `packages/enterprise/src/routes/share/[shareID].tsx` | ✅ | source | 397 |  |
| `packages/enterprise/sst-env.d.ts` | ✅ | source | 299 |  |
| `packages/enterprise/test-debug.ts` | ✅ | test | 40 |  |
| `packages/enterprise/test/core/share.test.ts` | ✅ | test | 284 |  |
| `packages/enterprise/test/core/storage.test.ts` | ✅ | test | 64 |  |
| `packages/enterprise/tsconfig.json` | ✅ | config | 20 |  |
| `packages/enterprise/vite.config.ts` | ✅ | config | 36 |  |
| `packages/extensions/zed/extension.toml` | ✅ | source | 36 |  |
| `packages/function/package.json` | ✅ | source | 20 |  |
| `packages/function/src/api.ts` | ✅ | source | 388 |  |
| `packages/function/sst-env.d.ts` | ✅ | source | 299 |  |
| `packages/function/tsconfig.json` | ✅ | config | 9 |  |
| `packages/opencode/.gitignore` | ✅ | source | 10 |  |
| `packages/opencode/AGENTS.md` | ✅ | docs | 137 |  |
| `packages/opencode/BUN_SHELL_MIGRATION_PLAN.md` | ✅ | docs | 136 |  |
| `packages/opencode/Dockerfile` | ✅ | source | 18 |  |
| `packages/opencode/README.md` | ✅ | docs | 15 |  |
| `packages/opencode/bunfig.toml` | ✅ | source | 7 |  |
| `packages/opencode/drizzle.config.ts` | ✅ | config | 10 |  |
| `packages/opencode/migration/20260127222353_familiar_lady_ursula/snapshot.json` | ✅ | source | 796 |  |
| `packages/opencode/migration/20260211171708_add_project_commands/snapshot.json` | ✅ | source | 806 |  |
| `packages/opencode/migration/20260213144116_wakeful_the_professor/snapshot.json` | ✅ | source | 897 |  |
| `packages/opencode/migration/20260225215848_workspace/snapshot.json` | ✅ | source | 959 |  |
| `packages/opencode/migration/20260227213759_add_session_workspace_id/snapshot.json` | ✅ | source | 983 |  |
| `packages/opencode/migration/20260228203230_blue_harpoon/snapshot.json` | ✅ | source | 1102 |  |
| `packages/opencode/migration/20260303231226_add_workspace_fields/snapshot.json` | ✅ | source | 1013 |  |
| `packages/opencode/migration/20260309230000_move_org_to_state/snapshot.json` | ✅ | source | 1156 |  |
| `packages/opencode/migration/20260312043431_session_message_cursor/snapshot.json` | ✅ | source | 1168 |  |
| `packages/opencode/migration/20260323234822_events/snapshot.json` | ✅ | source | 1271 |  |
| `packages/opencode/migration/20260410174513_workspace-name/snapshot.json` | ✅ | source | 1271 |  |
| `packages/opencode/migration/20260413175956_chief_energizer/snapshot.json` | ✅ | source | 1399 |  |
| `packages/opencode/migration/20260423070820_add_icon_url_override/snapshot.json` | ✅ | source | 1409 |  |
| `packages/opencode/migration/20260428004200_add_session_path/snapshot.json` | ✅ | source | 1419 |  |
| `packages/opencode/package.json` | ✅ | source | 180 |  |
| `packages/opencode/parsers-config.ts` | ✅ | config | 290 |  |
| `packages/opencode/script/build-node.ts` | ✅ | source | 62 |  |
| `packages/opencode/script/build.ts` | ✅ | source | 267 |  |
| `packages/opencode/script/check-migrations.ts` | ✅ | source | 16 |  |
| `packages/opencode/script/fix-node-pty.ts` | ✅ | source | 28 |  |
| `packages/opencode/script/generate.ts` | ✅ | source | 23 |  |
| `packages/opencode/script/publish.ts` | ✅ | source | 196 |  |
| `packages/opencode/script/schema.ts` | ✅ | source | 63 |  |
| `packages/opencode/script/time.ts` | ✅ | source | 6 |  |
| `packages/opencode/script/trace-imports.ts` | ✅ | source | 153 |  |
| `packages/opencode/script/upgrade-opentui.ts` | ✅ | source | 64 |  |
| `packages/opencode/scripts/diff-sdk-types.sh` | ✅ | source | 52 |  |
| `packages/opencode/specs/effect/facades.md` | ✅ | docs | 221 |  |
| `packages/opencode/specs/effect/http-api.md` | ✅ | docs | 401 |  |
| `packages/opencode/specs/effect/instance-context.md` | ✅ | docs | 309 |  |
| `packages/opencode/specs/effect/loose-ends.md` | ✅ | docs | 34 |  |
| `packages/opencode/specs/effect/migration.md` | ✅ | docs | 299 |  |
| `packages/opencode/specs/effect/routes.md` | ✅ | docs | 64 |  |
| `packages/opencode/specs/effect/schema.md` | ✅ | docs | 399 |  |
| `packages/opencode/specs/effect/server-package.md` | ✅ | docs | 668 |  |
| `packages/opencode/specs/effect/tools.md` | ✅ | docs | 90 |  |
| `packages/opencode/specs/tui-plugins.md` | ✅ | docs | 433 |  |
| `packages/opencode/specs/v2/api.ts` | ✅ | source | 67 |  |
| `packages/opencode/specs/v2/keymappings.md` | ✅ | docs | 10 |  |
| `packages/opencode/specs/v2/message-shape.md` | ✅ | docs | 136 |  |
| `packages/opencode/src/account/account.sql.ts` | ✅ | source | 39 | AccountTable |
| `packages/opencode/src/account/account.ts` | ✅ | source | 456 | layer |
| `packages/opencode/src/account/repo.ts` | ✅ | source | 166 | layer |
| `packages/opencode/src/account/schema.ts` | ✅ | source | 99 | AccountID |
| `packages/opencode/src/account/url.ts` | ✅ | source | 8 | normalizeServerUrl |
| `packages/opencode/src/acp/README.md` | ✅ | docs | 174 |  |
| `packages/opencode/src/acp/agent.ts` | ✅ | source | 1838 | init |
| `packages/opencode/src/acp/session.ts` | ✅ | source | 116 |  |
| `packages/opencode/src/acp/types.ts` | ✅ | source | 24 |  |
| `packages/opencode/src/agent/agent.ts` | ✅ | source | 413 | Info |
| `packages/opencode/src/audio.d.ts` | ✅ | source | 4 |  |
| `packages/opencode/src/auth/index.ts` | ✅ | source | 98 | OAUTH_DUMMY_KEY |
| `packages/opencode/src/bus/bus-event.ts` | ✅ | source | 49 | define |
| `packages/opencode/src/bus/global.ts` | ✅ | source | 12 | GlobalBus |
| `packages/opencode/src/bus/index.ts` | ✅ | source | 188 | publish |
| `packages/opencode/src/cli/bootstrap.ts` | ✅ | source | 18 | bootstrap |
| `packages/opencode/src/cli/cmd/account.ts` | ✅ | source | 258 | formatAccountLabel |
| `packages/opencode/src/cli/cmd/acp.ts` | ✅ | source | 70 | AcpCommand |
| `packages/opencode/src/cli/cmd/agent.ts` | ✅ | source | 264 | AgentCommand |
| `packages/opencode/src/cli/cmd/cmd.ts` | ✅ | source | 7 | cmd |
| `packages/opencode/src/cli/cmd/db.ts` | ✅ | source | 120 | DbCommand |
| `packages/opencode/src/cli/cmd/debug/agent.ts` | ✅ | source | 192 | AgentCommand |
| `packages/opencode/src/cli/cmd/debug/config.ts` | ✅ | config | 17 |  |
| `packages/opencode/src/cli/cmd/debug/file.ts` | ✅ | source | 100 | FileCommand |
| `packages/opencode/src/cli/cmd/debug/index.ts` | ✅ | source | 50 | DebugCommand |
| `packages/opencode/src/cli/cmd/debug/lsp.ts` | ✅ | source | 60 | LSPCommand |
| `packages/opencode/src/cli/cmd/debug/ripgrep.ts` | ✅ | source | 105 | RipgrepCommand |
| `packages/opencode/src/cli/cmd/debug/scrap.ts` | ✅ | source | 16 | ScrapCommand |
| `packages/opencode/src/cli/cmd/debug/skill.ts` | ✅ | source | 23 | SkillCommand |
| `packages/opencode/src/cli/cmd/debug/snapshot.ts` | ✅ | source | 53 | SnapshotCommand |
| `packages/opencode/src/cli/cmd/debug/startup.ts` | ✅ | source | 11 | StartupCommand |
| `packages/opencode/src/cli/cmd/export.ts` | ✅ | source | 303 | ExportCommand |
| `packages/opencode/src/cli/cmd/generate.ts` | ✅ | source | 61 | GenerateCommand |
| `packages/opencode/src/cli/cmd/github.ts` | ✅ | source | 1649 | parseGitHubRemote |
| `packages/opencode/src/cli/cmd/import.ts` | ✅ | source | 212 | parseShareUrl |
| `packages/opencode/src/cli/cmd/mcp.ts` | ✅ | source | 798 | McpCommand |
| `packages/opencode/src/cli/cmd/models.ts` | ✅ | source | 88 | ModelsCommand |
| `packages/opencode/src/cli/cmd/plug.ts` | ✅ | source | 233 | createPlugTask |
| `packages/opencode/src/cli/cmd/pr.ts` | ✅ | source | 138 | PrCommand |
| `packages/opencode/src/cli/cmd/providers.ts` | ✅ | source | 526 | resolvePluginProviders |
| `packages/opencode/src/cli/cmd/run.ts` | ✅ | source | 672 | RunCommand |
| `packages/opencode/src/cli/cmd/serve.ts` | ✅ | source | 21 | ServeCommand |
| `packages/opencode/src/cli/cmd/session.ts` | ✅ | source | 162 | SessionCommand |
| `packages/opencode/src/cli/cmd/stats.ts` | ✅ | source | 413 | aggregateSessionStats |
| `packages/opencode/src/cli/cmd/tui/app.tsx` | ✅ | source | 909 | tui |
| `packages/opencode/src/cli/cmd/tui/attach.ts` | ✅ | source | 99 | AttachCommand |
| `packages/opencode/src/cli/cmd/tui/component/bg-pulse.tsx` | ✅ | source | 130 | BgPulse |
| `packages/opencode/src/cli/cmd/tui/component/border.tsx` | ✅ | source | 21 | EmptyBorder |
| `packages/opencode/src/cli/cmd/tui/component/dialog-agent.tsx` | ✅ | source | 31 | DialogAgent |
| `packages/opencode/src/cli/cmd/tui/component/dialog-command.tsx` | ✅ | source | 172 | useCommandDialog |
| `packages/opencode/src/cli/cmd/tui/component/dialog-console-org.tsx` | ✅ | source | 103 | DialogConsoleOrg |
| `packages/opencode/src/cli/cmd/tui/component/dialog-go-upsell.tsx` | ✅ | source | 159 | DialogGoUpsell |
| `packages/opencode/src/cli/cmd/tui/component/dialog-mcp.tsx` | ✅ | source | 86 | DialogMcp |
| `packages/opencode/src/cli/cmd/tui/component/dialog-model.tsx` | ✅ | source | 177 | DialogModel |
| `packages/opencode/src/cli/cmd/tui/component/dialog-provider.tsx` | ✅ | source | 362 | createDialogProviderOptions |
| `packages/opencode/src/cli/cmd/tui/component/dialog-session-delete-failed.tsx` | ✅ | source | 103 | DialogSessionDeleteFailed |
| `packages/opencode/src/cli/cmd/tui/component/dialog-session-list.tsx` | ✅ | source | 265 | DialogSessionList |
| `packages/opencode/src/cli/cmd/tui/component/dialog-session-rename.tsx` | ✅ | source | 31 | DialogSessionRename |
| `packages/opencode/src/cli/cmd/tui/component/dialog-skill.tsx` | ✅ | source | 36 | DialogSkill |
| `packages/opencode/src/cli/cmd/tui/component/dialog-stash.tsx` | ✅ | source | 87 | DialogStash |
| `packages/opencode/src/cli/cmd/tui/component/dialog-status.tsx` | ✅ | source | 168 | DialogStatus |
| `packages/opencode/src/cli/cmd/tui/component/dialog-tag.tsx` | ✅ | source | 44 | DialogTag |
| `packages/opencode/src/cli/cmd/tui/component/dialog-theme-list.tsx` | ✅ | source | 50 | DialogThemeList |
| `packages/opencode/src/cli/cmd/tui/component/dialog-variant.tsx` | ✅ | source | 39 | DialogVariant |
| `packages/opencode/src/cli/cmd/tui/component/dialog-workspace-create.tsx` | ✅ | source | 200 | openWorkspaceSession |
| `packages/opencode/src/cli/cmd/tui/component/dialog-workspace-unavailable.tsx` | ✅ | source | 81 | DialogWorkspaceUnavailable |
| `packages/opencode/src/cli/cmd/tui/component/error-component.tsx` | ✅ | source | 92 | ErrorComponent |
| `packages/opencode/src/cli/cmd/tui/component/logo.tsx` | ✅ | source | 896 | Logo |
| `packages/opencode/src/cli/cmd/tui/component/plugin-route-missing.tsx` | ✅ | source | 14 | PluginRouteMissing |
| `packages/opencode/src/cli/cmd/tui/component/prompt/autocomplete.tsx` | ✅ | source | 722 | Autocomplete |
| `packages/opencode/src/cli/cmd/tui/component/prompt/cwd.ts` | ✅ | source | 0 |  |
| `packages/opencode/src/cli/cmd/tui/component/prompt/frecency.tsx` | ✅ | source | 90 |  |
| `packages/opencode/src/cli/cmd/tui/component/prompt/history.tsx` | ✅ | source | 108 |  |
| `packages/opencode/src/cli/cmd/tui/component/prompt/index.tsx` | ✅ | source | 1477 | Prompt |
| `packages/opencode/src/cli/cmd/tui/component/prompt/part.ts` | ✅ | source | 16 | strip |
| `packages/opencode/src/cli/cmd/tui/component/prompt/stash.tsx` | ✅ | source | 101 |  |
| `packages/opencode/src/cli/cmd/tui/component/spinner.tsx` | ✅ | source | 24 | Spinner |
| `packages/opencode/src/cli/cmd/tui/component/startup-loading.tsx` | ✅ | source | 63 | StartupLoading |
| `packages/opencode/src/cli/cmd/tui/component/textarea-keybindings.ts` | ✅ | source | 73 | useTextareaKeybindings |
| `packages/opencode/src/cli/cmd/tui/component/todo-item.tsx` | ✅ | source | 32 | TodoItem |
| `packages/opencode/src/cli/cmd/tui/component/use-connected.tsx` | ✅ | source | 9 | useConnected |
| `packages/opencode/src/cli/cmd/tui/config/cwd.ts` | ✅ | config | 5 |  |
| `packages/opencode/src/cli/cmd/tui/config/tui-migrate.ts` | ✅ | config | 152 |  |
| `packages/opencode/src/cli/cmd/tui/config/tui-schema.ts` | ✅ | config | 38 |  |
| `packages/opencode/src/cli/cmd/tui/config/tui.ts` | ✅ | config | 220 |  |
| `packages/opencode/src/cli/cmd/tui/context/args.tsx` | ✅ | source | 15 |  |
| `packages/opencode/src/cli/cmd/tui/context/directory.ts` | ✅ | source | 15 | useDirectory |
| `packages/opencode/src/cli/cmd/tui/context/editor-zed.ts` | ✅ | source | 280 | resolveZedSelection |
| `packages/opencode/src/cli/cmd/tui/context/editor.ts` | ✅ | source | 424 | editorSelectionKey |
| `packages/opencode/src/cli/cmd/tui/context/event.ts` | ✅ | source | 45 | useEvent |
| `packages/opencode/src/cli/cmd/tui/context/exit.tsx` | ✅ | source | 60 |  |
| `packages/opencode/src/cli/cmd/tui/context/helper.tsx` | ✅ | source | 25 | createSimpleContext |
| `packages/opencode/src/cli/cmd/tui/context/keybind.tsx` | ✅ | source | 105 |  |
| `packages/opencode/src/cli/cmd/tui/context/kv.tsx` | ✅ | source | 76 |  |
| `packages/opencode/src/cli/cmd/tui/context/local.tsx` | ✅ | source | 426 | parseModel |
| `packages/opencode/src/cli/cmd/tui/context/plugin-keybinds.ts` | ✅ | source | 41 | createPluginKeybind |
| `packages/opencode/src/cli/cmd/tui/context/project.tsx` | ✅ | source | 109 |  |
| `packages/opencode/src/cli/cmd/tui/context/prompt.tsx` | ✅ | source | 18 |  |
| `packages/opencode/src/cli/cmd/tui/context/route.tsx` | ✅ | source | 52 | useRouteData |
| `packages/opencode/src/cli/cmd/tui/context/sdk.tsx` | ✅ | source | 142 |  |
| `packages/opencode/src/cli/cmd/tui/context/sync.tsx` | ✅ | source | 543 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme.tsx` | ✅ | source | 1243 | selectedForeground |
| `packages/opencode/src/cli/cmd/tui/context/theme/aura.json` | ✅ | source | 69 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/ayu.json` | ✅ | source | 80 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/carbonfox.json` | ✅ | source | 248 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/catppuccin-frappe.json` | ✅ | source | 230 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/catppuccin-macchiato.json` | ✅ | source | 230 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/catppuccin.json` | ✅ | source | 112 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/cobalt2.json` | ✅ | source | 225 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/cursor.json` | ✅ | source | 249 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/dracula.json` | ✅ | source | 219 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/everforest.json` | ✅ | source | 241 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/flexoki.json` | ✅ | source | 237 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/github.json` | ✅ | source | 233 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/gruvbox.json` | ✅ | source | 242 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/kanagawa.json` | ✅ | source | 77 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/lucent-orng.json` | ✅ | source | 234 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/material.json` | ✅ | source | 235 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/matrix.json` | ✅ | source | 77 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/mercury.json` | ✅ | source | 252 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/monokai.json` | ✅ | source | 221 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/nightowl.json` | ✅ | source | 221 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/nord.json` | ✅ | source | 223 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/one-dark.json` | ✅ | source | 84 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/opencode.json` | ✅ | source | 245 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/orng.json` | ✅ | source | 249 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/osaka-jade.json` | ✅ | source | 93 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/palenight.json` | ✅ | source | 222 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/rosepine.json` | ✅ | source | 234 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/solarized.json` | ✅ | source | 223 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/synthwave84.json` | ✅ | source | 226 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/tokyonight.json` | ✅ | source | 243 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/vercel.json` | ✅ | source | 245 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/vesper.json` | ✅ | source | 218 |  |
| `packages/opencode/src/cli/cmd/tui/context/theme/zenburn.json` | ✅ | source | 223 |  |
| `packages/opencode/src/cli/cmd/tui/context/tui-config.tsx` | ✅ | config | 9 |  |
| `packages/opencode/src/cli/cmd/tui/event.ts` | ✅ | source | 53 | TuiEvent |
| `packages/opencode/src/cli/cmd/tui/feature-plugins/home/footer.tsx` | ✅ | source | 93 |  |
| `packages/opencode/src/cli/cmd/tui/feature-plugins/home/tips-view.tsx` | ✅ | source | 157 | Tips |
| `packages/opencode/src/cli/cmd/tui/feature-plugins/home/tips.tsx` | ✅ | source | 55 |  |
| `packages/opencode/src/cli/cmd/tui/feature-plugins/sidebar/context.tsx` | ✅ | source | 63 |  |
| `packages/opencode/src/cli/cmd/tui/feature-plugins/sidebar/files.tsx` | ✅ | source | 62 |  |
| `packages/opencode/src/cli/cmd/tui/feature-plugins/sidebar/footer.tsx` | ✅ | source | 93 |  |
| `packages/opencode/src/cli/cmd/tui/feature-plugins/sidebar/lsp.tsx` | ✅ | source | 66 |  |
| `packages/opencode/src/cli/cmd/tui/feature-plugins/sidebar/mcp.tsx` | ✅ | source | 96 |  |
| `packages/opencode/src/cli/cmd/tui/feature-plugins/sidebar/todo.tsx` | ✅ | source | 48 |  |
| `packages/opencode/src/cli/cmd/tui/feature-plugins/system/plugins.tsx` | ✅ | source | 270 |  |
| `packages/opencode/src/cli/cmd/tui/layer.ts` | ✅ | source | 6 | CliLayer |
| `packages/opencode/src/cli/cmd/tui/plugin/api.tsx` | ✅ | source | 390 | createTuiApi |
| `packages/opencode/src/cli/cmd/tui/plugin/internal.ts` | ✅ | source | 27 | INTERNAL_TUI_PLUGINS |
| `packages/opencode/src/cli/cmd/tui/plugin/runtime.ts` | ✅ | source | 1030 | init |
| `packages/opencode/src/cli/cmd/tui/plugin/slots.tsx` | ✅ | source | 60 | setupSlots |
| `packages/opencode/src/cli/cmd/tui/routes/home.tsx` | ✅ | source | 90 | Home |
| `packages/opencode/src/cli/cmd/tui/routes/session/dialog-fork-from-timeline.tsx` | ✅ | source | 76 | DialogForkFromTimeline |
| `packages/opencode/src/cli/cmd/tui/routes/session/dialog-message.tsx` | ✅ | source | 108 | DialogMessage |
| `packages/opencode/src/cli/cmd/tui/routes/session/dialog-subagent.tsx` | ✅ | source | 26 | DialogSubagent |
| `packages/opencode/src/cli/cmd/tui/routes/session/dialog-timeline.tsx` | ✅ | source | 47 | DialogTimeline |
| `packages/opencode/src/cli/cmd/tui/routes/session/footer.tsx` | ✅ | source | 91 | Footer |
| `packages/opencode/src/cli/cmd/tui/routes/session/index.tsx` | ✅ | source | 2271 | Session |
| `packages/opencode/src/cli/cmd/tui/routes/session/permission.tsx` | ✅ | source | 682 | PermissionPrompt |
| `packages/opencode/src/cli/cmd/tui/routes/session/question.tsx` | ✅ | source | 468 | QuestionPrompt |
| `packages/opencode/src/cli/cmd/tui/routes/session/sidebar.tsx` | ✅ | source | 97 | Sidebar |
| `packages/opencode/src/cli/cmd/tui/routes/session/subagent-footer.tsx` | ✅ | source | 131 | SubagentFooter |
| `packages/opencode/src/cli/cmd/tui/thread.ts` | ✅ | source | 261 | resolveThreadDirectory |
| `packages/opencode/src/cli/cmd/tui/ui/dialog-alert.tsx` | ✅ | source | 61 | DialogAlert |
| `packages/opencode/src/cli/cmd/tui/ui/dialog-confirm.tsx` | ✅ | source | 91 | DialogConfirm |
| `packages/opencode/src/cli/cmd/tui/ui/dialog-export-options.tsx` | ✅ | source | 213 | DialogExportOptions |
| `packages/opencode/src/cli/cmd/tui/ui/dialog-help.tsx` | ✅ | source | 42 | DialogHelp |
| `packages/opencode/src/cli/cmd/tui/ui/dialog-prompt.tsx` | ✅ | source | 117 | DialogPrompt |
| `packages/opencode/src/cli/cmd/tui/ui/dialog-select.tsx` | ✅ | source | 448 | DialogSelect |
| `packages/opencode/src/cli/cmd/tui/ui/dialog.tsx` | ✅ | source | 192 | Dialog |
| `packages/opencode/src/cli/cmd/tui/ui/link.tsx` | ✅ | source | 28 | Link |
| `packages/opencode/src/cli/cmd/tui/ui/spinner.ts` | ✅ | source | 368 | deriveTrailColors |
| `packages/opencode/src/cli/cmd/tui/ui/toast.tsx` | ✅ | source | 102 | Toast |
| `packages/opencode/src/cli/cmd/tui/util/clipboard.ts` | ✅ | source | 205 | read |
| `packages/opencode/src/cli/cmd/tui/util/editor.ts` | ✅ | source | 37 | open |
| `packages/opencode/src/cli/cmd/tui/util/model.ts` | ✅ | source | 23 | index |
| `packages/opencode/src/cli/cmd/tui/util/provider-origin.ts` | ✅ | source | 7 | isConsoleManagedProvider |
| `packages/opencode/src/cli/cmd/tui/util/revert-diff.ts` | ✅ | source | 18 | getRevertDiffFiles |
| `packages/opencode/src/cli/cmd/tui/util/scroll.ts` | ✅ | source | 23 | getScrollAcceleration |
| `packages/opencode/src/cli/cmd/tui/util/selection.ts` | ✅ | source | 25 | copy |
| `packages/opencode/src/cli/cmd/tui/util/signal.ts` | ✅ | source | 41 | createDebouncedSignal |
| `packages/opencode/src/cli/cmd/tui/util/sound.ts` | ✅ | source | 156 | start |
| `packages/opencode/src/cli/cmd/tui/util/transcript.ts` | ✅ | source | 112 | formatTranscript |
| `packages/opencode/src/cli/cmd/tui/validate-session.ts` | ✅ | source | 24 | validateSession |
| `packages/opencode/src/cli/cmd/tui/win32.ts` | ✅ | source | 130 | win32DisableProcessedInput |
| `packages/opencode/src/cli/cmd/tui/worker.ts` | ✅ | source | 104 | rpc |
| `packages/opencode/src/cli/cmd/uninstall.ts` | ✅ | source | 353 | UninstallCommand |
| `packages/opencode/src/cli/cmd/upgrade.ts` | ✅ | source | 74 | UpgradeCommand |
| `packages/opencode/src/cli/cmd/web.ts` | ✅ | source | 81 | WebCommand |
| `packages/opencode/src/cli/effect/prompt.ts` | ✅ | source | 25 | intro |
| `packages/opencode/src/cli/error.ts` | ✅ | source | 82 | FormatError |
| `packages/opencode/src/cli/heap.ts` | ✅ | source | 59 | start |
| `packages/opencode/src/cli/logo.ts` | ✅ | source | 11 | logo |
| `packages/opencode/src/cli/network.ts` | ✅ | source | 62 | withNetworkOptions |
| `packages/opencode/src/cli/ui.ts` | ✅ | source | 133 | println |
| `packages/opencode/src/cli/upgrade.ts` | ✅ | source | 33 | upgrade |
| `packages/opencode/src/command/index.ts` | ✅ | source | 187 | hints |
| `packages/opencode/src/config/agent.ts` | ✅ | config | 175 |  |
| `packages/opencode/src/config/command.ts` | ✅ | config | 62 |  |
| `packages/opencode/src/config/config.ts` | ✅ | config | 807 |  |
| `packages/opencode/src/config/console-state.ts` | ✅ | config | 17 |  |
| `packages/opencode/src/config/entry-name.ts` | ✅ | config | 16 |  |
| `packages/opencode/src/config/error.ts` | ✅ | config | 21 |  |
| `packages/opencode/src/config/formatter.ts` | ✅ | config | 17 |  |
| `packages/opencode/src/config/keybinds.ts` | ✅ | config | 127 |  |
| `packages/opencode/src/config/layout.ts` | ✅ | config | 10 |  |
| `packages/opencode/src/config/lsp.ts` | ✅ | config | 45 |  |
| `packages/opencode/src/config/managed.ts` | ✅ | config | 71 |  |
| `packages/opencode/src/config/markdown.ts` | ✅ | config | 99 |  |
| `packages/opencode/src/config/mcp.ts` | ✅ | config | 65 |  |
| `packages/opencode/src/config/model-id.ts` | ✅ | config | 14 |  |
| `packages/opencode/src/config/parse.ts` | ✅ | config | 88 |  |
| `packages/opencode/src/config/paths.ts` | ✅ | config | 55 |  |
| `packages/opencode/src/config/permission.ts` | ✅ | config | 70 |  |
| `packages/opencode/src/config/plugin.ts` | ✅ | config | 88 |  |
| `packages/opencode/src/config/provider.ts` | ✅ | config | 113 |  |
| `packages/opencode/src/config/server.ts` | ✅ | config | 22 |  |
| `packages/opencode/src/config/skills.ts` | ✅ | config | 16 |  |
| `packages/opencode/src/config/variable.ts` | ✅ | config | 90 |  |
| `packages/opencode/src/control-plane/adapters/index.ts` | ✅ | source | 45 | getAdapter |
| `packages/opencode/src/control-plane/adapters/worktree.ts` | ✅ | source | 54 | WorktreeAdapter |
| `packages/opencode/src/control-plane/dev/README.md` | ✅ | docs | 19 |  |
| `packages/opencode/src/control-plane/dev/debug-workspace-plugin.ts` | ✅ | source | 73 | DebugWorkspacePlugin |
| `packages/opencode/src/control-plane/schema.ts` | ✅ | source | 18 | WorkspaceID |
| `packages/opencode/src/control-plane/types.ts` | ✅ | source | 45 | WorkspaceInfo |
| `packages/opencode/src/control-plane/util.ts` | ✅ | source | 39 | waitEvent |
| `packages/opencode/src/control-plane/workspace-context.ts` | ✅ | source | 26 | WorkspaceContext |
| `packages/opencode/src/control-plane/workspace.sql.ts` | ✅ | source | 17 | WorkspaceTable |
| `packages/opencode/src/control-plane/workspace.ts` | ✅ | source | 875 | Info |
| `packages/opencode/src/effect/app-runtime.ts` | ✅ | source | 125 | AppLayer |
| `packages/opencode/src/effect/bootstrap-runtime.ts` | ✅ | source | 29 | BootstrapLayer |
| `packages/opencode/src/effect/bridge.ts` | ✅ | source | 59 | make |
| `packages/opencode/src/effect/config-service.ts` | ✅ | config | 67 |  |
| `packages/opencode/src/effect/instance-ref.ts` | ✅ | source | 11 | InstanceRef |
| `packages/opencode/src/effect/instance-registry.ts` | ✅ | source | 12 | registerDisposer |
| `packages/opencode/src/effect/instance-state.ts` | ✅ | source | 83 | bind |
| `packages/opencode/src/effect/run-service.ts` | ✅ | source | 52 | attachWith |
| `packages/opencode/src/effect/runner.ts` | ✅ | source | 222 | make |
| `packages/opencode/src/effect/service-use.ts` | ✅ | source | 38 | serviceUse |
| `packages/opencode/src/env/index.ts` | ✅ | source | 37 | layer |
| `packages/opencode/src/file/ignore.ts` | ✅ | source | 81 | match |
| `packages/opencode/src/file/index.ts` | ✅ | source | 658 | Info |
| `packages/opencode/src/file/protected.ts` | ✅ | source | 59 | names |
| `packages/opencode/src/file/ripgrep.ts` | ✅ | source | 482 | SearchMatch |
| `packages/opencode/src/file/watcher.ts` | ✅ | source | 159 | Event |
| `packages/opencode/src/format/formatter.ts` | ✅ | source | 403 | gofmt |
| `packages/opencode/src/format/index.ts` | ✅ | source | 207 | Status |
| `packages/opencode/src/git/index.ts` | ✅ | source | 260 | layer |
| `packages/opencode/src/id/id.ts` | ✅ | source | 86 | schema |
| `packages/opencode/src/ide/index.ts` | ✅ | source | 74 | ide |
| `packages/opencode/src/index.ts` | ✅ | source | 247 |  |
| `packages/opencode/src/installation/index.ts` | ✅ | source | 339 | getReleaseType |
| `packages/opencode/src/lsp/client.ts` | ✅ | source | 697 | create |
| `packages/opencode/src/lsp/diagnostic.ts` | ✅ | source | 29 | pretty |
| `packages/opencode/src/lsp/language.ts` | ✅ | source | 121 | LANGUAGE_EXTENSIONS |
| `packages/opencode/src/lsp/launch.ts` | ✅ | source | 21 | spawn |
| `packages/opencode/src/lsp/lsp.ts` | ✅ | source | 522 | Event |
| `packages/opencode/src/lsp/server.ts` | ✅ | source | 2064 | Deno |
| `packages/opencode/src/mcp/auth.ts` | ✅ | source | 144 | Tokens |
| `packages/opencode/src/mcp/index.ts` | ✅ | source | 931 | Resource |
| `packages/opencode/src/mcp/oauth-callback.ts` | ✅ | source | 232 | ensureRunning |
| `packages/opencode/src/mcp/oauth-provider.ts` | ✅ | source | 214 | parseRedirectUri |
| `packages/opencode/src/node.ts` | ✅ | source | 6 |  |
| `packages/opencode/src/patch/index.ts` | ✅ | source | 684 | parsePatch |
| `packages/opencode/src/permission/arity.ts` | ✅ | source | 163 | prefix |
| `packages/opencode/src/permission/evaluate.ts` | ✅ | source | 15 | evaluate |
| `packages/opencode/src/permission/index.ts` | ✅ | source | 325 | evaluate |
| `packages/opencode/src/permission/schema.ts` | ✅ | source | 16 |  |
| `packages/opencode/src/plugin/azure.ts` | ✅ | source | 26 | AzureAuthPlugin |
| `packages/opencode/src/plugin/cloudflare.ts` | ✅ | source | 76 | CloudflareWorkersAuthPlugin |
| `packages/opencode/src/plugin/codex.ts` | ✅ | source | 615 | parseJwtClaims |
| `packages/opencode/src/plugin/github-copilot/copilot.ts` | ✅ | source | 394 | CopilotAuthPlugin |
| `packages/opencode/src/plugin/github-copilot/models.ts` | ✅ | source | 195 | get |
| `packages/opencode/src/plugin/index.ts` | ✅ | source | 291 | layer |
| `packages/opencode/src/plugin/install.ts` | ✅ | source | 439 | installPlugin |
| `packages/opencode/src/plugin/loader.ts` | ✅ | source | 216 |  |
| `packages/opencode/src/plugin/meta.ts` | ✅ | source | 188 | touchMany |
| `packages/opencode/src/plugin/shared.ts` | ✅ | source | 323 | isDeprecatedPlugin |
| `packages/opencode/src/project/bootstrap.ts` | ✅ | source | 44 | InstanceBootstrap |
| `packages/opencode/src/project/instance.ts` | ✅ | source | 190 | Instance |
| `packages/opencode/src/project/project.sql.ts` | ✅ | source | 17 | ProjectTable |
| `packages/opencode/src/project/project.ts` | ✅ | source | 513 | fromRow |
| `packages/opencode/src/project/schema.ts` | ✅ | source | 15 | ProjectID |
| `packages/opencode/src/project/vcs.ts` | ✅ | source | 226 | Mode |
| `packages/opencode/src/provider/auth.ts` | ✅ | source | 228 | Methods |
| `packages/opencode/src/provider/error.ts` | ✅ | source | 203 | parseStreamError |
| `packages/opencode/src/provider/models.ts` | ✅ | source | 176 | get |
| `packages/opencode/src/provider/provider.ts` | ✅ | source | 1756 | defaultModelIDs |
| `packages/opencode/src/provider/schema.ts` | ✅ | source | 36 | ProviderID |
| `packages/opencode/src/provider/sdk/copilot/README.md` | ✅ | docs | 5 |  |
| `packages/opencode/src/provider/sdk/copilot/chat/convert-to-openai-compatible-chat-messages.ts` | ✅ | source | 170 | convertToOpenAICompatibleChatMessages |
| `packages/opencode/src/provider/sdk/copilot/chat/get-response-metadata.ts` | ✅ | source | 15 | getResponseMetadata |
| `packages/opencode/src/provider/sdk/copilot/chat/map-openai-compatible-finish-reason.ts` | ✅ | source | 19 | mapOpenAICompatibleFinishReason |
| `packages/opencode/src/provider/sdk/copilot/chat/openai-compatible-api-types.ts` | ✅ | source | 64 |  |
| `packages/opencode/src/provider/sdk/copilot/chat/openai-compatible-chat-language-model.ts` | ✅ | source | 815 |  |
| `packages/opencode/src/provider/sdk/copilot/chat/openai-compatible-chat-options.ts` | ✅ | source | 28 | openaiCompatibleProviderOptions |
| `packages/opencode/src/provider/sdk/copilot/chat/openai-compatible-metadata-extractor.ts` | ✅ | source | 44 |  |
| `packages/opencode/src/provider/sdk/copilot/chat/openai-compatible-prepare-tools.ts` | ✅ | source | 83 | prepareTools |
| `packages/opencode/src/provider/sdk/copilot/copilot-provider.ts` | ✅ | source | 100 | createOpenaiCompatible |
| `packages/opencode/src/provider/sdk/copilot/openai-compatible-error.ts` | ✅ | source | 27 | openaiCompatibleErrorDataSchema |
| `packages/opencode/src/provider/sdk/copilot/responses/convert-to-openai-responses-input.ts` | ✅ | source | 335 | convertToOpenAIResponsesInput |
| `packages/opencode/src/provider/sdk/copilot/responses/map-openai-responses-finish-reason.ts` | ✅ | source | 22 | mapOpenAIResponseFinishReason |
| `packages/opencode/src/provider/sdk/copilot/responses/openai-config.ts` | ✅ | config | 18 |  |
| `packages/opencode/src/provider/sdk/copilot/responses/openai-error.ts` | ✅ | source | 22 | openaiErrorDataSchema |
| `packages/opencode/src/provider/sdk/copilot/responses/openai-responses-api-types.ts` | ✅ | source | 214 |  |
| `packages/opencode/src/provider/sdk/copilot/responses/openai-responses-language-model.ts` | ✅ | source | 1770 |  |
| `packages/opencode/src/provider/sdk/copilot/responses/openai-responses-prepare-tools.ts` | ✅ | source | 173 | prepareResponsesTools |
| `packages/opencode/src/provider/sdk/copilot/responses/openai-responses-settings.ts` | ✅ | source | 1 |  |
| `packages/opencode/src/provider/sdk/copilot/responses/tool/code-interpreter.ts` | ✅ | source | 87 | codeInterpreterInputSchema |
| `packages/opencode/src/provider/sdk/copilot/responses/tool/file-search.ts` | ✅ | source | 127 | fileSearchArgsSchema |
| `packages/opencode/src/provider/sdk/copilot/responses/tool/image-generation.ts` | ✅ | source | 114 | imageGenerationArgsSchema |
| `packages/opencode/src/provider/sdk/copilot/responses/tool/local-shell.ts` | ✅ | source | 64 | localShellInputSchema |
| `packages/opencode/src/provider/sdk/copilot/responses/tool/web-search-preview.ts` | ✅ | source | 103 | webSearchPreviewArgsSchema |
| `packages/opencode/src/provider/sdk/copilot/responses/tool/web-search.ts` | ✅ | source | 102 | webSearchArgsSchema |
| `packages/opencode/src/provider/transform.ts` | ✅ | source | 1200 | message |
| `packages/opencode/src/pty/index.ts` | ✅ | source | 368 | Info |
| `packages/opencode/src/pty/input.ts` | ✅ | source | 24 | handlePtyInput |
| `packages/opencode/src/pty/pty.bun.ts` | ✅ | source | 26 | spawn |
| `packages/opencode/src/pty/pty.node.ts` | ✅ | source | 27 | spawn |
| `packages/opencode/src/pty/pty.ts` | ✅ | source | 25 |  |
| `packages/opencode/src/pty/schema.ts` | ✅ | source | 16 | PtyID |
| `packages/opencode/src/question/index.ts` | ✅ | source | 229 | Answer |
| `packages/opencode/src/question/schema.ts` | ✅ | source | 16 |  |
| `packages/opencode/src/server/adapter.bun.ts` | ✅ | source | 44 | adapter |
| `packages/opencode/src/server/adapter.node.ts` | ✅ | source | 73 | adapter |
| `packages/opencode/src/server/adapter.ts` | ✅ | source | 26 |  |
| `packages/opencode/src/server/backend.ts` | ✅ | source | 32 | select |
| `packages/opencode/src/server/cors.ts` | ✅ | source | 14 | isAllowedCorsOrigin |
| `packages/opencode/src/server/error.ts` | ✅ | source | 36 | errors |
| `packages/opencode/src/server/event.ts` | ✅ | source | 7 | Event |
| `packages/opencode/src/server/fence.ts` | ✅ | source | 90 | load |
| `packages/opencode/src/server/mdns.ts` | ✅ | source | 60 | publish |
| `packages/opencode/src/server/middleware.ts` | ✅ | source | 86 | LoggerMiddleware |
| `packages/opencode/src/server/projectors.ts` | ✅ | source | 28 | initProjectors |
| `packages/opencode/src/server/proxy-util.ts` | ✅ | source | 48 | headers |
| `packages/opencode/src/server/proxy.ts` | ✅ | source | 149 | httpEffect |
| `packages/opencode/src/server/routes/control/index.ts` | ✅ | source | 160 | ControlPlaneRoutes |
| `packages/opencode/src/server/routes/control/workspace.ts` | ✅ | source | 210 | WorkspaceRoutes |
| `packages/opencode/src/server/routes/global.ts` | ✅ | source | 287 | GlobalDisposedEvent |
| `packages/opencode/src/server/routes/instance/config.ts` | ✅ | config | 89 |  |
| `packages/opencode/src/server/routes/instance/event.ts` | ✅ | source | 88 | EventRoutes |
| `packages/opencode/src/server/routes/instance/experimental.ts` | ✅ | source | 419 | ExperimentalRoutes |
| `packages/opencode/src/server/routes/instance/file.ts` | ✅ | source | 190 | FileRoutes |
| `packages/opencode/src/server/routes/instance/httpapi/AGENTS.md` | ✅ | docs | 35 |  |
| `packages/opencode/src/server/routes/instance/httpapi/api.ts` | ✅ | source | 54 | RootHttpApi |
| `packages/opencode/src/server/routes/instance/httpapi/event.ts` | ✅ | source | 77 | EventPaths |
| `packages/opencode/src/server/routes/instance/httpapi/groups/config.ts` | ✅ | config | 61 |  |
| `packages/opencode/src/server/routes/instance/httpapi/groups/control.ts` | ✅ | source | 75 | LogInput |
| `packages/opencode/src/server/routes/instance/httpapi/groups/experimental.ts` | ✅ | source | 214 | ConsoleSwitchPayload |
| `packages/opencode/src/server/routes/instance/httpapi/groups/file.ts` | ✅ | source | 121 | FileQuery |
| `packages/opencode/src/server/routes/instance/httpapi/groups/global.ts` | ✅ | source | 106 | GlobalUpgradeInput |
| `packages/opencode/src/server/routes/instance/httpapi/groups/instance.ts` | ✅ | source | 143 | VcsDiffQuery |
| `packages/opencode/src/server/routes/instance/httpapi/groups/mcp.ts` | ✅ | source | 145 | AddPayload |
| `packages/opencode/src/server/routes/instance/httpapi/groups/metadata.ts` | ✅ | source | 18 | described |
| `packages/opencode/src/server/routes/instance/httpapi/groups/permission.ts` | ✅ | source | 58 | PermissionApi |
| `packages/opencode/src/server/routes/instance/httpapi/groups/project.ts` | ✅ | source | 77 | ProjectApi |
| `packages/opencode/src/server/routes/instance/httpapi/groups/provider.ts` | ✅ | source | 76 | ProviderApi |
| `packages/opencode/src/server/routes/instance/httpapi/groups/pty.ts` | ✅ | source | 127 | Params |
| `packages/opencode/src/server/routes/instance/httpapi/groups/question.ts` | ✅ | source | 70 | QuestionApi |
| `packages/opencode/src/server/routes/instance/httpapi/groups/session.ts` | ✅ | source | 429 | ListQuery |
| `packages/opencode/src/server/routes/instance/httpapi/groups/sync.ts` | ✅ | source | 92 | ReplayEvent |
| `packages/opencode/src/server/routes/instance/httpapi/groups/tui.ts` | ✅ | source | 197 | CommandPayload |
| `packages/opencode/src/server/routes/instance/httpapi/groups/workspace.ts` | ✅ | source | 103 | CreatePayload |
| `packages/opencode/src/server/routes/instance/httpapi/handlers/config.ts` | ✅ | config | 34 |  |
| `packages/opencode/src/server/routes/instance/httpapi/handlers/control.ts` | ✅ | source | 34 | controlHandlers |
| `packages/opencode/src/server/routes/instance/httpapi/handlers/experimental.ts` | ✅ | source | 155 | experimentalHandlers |
| `packages/opencode/src/server/routes/instance/httpapi/handlers/file.ts` | ✅ | source | 54 | fileHandlers |
| `packages/opencode/src/server/routes/instance/httpapi/handlers/global.ts` | ✅ | source | 156 | globalHandlers |
| `packages/opencode/src/server/routes/instance/httpapi/handlers/instance.ts` | ✅ | source | 79 | instanceHandlers |
| `packages/opencode/src/server/routes/instance/httpapi/handlers/mcp.ts` | ✅ | source | 68 | mcpHandlers |
| `packages/opencode/src/server/routes/instance/httpapi/handlers/permission.ts` | ✅ | source | 29 | permissionHandlers |
| `packages/opencode/src/server/routes/instance/httpapi/handlers/project.ts` | ✅ | source | 46 | projectHandlers |
| `packages/opencode/src/server/routes/instance/httpapi/handlers/provider.ts` | ✅ | source | 89 | providerHandlers |
| `packages/opencode/src/server/routes/instance/httpapi/handlers/pty.ts` | ✅ | source | 121 | ptyHandlers |
| `packages/opencode/src/server/routes/instance/httpapi/handlers/question.ts` | ✅ | source | 33 | questionHandlers |
| `packages/opencode/src/server/routes/instance/httpapi/handlers/session.ts` | ✅ | source | 388 | sessionHandlers |
| `packages/opencode/src/server/routes/instance/httpapi/handlers/sync.ts` | ✅ | source | 77 | syncHandlers |
| `packages/opencode/src/server/routes/instance/httpapi/handlers/tui.ts` | ✅ | source | 135 | tuiHandlers |
| `packages/opencode/src/server/routes/instance/httpapi/handlers/workspace.ts` | ✅ | source | 61 | workspaceHandlers |
| `packages/opencode/src/server/routes/instance/httpapi/lifecycle.ts` | ✅ | source | 63 | markInstanceForDisposal |
| `packages/opencode/src/server/routes/instance/httpapi/middleware/authorization.ts` | ✅ | source | 128 | authorizationRouterMiddleware |
| `packages/opencode/src/server/routes/instance/httpapi/middleware/instance-context.ts` | ✅ | source | 55 | instanceContextLayer |
| `packages/opencode/src/server/routes/instance/httpapi/middleware/proxy.ts` | ✅ | source | 86 | websocket |
| `packages/opencode/src/server/routes/instance/httpapi/middleware/workspace-routing.ts` | ✅ | source | 228 | workspaceRoutingLayer |
| `packages/opencode/src/server/routes/instance/httpapi/public.ts` | ✅ | source | 505 | PublicApi |
| `packages/opencode/src/server/routes/instance/httpapi/server.ts` | ✅ | source | 198 | createRoutes |
| `packages/opencode/src/server/routes/instance/index.ts` | ✅ | source | 278 | InstanceRoutes |
| `packages/opencode/src/server/routes/instance/mcp.ts` | ✅ | source | 277 | McpRoutes |
| `packages/opencode/src/server/routes/instance/middleware.ts` | ✅ | source | 35 | InstanceMiddleware |
| `packages/opencode/src/server/routes/instance/permission.ts` | ✅ | source | 73 | PermissionRoutes |
| `packages/opencode/src/server/routes/instance/project.ts` | ✅ | source | 122 | ProjectRoutes |
| `packages/opencode/src/server/routes/instance/provider.ts` | ✅ | source | 158 | ProviderRoutes |
| `packages/opencode/src/server/routes/instance/pty.ts` | ✅ | source | 276 | PtyRoutes |
| `packages/opencode/src/server/routes/instance/question.ts` | ✅ | source | 111 | QuestionRoutes |
| `packages/opencode/src/server/routes/instance/session.ts` | ✅ | source | 1124 | SessionRoutes |
| `packages/opencode/src/server/routes/instance/sync.ts` | ✅ | source | 152 | SyncRoutes |
| `packages/opencode/src/server/routes/instance/trace.ts` | ✅ | source | 59 | paramToAttributeKey |
| `packages/opencode/src/server/routes/instance/tui.ts` | ✅ | source | 399 | nextTuiRequest |
| `packages/opencode/src/server/routes/ui.ts` | ✅ | source | 127 | serveUI |
| `packages/opencode/src/server/server.ts` | ✅ | source | 195 | Legacy |
| `packages/opencode/src/server/workspace.ts` | ✅ | source | 130 | isLocalWorkspaceRoute |
| `packages/opencode/src/session/compaction.ts` | ✅ | source | 630 | isOverflow |
| `packages/opencode/src/session/instruction.ts` | ✅ | source | 232 | loaded |
| `packages/opencode/src/session/llm.ts` | ✅ | source | 469 | hasToolCalls |
| `packages/opencode/src/session/message-v2.ts` | ✅ | source | 1221 | toModelMessages |
| `packages/opencode/src/session/message.ts` | ✅ | source | 192 | OutputLengthError |
| `packages/opencode/src/session/overflow.ts` | ✅ | source | 26 | usable |
| `packages/opencode/src/session/processor.ts` | ✅ | source | 619 | layer |
| `packages/opencode/src/session/projectors.ts` | ✅ | source | 139 | toPartialRow |
| `packages/opencode/src/session/prompt.ts` | ✅ | source | 1784 | createStructuredOutputTool |
| `packages/opencode/src/session/retry.ts` | ✅ | source | 125 | delay |
| `packages/opencode/src/session/revert.ts` | ✅ | source | 164 | RevertInput |
| `packages/opencode/src/session/run-state.ts` | ✅ | source | 110 | layer |
| `packages/opencode/src/session/schema.ts` | ✅ | source | 35 | SessionID |
| `packages/opencode/src/session/session.sql.ts` | ✅ | source | 124 | SessionTable |
| `packages/opencode/src/session/session.ts` | ✅ | source | 902 | isDefaultTitle |
| `packages/opencode/src/session/status.ts` | ✅ | source | 88 | Info |
| `packages/opencode/src/session/summary.ts` | ✅ | source | 165 | layer |
| `packages/opencode/src/session/system.ts` | ✅ | source | 84 | provider |
| `packages/opencode/src/session/todo.ts` | ✅ | source | 86 | Info |
| `packages/opencode/src/share/session.ts` | ✅ | source | 59 | layer |
| `packages/opencode/src/share/share-next.ts` | ✅ | source | 376 | layer |
| `packages/opencode/src/share/share.sql.ts` | ✅ | source | 13 | SessionShareTable |
| `packages/opencode/src/shell/shell.ts` | ✅ | source | 215 | killTree |
| `packages/opencode/src/skill/discovery.ts` | ✅ | source | 116 | layer |
| `packages/opencode/src/skill/index.ts` | ✅ | source | 297 | fmt |
| `packages/opencode/src/snapshot/index.ts` | ✅ | source | 777 | Patch |
| `packages/opencode/src/sql.d.ts` | ✅ | source | 4 |  |
| `packages/opencode/src/storage/db.bun.ts` | ✅ | source | 8 | init |
| `packages/opencode/src/storage/db.node.ts` | ✅ | source | 8 | init |
| `packages/opencode/src/storage/db.ts` | ✅ | source | 181 | getChannelPath |
| `packages/opencode/src/storage/json-migration.ts` | ✅ | source | 431 | run |
| `packages/opencode/src/storage/schema.sql.ts` | ✅ | source | 10 | Timestamps |
| `packages/opencode/src/storage/schema.ts` | ✅ | source | 5 |  |
| `packages/opencode/src/storage/storage.ts` | ✅ | source | 334 | NotFoundError |
| `packages/opencode/src/sync/README.md` | ✅ | docs | 179 |  |
| `packages/opencode/src/sync/event.sql.ts` | ✅ | source | 16 | EventSequenceTable |
| `packages/opencode/src/sync/index.ts` | ✅ | source | 387 | reset |
| `packages/opencode/src/sync/schema.ts` | ✅ | source | 13 | EventID |
| `packages/opencode/src/temporary.ts` | ✅ | source | 33 |  |
| `packages/opencode/src/tool/apply_patch.ts` | ✅ | source | 309 | Parameters |
| `packages/opencode/src/tool/bash.ts` | ✅ | source | 635 | Parameters |
| `packages/opencode/src/tool/edit.ts` | ✅ | source | 711 | trimDiff |
| `packages/opencode/src/tool/external-directory.ts` | ✅ | source | 49 | assertExternalDirectory |
| `packages/opencode/src/tool/glob.ts` | ✅ | source | 97 | Parameters |
| `packages/opencode/src/tool/grep.ts` | ✅ | source | 151 | Parameters |
| `packages/opencode/src/tool/invalid.ts` | ✅ | source | 21 | Parameters |
| `packages/opencode/src/tool/lsp.ts` | ✅ | source | 113 | Parameters |
| `packages/opencode/src/tool/mcp-exa.ts` | ✅ | source | 73 | SearchArgs |
| `packages/opencode/src/tool/plan.ts` | ✅ | source | 82 | Parameters |
| `packages/opencode/src/tool/question.ts` | ✅ | source | 44 | Parameters |
| `packages/opencode/src/tool/read.ts` | ✅ | source | 343 | Parameters |
| `packages/opencode/src/tool/registry.ts` | ✅ | source | 347 | layer |
| `packages/opencode/src/tool/schema.ts` | ✅ | source | 16 | ToolID |
| `packages/opencode/src/tool/skill.ts` | ✅ | source | 75 | Parameters |
| `packages/opencode/src/tool/task.ts` | ✅ | source | 180 | Parameters |
| `packages/opencode/src/tool/todo.ts` | ✅ | source | 57 | Parameters |
| `packages/opencode/src/tool/tool.ts` | ✅ | source | 162 | define |
| `packages/opencode/src/tool/truncate.ts` | ✅ | source | 160 | MAX_LINES |
| `packages/opencode/src/tool/truncation-dir.ts` | ✅ | source | 4 | TRUNCATION_DIR |
| `packages/opencode/src/tool/webfetch.ts` | ✅ | source | 199 | Parameters |
| `packages/opencode/src/tool/websearch.ts` | ✅ | source | 71 | Parameters |
| `packages/opencode/src/tool/write.ts` | ✅ | source | 104 | Parameters |
| `packages/opencode/src/util/abort.ts` | ✅ | source | 35 | abortAfter |
| `packages/opencode/src/util/archive.ts` | ✅ | source | 17 | extractZip |
| `packages/opencode/src/util/bom.ts` | ✅ | source | 31 | split |
| `packages/opencode/src/util/color.ts` | ✅ | source | 19 | isValidHex |
| `packages/opencode/src/util/data-url.ts` | ✅ | source | 9 | decodeDataUrl |
| `packages/opencode/src/util/defer.ts` | ✅ | source | 10 | defer |
| `packages/opencode/src/util/effect-http-client.ts` | ✅ | source | 11 | withTransientReadRetry |
| `packages/opencode/src/util/effect-zod.ts` | ✅ | source | 370 | zod |
| `packages/opencode/src/util/error.ts` | ✅ | source | 82 | errorFormat |
| `packages/opencode/src/util/filesystem.ts` | ✅ | source | 245 | exists |
| `packages/opencode/src/util/fn.ts` | ✅ | source | 21 | fn |
| `packages/opencode/src/util/format.ts` | ✅ | source | 20 | formatDuration |
| `packages/opencode/src/util/iife.ts` | ✅ | source | 3 | iife |
| `packages/opencode/src/util/keybind.ts` | ✅ | source | 103 | match |
| `packages/opencode/src/util/lazy.ts` | ✅ | source | 18 | lazy |
| `packages/opencode/src/util/local-context.ts` | ✅ | source | 25 | create |
| `packages/opencode/src/util/locale.ts` | ✅ | source | 81 | titlecase |
| `packages/opencode/src/util/lock.ts` | ✅ | source | 98 | read |
| `packages/opencode/src/util/media.ts` | ✅ | source | 26 | isPdfAttachment |
| `packages/opencode/src/util/named-schema-error.ts` | ✅ | source | 61 | namedSchemaError |
| `packages/opencode/src/util/network.ts` | ✅ | source | 9 | online |
| `packages/opencode/src/util/process.ts` | ✅ | source | 176 | spawn |
| `packages/opencode/src/util/queue.ts` | ✅ | source | 32 | work |
| `packages/opencode/src/util/record.ts` | ✅ | source | 3 | isRecord |
| `packages/opencode/src/util/rpc.ts` | ✅ | source | 66 | listen |
| `packages/opencode/src/util/schema.ts` | ✅ | source | 108 | Newtype |
| `packages/opencode/src/util/scrap.ts` | ✅ | source | 10 | dummyFunction |
| `packages/opencode/src/util/signal.ts` | ✅ | source | 12 | signal |
| `packages/opencode/src/util/timeout.ts` | ✅ | source | 13 | withTimeout |
| `packages/opencode/src/util/token.ts` | ✅ | source | 7 | estimate |
| `packages/opencode/src/util/update-schema.ts` | ✅ | source | 13 | updateSchema |
| `packages/opencode/src/util/which.ts` | ✅ | source | 14 | which |
| `packages/opencode/src/util/wildcard.ts` | ✅ | source | 59 | match |
| `packages/opencode/src/v2/session-entry-stepper.ts` | ✅ | source | 261 | memory |
| `packages/opencode/src/v2/session-entry.ts` | ✅ | source | 220 | ID |
| `packages/opencode/src/v2/session-event.ts` | ✅ | source | 458 |  |
| `packages/opencode/src/v2/session.ts` | ✅ | source | 69 | ID |
| `packages/opencode/src/worktree/index.ts` | ✅ | source | 592 | Event |
| `packages/opencode/sst-env.d.ts` | ✅ | source | 10 |  |
| `packages/opencode/test/AGENTS.md` | ✅ | test | 133 |  |
| `packages/opencode/test/account/repo.test.ts` | ✅ | test | 352 |  |
| `packages/opencode/test/account/service.test.ts` | ✅ | test | 456 |  |
| `packages/opencode/test/acp/agent-interface.test.ts` | ✅ | test | 51 |  |
| `packages/opencode/test/acp/event-subscription.test.ts` | ✅ | test | 725 |  |
| `packages/opencode/test/agent/agent.test.ts` | ✅ | test | 742 |  |
| `packages/opencode/test/auth/auth.test.ts` | ✅ | test | 86 |  |
| `packages/opencode/test/bus/bus-effect.test.ts` | ✅ | test | 161 |  |
| `packages/opencode/test/bus/bus-integration.test.ts` | ✅ | test | 87 |  |
| `packages/opencode/test/bus/bus.test.ts` | ✅ | test | 219 |  |
| `packages/opencode/test/cli/account.test.ts` | ✅ | test | 26 |  |
| `packages/opencode/test/cli/cmd/tui/prompt-part.test.ts` | ✅ | test | 47 |  |
| `packages/opencode/test/cli/cmd/tui/sync.test.tsx` | ✅ | test | 149 |  |
| `packages/opencode/test/cli/error.test.ts` | ✅ | test | 18 |  |
| `packages/opencode/test/cli/github-action.test.ts` | ✅ | test | 198 |  |
| `packages/opencode/test/cli/github-remote.test.ts` | ✅ | test | 80 |  |
| `packages/opencode/test/cli/import.test.ts` | ✅ | test | 54 |  |
| `packages/opencode/test/cli/plugin-auth-picker.test.ts` | ✅ | test | 120 |  |
| `packages/opencode/test/cli/tui/editor-context-zed.test.ts` | ✅ | test | 356 |  |
| `packages/opencode/test/cli/tui/editor-context.test.tsx` | ✅ | test | 228 |  |
| `packages/opencode/test/cli/tui/keybind-plugin.test.ts` | ✅ | test | 90 |  |
| `packages/opencode/test/cli/tui/plugin-add.test.ts` | ✅ | test | 111 |  |
| `packages/opencode/test/cli/tui/plugin-install.test.ts` | ✅ | test | 87 |  |
| `packages/opencode/test/cli/tui/plugin-lifecycle.test.ts` | ✅ | test | 224 |  |
| `packages/opencode/test/cli/tui/plugin-loader-entrypoint.test.ts` | ✅ | test | 484 |  |
| `packages/opencode/test/cli/tui/plugin-loader-pure.test.ts` | ✅ | test | 71 |  |
| `packages/opencode/test/cli/tui/plugin-loader.test.ts` | ✅ | test | 816 |  |
| `packages/opencode/test/cli/tui/plugin-toggle.test.ts` | ✅ | test | 157 |  |
| `packages/opencode/test/cli/tui/revert-diff.test.ts` | ✅ | test | 35 |  |
| `packages/opencode/test/cli/tui/slot-replace.test.tsx` | ✅ | test | 47 |  |
| `packages/opencode/test/cli/tui/theme-store.test.ts` | ✅ | test | 51 |  |
| `packages/opencode/test/cli/tui/thread.test.ts` | ✅ | test | 28 |  |
| `packages/opencode/test/cli/tui/transcript.test.ts` | ✅ | test | 426 |  |
| `packages/opencode/test/cli/tui/use-event.test.tsx` | ✅ | test | 175 |  |
| `packages/opencode/test/config/agent-color.test.ts` | ✅ | test | 69 |  |
| `packages/opencode/test/config/config.test.ts` | ✅ | test | 2481 |  |
| `packages/opencode/test/config/fixtures/empty-frontmatter.md` | ✅ | test | 4 |  |
| `packages/opencode/test/config/fixtures/frontmatter.md` | ✅ | test | 28 |  |
| `packages/opencode/test/config/fixtures/markdown-header.md` | ✅ | test | 11 |  |
| `packages/opencode/test/config/fixtures/no-frontmatter.md` | ✅ | test | 1 |  |
| `packages/opencode/test/config/fixtures/weird-model-id.md` | ✅ | test | 13 |  |
| `packages/opencode/test/config/lsp.test.ts` | ✅ | test | 87 |  |
| `packages/opencode/test/config/markdown.test.ts` | ✅ | test | 228 |  |
| `packages/opencode/test/config/plugin.test.ts` | ✅ | test | 0 |  |
| `packages/opencode/test/config/tui.test.ts` | ✅ | test | 626 |  |
| `packages/opencode/test/control-plane/adapters.test.ts` | ✅ | test | 71 |  |
| `packages/opencode/test/control-plane/workspace.test.ts` | ✅ | test | 1526 |  |
| `packages/opencode/test/effect/app-runtime-logger.test.ts` | ✅ | test | 98 |  |
| `packages/opencode/test/effect/config-service.test.ts` | ✅ | test | 65 |  |
| `packages/opencode/test/effect/instance-state.test.ts` | ✅ | test | 393 |  |
| `packages/opencode/test/effect/run-service.test.ts` | ✅ | test | 49 |  |
| `packages/opencode/test/effect/runner.test.ts` | ✅ | test | 523 |  |
| `packages/opencode/test/fake/provider.ts` | ✅ | test | 81 |  |
| `packages/opencode/test/file/fsmonitor.test.ts` | ✅ | test | 68 |  |
| `packages/opencode/test/file/ignore.test.ts` | ✅ | test | 10 |  |
| `packages/opencode/test/file/index.test.ts` | ✅ | test | 956 |  |
| `packages/opencode/test/file/path-traversal.test.ts` | ✅ | test | 204 |  |
| `packages/opencode/test/file/ripgrep.test.ts` | ✅ | test | 214 |  |
| `packages/opencode/test/file/watcher.test.ts` | ✅ | test | 249 |  |
| `packages/opencode/test/filesystem/filesystem.test.ts` | ✅ | test | 319 |  |
| `packages/opencode/test/fixture/db.ts` | ✅ | test | 11 |  |
| `packages/opencode/test/fixture/fixture.test.ts` | ✅ | test | 26 |  |
| `packages/opencode/test/fixture/fixture.ts` | ✅ | test | 174 |  |
| `packages/opencode/test/fixture/flock-worker.ts` | ✅ | test | 72 |  |
| `packages/opencode/test/fixture/lsp/fake-lsp-server.js` | ✅ | test | 249 |  |
| `packages/opencode/test/fixture/plug-worker.ts` | ✅ | test | 93 |  |
| `packages/opencode/test/fixture/plugin-meta-worker.ts` | ✅ | test | 19 |  |
| `packages/opencode/test/fixture/skills/agents-sdk/SKILL.md` | ✅ | test | 152 |  |
| `packages/opencode/test/fixture/skills/agents-sdk/references/callable.md` | ✅ | test | 92 |  |
| `packages/opencode/test/fixture/skills/cloudflare/SKILL.md` | ✅ | test | 211 |  |
| `packages/opencode/test/fixture/skills/index.json` | ✅ | test | 6 |  |
| `packages/opencode/test/fixture/tui-plugin.ts` | ✅ | test | 323 |  |
| `packages/opencode/test/fixture/tui-runtime.ts` | ✅ | test | 31 |  |
| `packages/opencode/test/format/format.test.ts` | ✅ | test | 272 |  |
| `packages/opencode/test/git/git.test.ts` | ✅ | test | 128 |  |
| `packages/opencode/test/ide/ide.test.ts` | ✅ | test | 82 |  |
| `packages/opencode/test/installation/installation.test.ts` | ✅ | test | 168 |  |
| `packages/opencode/test/keybind.test.ts` | ✅ | test | 421 |  |
| `packages/opencode/test/lib/effect.ts` | ✅ | test | 53 |  |
| `packages/opencode/test/lib/filesystem.ts` | ✅ | test | 10 |  |
| `packages/opencode/test/lib/llm-server.ts` | ✅ | test | 771 |  |
| `packages/opencode/test/lib/websocket.ts` | ✅ | test | 46 |  |
| `packages/opencode/test/lsp/client.test.ts` | ✅ | test | 482 |  |
| `packages/opencode/test/lsp/index.test.ts` | ✅ | test | 109 |  |
| `packages/opencode/test/lsp/launch.test.ts` | ✅ | test | 22 |  |
| `packages/opencode/test/lsp/lifecycle.test.ts` | ✅ | test | 184 |  |
| `packages/opencode/test/mcp/headers.test.ts` | ✅ | test | 178 |  |
| `packages/opencode/test/mcp/lifecycle.test.ts` | ✅ | test | 786 |  |
| `packages/opencode/test/mcp/oauth-auto-connect.test.ts` | ✅ | test | 281 |  |
| `packages/opencode/test/mcp/oauth-browser.test.ts` | ✅ | test | 268 |  |
| `packages/opencode/test/mcp/oauth-callback.test.ts` | ✅ | test | 34 |  |
| `packages/opencode/test/memory/abort-leak-webfetch.ts` | ✅ | test | 49 |  |
| `packages/opencode/test/memory/abort-leak.test.ts` | ✅ | test | 127 |  |
| `packages/opencode/test/patch/patch.test.ts` | ✅ | test | 348 |  |
| `packages/opencode/test/permission-task.test.ts` | ✅ | test | 326 |  |
| `packages/opencode/test/permission/arity.test.ts` | ✅ | test | 33 |  |
| `packages/opencode/test/permission/next.test.ts` | ✅ | test | 1124 |  |
| `packages/opencode/test/plugin/auth-override.test.ts` | ✅ | test | 79 |  |
| `packages/opencode/test/plugin/cloudflare.test.ts` | ✅ | test | 68 |  |
| `packages/opencode/test/plugin/codex.test.ts` | ✅ | test | 123 |  |
| `packages/opencode/test/plugin/github-copilot-models.test.ts` | ✅ | test | 261 |  |
| `packages/opencode/test/plugin/install-concurrency.test.ts` | ✅ | test | 140 |  |
| `packages/opencode/test/plugin/install.test.ts` | ✅ | test | 570 |  |
| `packages/opencode/test/plugin/loader-shared.test.ts` | ✅ | test | 1169 |  |
| `packages/opencode/test/plugin/meta.test.ts` | ✅ | test | 137 |  |
| `packages/opencode/test/plugin/shared.test.ts` | ✅ | test | 88 |  |
| `packages/opencode/test/plugin/trigger.test.ts` | ✅ | test | 102 |  |
| `packages/opencode/test/plugin/workspace-adapter.test.ts` | ✅ | test | 109 |  |
| `packages/opencode/test/preload.ts` | ✅ | test | 91 |  |
| `packages/opencode/test/project/migrate-global.test.ts` | ✅ | test | 152 |  |
| `packages/opencode/test/project/project.test.ts` | ✅ | test | 601 |  |
| `packages/opencode/test/project/vcs.test.ts` | ✅ | test | 286 |  |
| `packages/opencode/test/project/worktree-remove.test.ts` | ✅ | test | 126 |  |
| `packages/opencode/test/project/worktree.test.ts` | ✅ | test | 214 |  |
| `packages/opencode/test/provider/amazon-bedrock.test.ts` | ✅ | test | 462 |  |
| `packages/opencode/test/provider/copilot/convert-to-copilot-messages.test.ts` | ✅ | test | 523 |  |
| `packages/opencode/test/provider/copilot/copilot-chat-model.test.ts` | ✅ | test | 592 |  |
| `packages/opencode/test/provider/gitlab-duo.test.ts` | ✅ | test | 413 |  |
| `packages/opencode/test/provider/provider.test.ts` | ✅ | test | 2714 |  |
| `packages/opencode/test/provider/transform.test.ts` | ✅ | test | 3333 |  |
| `packages/opencode/test/pty/pty-output-isolation.test.ts` | ✅ | test | 146 |  |
| `packages/opencode/test/pty/pty-session.test.ts` | ✅ | test | 102 |  |
| `packages/opencode/test/pty/pty-shell.test.ts` | ✅ | test | 104 |  |
| `packages/opencode/test/question/question.test.ts` | ✅ | test | 464 |  |
| `packages/opencode/test/server/AGENTS.md` | ✅ | test | 15 |  |
| `packages/opencode/test/server/global-session-list.test.ts` | ✅ | test | 105 |  |
| `packages/opencode/test/server/httpapi-authorization.test.ts` | ✅ | test | 103 |  |
| `packages/opencode/test/server/httpapi-bridge.test.ts` | ✅ | test | 420 |  |
| `packages/opencode/test/server/httpapi-config.test.ts` | ✅ | test | 67 |  |
| `packages/opencode/test/server/httpapi-cors.test.ts` | ✅ | test | 89 |  |
| `packages/opencode/test/server/httpapi-event.test.ts` | ✅ | test | 57 |  |
| `packages/opencode/test/server/httpapi-experimental.test.ts` | ✅ | test | 217 |  |
| `packages/opencode/test/server/httpapi-file.test.ts` | ✅ | test | 77 |  |
| `packages/opencode/test/server/httpapi-instance-context.test.ts` | ✅ | test | 233 |  |
| `packages/opencode/test/server/httpapi-instance.legacy.test.ts` | ✅ | test | 138 |  |
| `packages/opencode/test/server/httpapi-instance.test.ts` | ✅ | test | 83 |  |
| `packages/opencode/test/server/httpapi-json-parity.test.ts` | ✅ | test | 254 |  |
| `packages/opencode/test/server/httpapi-mcp-oauth.test.ts` | ✅ | test | 76 |  |
| `packages/opencode/test/server/httpapi-mcp.test.ts` | ✅ | test | 186 |  |
| `packages/opencode/test/server/httpapi-provider.test.ts` | ✅ | test | 150 |  |
| `packages/opencode/test/server/httpapi-pty-websocket.test.ts` | ✅ | test | 16 |  |
| `packages/opencode/test/server/httpapi-pty.test.ts` | ✅ | test | 175 |  |
| `packages/opencode/test/server/httpapi-raw-route-auth.test.ts` | ✅ | test | 89 |  |
| `packages/opencode/test/server/httpapi-sdk.test.ts` | ✅ | test | 670 |  |
| `packages/opencode/test/server/httpapi-session.test.ts` | ✅ | test | 464 |  |
| `packages/opencode/test/server/httpapi-sync.test.ts` | ✅ | test | 130 |  |
| `packages/opencode/test/server/httpapi-tui.test.ts` | ✅ | test | 121 |  |
| `packages/opencode/test/server/httpapi-ui.test.ts` | ✅ | test | 245 |  |
| `packages/opencode/test/server/httpapi-workspace-routing.test.ts` | ✅ | test | 471 |  |
| `packages/opencode/test/server/httpapi-workspace.test.ts` | ✅ | test | 360 |  |
| `packages/opencode/test/server/project-init-git.test.ts` | ✅ | test | 122 |  |
| `packages/opencode/test/server/proxy-util.test.ts` | ✅ | test | 113 |  |
| `packages/opencode/test/server/session-actions.test.ts` | ✅ | test | 49 |  |
| `packages/opencode/test/server/session-list.test.ts` | ✅ | test | 238 |  |
| `packages/opencode/test/server/session-messages.test.ts` | ✅ | test | 167 |  |
| `packages/opencode/test/server/session-select.test.ts` | ✅ | test | 100 |  |
| `packages/opencode/test/server/trace-attributes.test.ts` | ✅ | test | 76 |  |
| `packages/opencode/test/server/workspace-proxy.test.ts` | ✅ | test | 165 |  |
| `packages/opencode/test/server/workspace-routing.test.ts` | ✅ | test | 85 |  |
| `packages/opencode/test/session/compaction.test.ts` | ✅ | test | 2181 |  |
| `packages/opencode/test/session/instruction.test.ts` | ✅ | test | 246 |  |
| `packages/opencode/test/session/llm.test.ts` | ✅ | test | 1272 |  |
| `packages/opencode/test/session/message-v2.test.ts` | ✅ | test | 1291 |  |
| `packages/opencode/test/session/messages-pagination.test.ts` | ✅ | test | 1173 |  |
| `packages/opencode/test/session/processor-effect.test.ts` | ✅ | test | 842 |  |
| `packages/opencode/test/session/prompt.test.ts` | ✅ | test | 1980 |  |
| `packages/opencode/test/session/retry.test.ts` | ✅ | test | 326 |  |
| `packages/opencode/test/session/revert-compact.test.ts` | ✅ | test | 639 |  |
| `packages/opencode/test/session/schema-decoding.test.ts` | ✅ | test | 311 |  |
| `packages/opencode/test/session/session-entry-stepper.test.ts` | ✅ | test | 916 |  |
| `packages/opencode/test/session/session-schema.test.ts` | ✅ | test | 76 |  |
| `packages/opencode/test/session/session.test.ts` | ✅ | test | 185 |  |
| `packages/opencode/test/session/snapshot-tool-race.test.ts` | ✅ | test | 249 |  |
| `packages/opencode/test/session/structured-output-integration.test.ts` | ✅ | test | 264 |  |
| `packages/opencode/test/session/structured-output.test.ts` | ✅ | test | 381 |  |
| `packages/opencode/test/session/system.test.ts` | ✅ | test | 73 |  |
| `packages/opencode/test/share/share-next.test.ts` | ✅ | test | 333 |  |
| `packages/opencode/test/shell/shell.test.ts` | ✅ | test | 99 |  |
| `packages/opencode/test/skill/discovery.test.ts` | ✅ | test | 116 |  |
| `packages/opencode/test/skill/skill.test.ts` | ✅ | test | 391 |  |
| `packages/opencode/test/snapshot/snapshot.test.ts` | ✅ | test | 1531 |  |
| `packages/opencode/test/storage/db.test.ts` | ✅ | test | 14 |  |
| `packages/opencode/test/storage/json-migration.test.ts` | ✅ | test | 832 |  |
| `packages/opencode/test/storage/storage.test.ts` | ✅ | test | 293 |  |
| `packages/opencode/test/sync/index.test.ts` | ✅ | test | 256 |  |
| `packages/opencode/test/tool/apply_patch.test.ts` | ✅ | test | 614 |  |
| `packages/opencode/test/tool/bash.test.ts` | ✅ | test | 1224 |  |
| `packages/opencode/test/tool/edit.test.ts` | ✅ | test | 754 |  |
| `packages/opencode/test/tool/external-directory.test.ts` | ✅ | test | 169 |  |
| `packages/opencode/test/tool/fixtures/models-api.json` | ✅ | test | 65179 |  |
| `packages/opencode/test/tool/glob.test.ts` | ✅ | test | 81 |  |
| `packages/opencode/test/tool/grep.test.ts` | ✅ | test | 114 |  |
| `packages/opencode/test/tool/lsp.test.ts` | ✅ | test | 187 |  |
| `packages/opencode/test/tool/parameters.test.ts` | ✅ | test | 243 |  |
| `packages/opencode/test/tool/question.test.ts` | ✅ | test | 129 |  |
| `packages/opencode/test/tool/read.test.ts` | ✅ | test | 501 |  |
| `packages/opencode/test/tool/registry.test.ts` | ✅ | test | 152 |  |
| `packages/opencode/test/tool/skill.test.ts` | ✅ | test | 96 |  |
| `packages/opencode/test/tool/task.test.ts` | ✅ | test | 387 |  |
| `packages/opencode/test/tool/tool-define.test.ts` | ✅ | test | 99 |  |
| `packages/opencode/test/tool/truncation.test.ts` | ✅ | test | 260 |  |
| `packages/opencode/test/tool/webfetch.test.ts` | ✅ | test | 103 |  |
| `packages/opencode/test/tool/write.test.ts` | ✅ | test | 291 |  |
| `packages/opencode/test/util/data-url.test.ts` | ✅ | test | 14 |  |
| `packages/opencode/test/util/effect-zod.test.ts` | ✅ | test | 754 |  |
| `packages/opencode/test/util/error.test.ts` | ✅ | test | 38 |  |
| `packages/opencode/test/util/filesystem.test.ts` | ✅ | test | 656 |  |
| `packages/opencode/test/util/format.test.ts` | ✅ | test | 59 |  |
| `packages/opencode/test/util/glob.test.ts` | ✅ | test | 164 |  |
| `packages/opencode/test/util/iife.test.ts` | ✅ | test | 36 |  |
| `packages/opencode/test/util/lazy.test.ts` | ✅ | test | 50 |  |
| `packages/opencode/test/util/lock.test.ts` | ✅ | test | 72 |  |
| `packages/opencode/test/util/log.test.ts` | ✅ | test | 44 |  |
| `packages/opencode/test/util/module.test.ts` | ✅ | test | 59 |  |
| `packages/opencode/test/util/process.test.ts` | ✅ | test | 128 |  |
| `packages/opencode/test/util/timeout.test.ts` | ✅ | test | 21 |  |
| `packages/opencode/test/util/which.test.ts` | ✅ | test | 100 |  |
| `packages/opencode/test/util/wildcard.test.ts` | ✅ | test | 90 |  |
| `packages/opencode/tsconfig.json` | ✅ | config | 17 |  |
| `packages/plugin/.gitignore` | ✅ | source | 1 |  |
| `packages/plugin/package.json` | ✅ | source | 44 |  |
| `packages/plugin/script/publish.ts` | ✅ | source | 38 |  |
| `packages/plugin/src/example-workspace.ts` | ✅ | source | 34 | FolderWorkspacePlugin |
| `packages/plugin/src/example.ts` | ✅ | source | 18 | ExamplePlugin |
| `packages/plugin/src/index.ts` | ✅ | source | 333 |  |
| `packages/plugin/src/shell.ts` | ✅ | source | 136 |  |
| `packages/plugin/src/tool.ts` | ✅ | source | 41 | tool |
| `packages/plugin/src/tui.ts` | ✅ | source | 501 |  |
| `packages/plugin/sst-env.d.ts` | ✅ | source | 10 |  |
| `packages/plugin/tsconfig.json` | ✅ | config | 13 |  |
| `packages/script/package.json` | ✅ | source | 15 |  |
| `packages/script/src/index.ts` | ✅ | source | 77 | Script |
| `packages/script/sst-env.d.ts` | ✅ | source | 10 |  |
| `packages/script/tsconfig.json` | ✅ | config | 8 |  |
| `packages/sdk/.gitignore` | ✅ | source | 10 |  |
| `packages/sdk/js/example/example.ts` | ✅ | source | 56 |  |
| `packages/sdk/js/package.json` | ✅ | source | 34 |  |
| `packages/sdk/js/script/build.ts` | ✅ | source | 52 |  |
| `packages/sdk/js/script/publish.ts` | ✅ | source | 45 |  |
| `packages/sdk/js/src/client.ts` | ✅ | source | 55 | createOpencodeClient |
| `packages/sdk/js/src/gen/client.gen.ts` | ✅ | source | 22 | client |
| `packages/sdk/js/src/gen/client/client.gen.ts` | ✅ | source | 212 | createClient |
| `packages/sdk/js/src/gen/client/index.ts` | ✅ | source | 25 |  |
| `packages/sdk/js/src/gen/client/types.gen.ts` | ✅ | source | 222 |  |
| `packages/sdk/js/src/gen/client/utils.gen.ts` | ✅ | source | 287 | createQuerySerializer |
| `packages/sdk/js/src/gen/core/auth.gen.ts` | ✅ | source | 41 | getAuthToken |
| `packages/sdk/js/src/gen/core/bodySerializer.gen.ts` | ✅ | source | 74 | formDataBodySerializer |
| `packages/sdk/js/src/gen/core/params.gen.ts` | ✅ | source | 144 | buildClientParams |
| `packages/sdk/js/src/gen/core/pathSerializer.gen.ts` | ✅ | source | 167 | separatorArrayExplode |
| `packages/sdk/js/src/gen/core/queryKeySerializer.gen.ts` | ✅ | source | 111 | queryKeyJsonReplacer |
| `packages/sdk/js/src/gen/core/serverSentEvents.gen.ts` | ✅ | source | 210 | createSseClient |
| `packages/sdk/js/src/gen/core/types.gen.ts` | ✅ | source | 91 |  |
| `packages/sdk/js/src/gen/core/utils.gen.ts` | ✅ | source | 109 | PATH_PARAM_RE |
| `packages/sdk/js/src/gen/sdk.gen.ts` | ✅ | source | 1197 | _HeyApiClient |
| `packages/sdk/js/src/gen/types.gen.ts` | ✅ | source | 3904 |  |
| `packages/sdk/js/src/index.ts` | ✅ | source | 21 | createOpencode |
| `packages/sdk/js/src/process.ts` | ✅ | source | 31 | stop |
| `packages/sdk/js/src/server.ts` | ✅ | source | 134 | createOpencodeServer |
| `packages/sdk/js/src/v2/client.ts` | ✅ | source | 88 | createOpencodeClient |
| `packages/sdk/js/src/v2/data.ts` | ✅ | source | 32 | message |
| `packages/sdk/js/src/v2/gen/client.gen.ts` | ✅ | source | 18 | client |
| `packages/sdk/js/src/v2/gen/client/client.gen.ts` | ✅ | source | 285 | createClient |
| `packages/sdk/js/src/v2/gen/client/index.ts` | ✅ | source | 25 |  |
| `packages/sdk/js/src/v2/gen/client/types.gen.ts` | ✅ | source | 202 |  |
| `packages/sdk/js/src/v2/gen/client/utils.gen.ts` | ✅ | source | 289 | createQuerySerializer |
| `packages/sdk/js/src/v2/gen/core/auth.gen.ts` | ✅ | source | 41 | getAuthToken |
| `packages/sdk/js/src/v2/gen/core/bodySerializer.gen.ts` | ✅ | source | 82 | formDataBodySerializer |
| `packages/sdk/js/src/v2/gen/core/params.gen.ts` | ✅ | source | 169 | buildClientParams |
| `packages/sdk/js/src/v2/gen/core/pathSerializer.gen.ts` | ✅ | source | 167 | separatorArrayExplode |
| `packages/sdk/js/src/v2/gen/core/queryKeySerializer.gen.ts` | ✅ | source | 111 | queryKeyJsonReplacer |
| `packages/sdk/js/src/v2/gen/core/serverSentEvents.gen.ts` | ✅ | source | 239 | createSseClient |
| `packages/sdk/js/src/v2/gen/core/types.gen.ts` | ✅ | source | 86 |  |
| `packages/sdk/js/src/v2/gen/core/utils.gen.ts` | ✅ | source | 137 | getValidRequestBody |
| `packages/sdk/js/src/v2/gen/sdk.gen.ts` | ✅ | source | 4497 | HeyApiClient |
| `packages/sdk/js/src/v2/gen/types.gen.ts` | ✅ | source | 5546 |  |
| `packages/sdk/js/src/v2/index.ts` | ✅ | source | 23 | createOpencode |
| `packages/sdk/js/src/v2/server.ts` | ✅ | source | 134 | createOpencodeServer |
| `packages/sdk/js/sst-env.d.ts` | ✅ | source | 10 |  |
| `packages/sdk/js/tsconfig.json` | ✅ | config | 14 |  |
| `packages/sdk/openapi.json` | ✅ | source | 13688 |  |
| `packages/slack/.env.example` | ✅ | source | 3 |  |
| `packages/slack/.gitignore` | ✅ | source | 4 |  |
| `packages/slack/README.md` | ✅ | docs | 27 |  |
| `packages/slack/package.json` | ✅ | source | 19 |  |
| `packages/slack/src/index.ts` | ✅ | source | 145 |  |
| `packages/slack/sst-env.d.ts` | ✅ | source | 10 |  |
| `packages/slack/tsconfig.json` | ✅ | config | 8 |  |
| `packages/storybook/.gitignore` | ✅ | source | 3 |  |
| `packages/storybook/.storybook/main.ts` | ✅ | source | 67 |  |
| `packages/storybook/.storybook/manager.ts` | ✅ | source | 11 |  |
| `packages/storybook/.storybook/mocks/app/components/dialog-select-model-unpaid.tsx` | ✅ | source | 3 | DialogSelectModelUnpaid |
| `packages/storybook/.storybook/mocks/app/components/dialog-select-model.tsx` | ✅ | source | 7 | ModelSelectorPopover |
| `packages/storybook/.storybook/mocks/app/context/command.ts` | ✅ | source | 22 | useCommand |
| `packages/storybook/.storybook/mocks/app/context/comments.ts` | ✅ | source | 34 | useComments |
| `packages/storybook/.storybook/mocks/app/context/file.ts` | ✅ | source | 47 | selectionFromLines |
| `packages/storybook/.storybook/mocks/app/context/global-sync.ts` | ✅ | source | 42 | useGlobalSync |
| `packages/storybook/.storybook/mocks/app/context/language.ts` | ✅ | source | 75 | useLanguage |
| `packages/storybook/.storybook/mocks/app/context/layout.ts` | ✅ | source | 41 | useLayout |
| `packages/storybook/.storybook/mocks/app/context/local.ts` | ✅ | source | 41 | useLocal |
| `packages/storybook/.storybook/mocks/app/context/permission.ts` | ✅ | source | 24 | usePermission |
| `packages/storybook/.storybook/mocks/app/context/platform.ts` | ✅ | source | 16 | usePlatform |
| `packages/storybook/.storybook/mocks/app/context/prompt.ts` | ✅ | source | 117 | isPromptEqual |
| `packages/storybook/.storybook/mocks/app/context/sdk.ts` | ✅ | source | 25 | useSDK |
| `packages/storybook/.storybook/mocks/app/context/sync.ts` | ✅ | source | 32 | useSync |
| `packages/storybook/.storybook/mocks/app/hooks/use-providers.ts` | ✅ | source | 23 | useProviders |
| `packages/storybook/.storybook/mocks/solid-router.tsx` | ✅ | source | 28 | useParams |
| `packages/storybook/.storybook/playground-css-plugin.ts` | ✅ | source | 136 | playgroundCss |
| `packages/storybook/.storybook/preview.tsx` | ✅ | source | 98 |  |
| `packages/storybook/.storybook/theme-tool.ts` | ✅ | source | 21 | ThemeTool |
| `packages/storybook/package.json` | ✅ | source | 29 |  |
| `packages/storybook/sst-env.d.ts` | ✅ | source | 10 |  |
| `packages/storybook/tsconfig.json` | ✅ | config | 16 |  |
| `packages/ui/.gitignore` | ✅ | source | 26 |  |
| `packages/ui/package.json` | ✅ | source | 76 |  |
| `packages/ui/script/tailwind.ts` | ✅ | source | 23 |  |
| `packages/ui/src/components/accordion.css` | ✅ | style | 123 |  |
| `packages/ui/src/components/accordion.stories.tsx` | ✅ | source | 149 | Basic |
| `packages/ui/src/components/accordion.tsx` | ✅ | source | 92 | Accordion |
| `packages/ui/src/components/animated-number.css` | ✅ | style | 75 |  |
| `packages/ui/src/components/animated-number.tsx` | ✅ | source | 109 | AnimatedNumber |
| `packages/ui/src/components/app-icon.css` | ✅ | style | 5 |  |
| `packages/ui/src/components/app-icon.stories.tsx` | ✅ | source | 69 | Basic |
| `packages/ui/src/components/app-icon.tsx` | ✅ | source | 85 | AppIcon |
| `packages/ui/src/components/app-icons/types.ts` | ✅ | source | 21 | iconNames |
| `packages/ui/src/components/apply-patch-file.test.ts` | ✅ | test | 43 |  |
| `packages/ui/src/components/apply-patch-file.ts` | ✅ | source | 78 | patchFile |
| `packages/ui/src/components/avatar.css` | ✅ | style | 49 |  |
| `packages/ui/src/components/avatar.stories.tsx` | ✅ | source | 76 | Basic |
| `packages/ui/src/components/avatar.tsx` | ✅ | source | 55 | Avatar |
| `packages/ui/src/components/basic-tool.css` | ✅ | style | 248 |  |
| `packages/ui/src/components/basic-tool.stories.tsx` | ✅ | source | 133 | Basic |
| `packages/ui/src/components/basic-tool.tsx` | ✅ | source | 283 | BasicTool |
| `packages/ui/src/components/button.css` | ✅ | style | 194 |  |
| `packages/ui/src/components/button.stories.tsx` | ✅ | source | 108 | Primary |
| `packages/ui/src/components/button.tsx` | ✅ | source | 33 | Button |
| `packages/ui/src/components/card.css` | ✅ | style | 94 |  |
| `packages/ui/src/components/card.stories.tsx` | ✅ | source | 88 | Normal |
| `packages/ui/src/components/card.tsx` | ✅ | source | 123 | Card |
| `packages/ui/src/components/checkbox.css` | ✅ | style | 131 |  |
| `packages/ui/src/components/checkbox.stories.tsx` | ✅ | source | 71 | Basic |
| `packages/ui/src/components/checkbox.tsx` | ✅ | source | 43 | Checkbox |
| `packages/ui/src/components/collapsible.css` | ✅ | style | 148 |  |
| `packages/ui/src/components/collapsible.stories.tsx` | ✅ | source | 86 | Basic |
| `packages/ui/src/components/collapsible.tsx` | ✅ | source | 48 | Collapsible |
| `packages/ui/src/components/context-menu.css` | ✅ | style | 134 |  |
| `packages/ui/src/components/context-menu.stories.tsx` | ✅ | source | 113 | Basic |
| `packages/ui/src/components/context-menu.tsx` | ✅ | source | 308 | ContextMenu |
| `packages/ui/src/components/dialog.css` | ✅ | style | 181 |  |
| `packages/ui/src/components/dialog.stories.tsx` | ✅ | source | 173 | Basic |
| `packages/ui/src/components/dialog.tsx` | ✅ | source | 72 | Dialog |
| `packages/ui/src/components/diff-changes.css` | ✅ | style | 42 |  |
| `packages/ui/src/components/diff-changes.stories.tsx` | ✅ | source | 81 | Default |
| `packages/ui/src/components/diff-changes.tsx` | ✅ | source | 115 | DiffChanges |
| `packages/ui/src/components/dock-prompt.stories.tsx` | ✅ | source | 62 | Basic |
| `packages/ui/src/components/dock-prompt.tsx` | ✅ | source | 23 | DockPrompt |
| `packages/ui/src/components/dock-surface.css` | ✅ | style | 23 |  |
| `packages/ui/src/components/dock-surface.tsx` | ✅ | source | 54 | DockShell |
| `packages/ui/src/components/dropdown-menu.css` | ✅ | style | 135 |  |
| `packages/ui/src/components/dropdown-menu.stories.tsx` | ✅ | source | 97 | Basic |
| `packages/ui/src/components/dropdown-menu.tsx` | ✅ | source | 308 | DropdownMenu |
| `packages/ui/src/components/favicon.stories.tsx` | ✅ | source | 49 | Basic |
| `packages/ui/src/components/favicon.tsx` | ✅ | source | 13 | Favicon |
| `packages/ui/src/components/file-icon.css` | ✅ | style | 26 |  |
| `packages/ui/src/components/file-icon.stories.tsx` | ✅ | source | 94 | Basic |
| `packages/ui/src/components/file-icon.tsx` | ✅ | source | 588 | chooseIconName |
| `packages/ui/src/components/file-icons/types.ts` | ✅ | source | 1095 | iconNames |
| `packages/ui/src/components/file-media.tsx` | ✅ | source | 267 | FileMedia |
| `packages/ui/src/components/file-search.tsx` | ✅ | source | 72 | FileSearchBar |
| `packages/ui/src/components/file-ssr.tsx` | ✅ | source | 193 | FileSSR |
| `packages/ui/src/components/file.css` | ✅ | style | 42 |  |
| `packages/ui/src/components/file.tsx` | ✅ | source | 1132 | File |
| `packages/ui/src/components/font.stories.tsx` | ✅ | source | 48 | Basic |
| `packages/ui/src/components/font.tsx` | ✅ | source | 1 | Font |
| `packages/ui/src/components/hover-card.css` | ✅ | style | 61 |  |
| `packages/ui/src/components/hover-card.stories.tsx` | ✅ | source | 70 | Basic |
| `packages/ui/src/components/hover-card.tsx` | ✅ | source | 32 | HoverCard |
| `packages/ui/src/components/icon-button.css` | ✅ | style | 181 |  |
| `packages/ui/src/components/icon-button.stories.tsx` | ✅ | source | 74 | Basic |
| `packages/ui/src/components/icon-button.tsx` | ✅ | source | 29 | IconButton |
| `packages/ui/src/components/icon.css` | ✅ | style | 34 |  |
| `packages/ui/src/components/icon.stories.tsx` | ✅ | source | 170 | Basic |
| `packages/ui/src/components/icon.tsx` | ✅ | source | 133 | Icon |
| `packages/ui/src/components/image-preview.css` | ✅ | style | 63 |  |
| `packages/ui/src/components/image-preview.stories.tsx` | ✅ | source | 59 | Basic |
| `packages/ui/src/components/image-preview.tsx` | ✅ | source | 32 | ImagePreview |
| `packages/ui/src/components/inline-input.css` | ✅ | style | 17 |  |
| `packages/ui/src/components/inline-input.stories.tsx` | ✅ | source | 50 | Basic |
| `packages/ui/src/components/inline-input.tsx` | ✅ | source | 22 | InlineInput |
| `packages/ui/src/components/keybind.css` | ✅ | style | 18 |  |
| `packages/ui/src/components/keybind.stories.tsx` | ✅ | source | 43 | Basic |
| `packages/ui/src/components/keybind.tsx` | ✅ | source | 20 | Keybind |
| `packages/ui/src/components/line-comment-annotations.tsx` | ✅ | source | 596 | createLineCommentAnnotationRenderer |
| `packages/ui/src/components/line-comment-styles.ts` | ✅ | source | 292 | installLineCommentStyles |
| `packages/ui/src/components/line-comment.stories.tsx` | ✅ | source | 115 | Default |
| `packages/ui/src/components/line-comment.tsx` | ✅ | source | 438 | LineCommentAnchor |
| `packages/ui/src/components/list.css` | ✅ | style | 331 |  |
| `packages/ui/src/components/list.stories.tsx` | ✅ | source | 170 | Basic |
| `packages/ui/src/components/list.tsx` | ✅ | source | 394 | List |
| `packages/ui/src/components/logo.css` | ✅ | style | 4 |  |
| `packages/ui/src/components/logo.stories.tsx` | ✅ | source | 57 | Basic |
| `packages/ui/src/components/logo.tsx` | ✅ | source | 62 | Mark |
| `packages/ui/src/components/markdown-stream.test.ts` | ✅ | test | 32 |  |
| `packages/ui/src/components/markdown-stream.ts` | ✅ | source | 49 | stream |
| `packages/ui/src/components/markdown.css` | ✅ | style | 266 |  |
| `packages/ui/src/components/markdown.stories.tsx` | ✅ | source | 53 | Basic |
| `packages/ui/src/components/markdown.tsx` | ✅ | source | 348 | Markdown |
| `packages/ui/src/components/message-file.test.ts` | ✅ | test | 55 |  |
| `packages/ui/src/components/message-file.ts` | ✅ | source | 14 | attached |
| `packages/ui/src/components/message-nav.css` | ✅ | style | 123 |  |
| `packages/ui/src/components/message-nav.stories.tsx` | ✅ | source | 7 | Basic |
| `packages/ui/src/components/message-nav.tsx` | ✅ | source | 92 | MessageNav |
| `packages/ui/src/components/message-part.css` | ✅ | style | 1275 |  |
| `packages/ui/src/components/message-part.stories.tsx` | ✅ | source | 7 | Basic |
| `packages/ui/src/components/message-part.tsx` | ✅ | source | 2293 | getToolInfo |
| `packages/ui/src/components/motion-spring.tsx` | ✅ | source | 45 | useSpring |
| `packages/ui/src/components/popover.css` | ✅ | style | 98 |  |
| `packages/ui/src/components/popover.stories.tsx` | ✅ | source | 87 | Basic |
| `packages/ui/src/components/popover.tsx` | ✅ | source | 153 | Popover |
| `packages/ui/src/components/progress-circle.css` | ✅ | style | 12 |  |
| `packages/ui/src/components/progress-circle.stories.tsx` | ✅ | source | 59 | Basic |
| `packages/ui/src/components/progress-circle.tsx` | ✅ | source | 57 | ProgressCircle |
| `packages/ui/src/components/progress.css` | ✅ | style | 63 |  |
| `packages/ui/src/components/progress.stories.tsx` | ✅ | source | 67 | Basic |
| `packages/ui/src/components/progress.tsx` | ✅ | source | 39 | Progress |
| `packages/ui/src/components/provider-icon.css` | ✅ | style | 5 |  |
| `packages/ui/src/components/provider-icon.stories.tsx` | ✅ | source | 69 | Basic |
| `packages/ui/src/components/provider-icon.tsx` | ✅ | source | 25 | ProviderIcon |
| `packages/ui/src/components/provider-icons/types.ts` | ✅ | source | 104 | iconNames |
| `packages/ui/src/components/radio-group.css` | ✅ | style | 187 |  |
| `packages/ui/src/components/radio-group.stories.tsx` | ✅ | source | 92 | Basic |
| `packages/ui/src/components/radio-group.tsx` | ✅ | source | 83 | RadioGroup |
| `packages/ui/src/components/resize-handle.css` | ✅ | style | 58 |  |
| `packages/ui/src/components/resize-handle.stories.tsx` | ✅ | source | 161 | Basic |
| `packages/ui/src/components/resize-handle.tsx` | ✅ | source | 82 | ResizeHandle |
| `packages/ui/src/components/scroll-view.css` | ✅ | style | 62 |  |
| `packages/ui/src/components/scroll-view.test.ts` | ✅ | test | 19 |  |
| `packages/ui/src/components/scroll-view.tsx` | ✅ | source | 237 | ScrollView |
| `packages/ui/src/components/select.css` | ✅ | style | 202 |  |
| `packages/ui/src/components/select.stories.tsx` | ✅ | source | 113 | Basic |
| `packages/ui/src/components/select.tsx` | ✅ | source | 174 | Select |
| `packages/ui/src/components/session-diff.test.ts` | ✅ | test | 37 |  |
| `packages/ui/src/components/session-diff.ts` | ✅ | source | 92 | normalize |
| `packages/ui/src/components/session-retry.tsx` | ✅ | source | 74 | SessionRetry |
| `packages/ui/src/components/session-review.css` | ✅ | style | 237 |  |
| `packages/ui/src/components/session-review.stories.tsx` | ✅ | source | 7 | Basic |
| `packages/ui/src/components/session-review.tsx` | ✅ | source | 650 | SessionReview |
| `packages/ui/src/components/session-turn.css` | ✅ | style | 231 |  |
| `packages/ui/src/components/session-turn.stories.tsx` | ✅ | source | 7 | Basic |
| `packages/ui/src/components/session-turn.tsx` | ✅ | source | 533 | SessionTurn |
| `packages/ui/src/components/shell-submessage-motion.stories.tsx` | ✅ | source | 346 | Playground |
| `packages/ui/src/components/shell-submessage.css` | ✅ | style | 23 |  |
| `packages/ui/src/components/spinner.css` | ✅ | style | 6 |  |
| `packages/ui/src/components/spinner.stories.tsx` | ✅ | source | 53 | Basic |
| `packages/ui/src/components/spinner.tsx` | ✅ | source | 52 | Spinner |
| `packages/ui/src/components/sticky-accordion-header.css` | ✅ | style | 6 |  |
| `packages/ui/src/components/sticky-accordion-header.stories.tsx` | ✅ | source | 54 | Basic |
| `packages/ui/src/components/sticky-accordion-header.tsx` | ✅ | source | 18 | StickyAccordionHeader |
| `packages/ui/src/components/switch.css` | ✅ | style | 132 |  |
| `packages/ui/src/components/switch.stories.tsx` | ✅ | source | 68 | Basic |
| `packages/ui/src/components/switch.tsx` | ✅ | source | 29 | Switch |
| `packages/ui/src/components/tabs.css` | ✅ | style | 635 |  |
| `packages/ui/src/components/tabs.stories.tsx` | ✅ | source | 179 | Basic |
| `packages/ui/src/components/tabs.tsx` | ✅ | source | 125 | Tabs |
| `packages/ui/src/components/tag.css` | ✅ | style | 37 |  |
| `packages/ui/src/components/tag.stories.tsx` | ✅ | source | 58 | Basic |
| `packages/ui/src/components/tag.tsx` | ✅ | source | 22 | Tag |
| `packages/ui/src/components/text-field.css` | ✅ | style | 134 |  |
| `packages/ui/src/components/text-field.stories.tsx` | ✅ | source | 111 | Basic |
| `packages/ui/src/components/text-field.tsx` | ✅ | source | 128 | TextField |
| `packages/ui/src/components/text-reveal.css` | ✅ | style | 150 |  |
| `packages/ui/src/components/text-reveal.stories.tsx` | ✅ | source | 320 | Playground |
| `packages/ui/src/components/text-reveal.tsx` | ✅ | source | 143 | TextReveal |
| `packages/ui/src/components/text-shimmer.css` | ✅ | style | 119 |  |
| `packages/ui/src/components/text-shimmer.stories.tsx` | ✅ | source | 92 | Basic |
| `packages/ui/src/components/text-shimmer.tsx` | ✅ | source | 62 | TextShimmer |
| `packages/ui/src/components/text-strikethrough.css` | ✅ | style | 27 |  |
| `packages/ui/src/components/text-strikethrough.stories.tsx` | ✅ | source | 279 | Playground |
| `packages/ui/src/components/text-strikethrough.tsx` | ✅ | source | 84 | TextStrikethrough |
| `packages/ui/src/components/thinking-heading.stories.tsx` | ✅ | source | 854 | Playground |
| `packages/ui/src/components/timeline-playground.stories.tsx` | ✅ | source | 2041 | sum |
| `packages/ui/src/components/toast.css` | ✅ | style | 236 |  |
| `packages/ui/src/components/toast.stories.tsx` | ✅ | source | 138 | Basic |
| `packages/ui/src/components/toast.tsx` | ✅ | source | 185 | showToast |
| `packages/ui/src/components/todo-panel-motion.stories.tsx` | ✅ | source | 605 | Playground |
| `packages/ui/src/components/tool-count-label.css` | ✅ | style | 57 |  |
| `packages/ui/src/components/tool-count-label.tsx` | ✅ | source | 58 | AnimatedCountLabel |
| `packages/ui/src/components/tool-count-summary.css` | ✅ | style | 102 |  |
| `packages/ui/src/components/tool-count-summary.stories.tsx` | ✅ | source | 238 | Playground |
| `packages/ui/src/components/tool-count-summary.tsx` | ✅ | source | 52 | AnimatedCountList |
| `packages/ui/src/components/tool-error-card.css` | ✅ | style | 54 |  |
| `packages/ui/src/components/tool-error-card.stories.tsx` | ✅ | source | 92 | All |
| `packages/ui/src/components/tool-error-card.tsx` | ✅ | source | 143 | ToolErrorCard |
| `packages/ui/src/components/tool-status-title.css` | ✅ | style | 89 |  |
| `packages/ui/src/components/tool-status-title.tsx` | ✅ | source | 138 | ToolStatusTitle |
| `packages/ui/src/components/tooltip.css` | ✅ | style | 74 |  |
| `packages/ui/src/components/tooltip.stories.tsx` | ✅ | source | 64 | Basic |
| `packages/ui/src/components/tooltip.tsx` | ✅ | source | 161 | TooltipKeybind |
| `packages/ui/src/components/typewriter.css` | ✅ | style | 14 |  |
| `packages/ui/src/components/typewriter.stories.tsx` | ✅ | source | 51 | Basic |
| `packages/ui/src/components/typewriter.tsx` | ✅ | source | 55 | Typewriter |
| `packages/ui/src/context/data.tsx` | ✅ | source | 52 |  |
| `packages/ui/src/context/dialog.tsx` | ✅ | source | 163 | DialogProvider |
| `packages/ui/src/context/file.tsx` | ✅ | source | 10 | FileComponentProvider |
| `packages/ui/src/context/helper.tsx` | ✅ | source | 37 | createSimpleContext |
| `packages/ui/src/context/i18n.tsx` | ✅ | source | 38 | I18nProvider |
| `packages/ui/src/context/index.ts` | ✅ | source | 5 |  |
| `packages/ui/src/context/marked.tsx` | ✅ | source | 519 |  |
| `packages/ui/src/context/worker-pool.tsx` | ✅ | source | 20 | useWorkerPool |
| `packages/ui/src/custom-elements.d.ts` | ✅ | source | 17 |  |
| `packages/ui/src/hooks/create-auto-scroll.tsx` | ✅ | source | 237 | createAutoScroll |
| `packages/ui/src/hooks/index.ts` | ✅ | source | 2 |  |
| `packages/ui/src/hooks/use-filtered-list.tsx` | ✅ | source | 129 | useFilteredList |
| `packages/ui/src/i18n/ar.ts` | ✅ | source | 159 | dict |
| `packages/ui/src/i18n/br.ts` | ✅ | source | 159 | dict |
| `packages/ui/src/i18n/bs.ts` | ✅ | source | 163 | dict |
| `packages/ui/src/i18n/da.ts` | ✅ | source | 158 | dict |
| `packages/ui/src/i18n/de.ts` | ✅ | source | 164 | dict |
| `packages/ui/src/i18n/en.ts` | ✅ | source | 167 | dict |
| `packages/ui/src/i18n/es.ts` | ✅ | source | 159 | dict |
| `packages/ui/src/i18n/fr.ts` | ✅ | source | 159 | dict |
| `packages/ui/src/i18n/ja.ts` | ✅ | source | 158 | dict |
| `packages/ui/src/i18n/ko.ts` | ✅ | source | 159 | dict |
| `packages/ui/src/i18n/no.ts` | ✅ | source | 162 | dict |
| `packages/ui/src/i18n/pl.ts` | ✅ | source | 158 | dict |
| `packages/ui/src/i18n/ru.ts` | ✅ | source | 158 | dict |
| `packages/ui/src/i18n/th.ts` | ✅ | source | 160 | dict |
| `packages/ui/src/i18n/tr.ts` | ✅ | source | 165 | dict |
| `packages/ui/src/i18n/zh.ts` | ✅ | source | 163 | dict |
| `packages/ui/src/i18n/zht.ts` | ✅ | source | 163 | dict |
| `packages/ui/src/pierre/comment-hover.ts` | ✅ | source | 74 | createHoverCommentUtility |
| `packages/ui/src/pierre/commented-lines.ts` | ✅ | source | 91 | markCommentedDiffLines |
| `packages/ui/src/pierre/diff-selection.ts` | ✅ | source | 71 | findDiffSide |
| `packages/ui/src/pierre/file-find.ts` | ✅ | source | 485 | createFileFind |
| `packages/ui/src/pierre/file-runtime.ts` | ✅ | source | 114 | createReadyWatcher |
| `packages/ui/src/pierre/file-selection.ts` | ✅ | source | 85 | findElement |
| `packages/ui/src/pierre/index.ts` | ✅ | source | 191 | createDefaultOptions |
| `packages/ui/src/pierre/media.ts` | ✅ | source | 110 | normalizeMimeType |
| `packages/ui/src/pierre/selection-bridge.ts` | ✅ | source | 132 | formatSelectedLineLabel |
| `packages/ui/src/pierre/virtualizer.ts` | ✅ | source | 100 | acquireVirtualizer |
| `packages/ui/src/pierre/worker.ts` | ✅ | source | 52 | workerFactory |
| `packages/ui/src/storybook/fixtures.ts` | ✅ | source | 51 | average |
| `packages/ui/src/storybook/scaffold.tsx` | ✅ | source | 62 | create |
| `packages/ui/src/styles/animations.css` | ✅ | style | 141 |  |
| `packages/ui/src/styles/base.css` | ✅ | style | 404 |  |
| `packages/ui/src/styles/colors.css` | ✅ | style | 772 |  |
| `packages/ui/src/styles/index.css` | ✅ | style | 65 |  |
| `packages/ui/src/styles/tailwind/colors.css` | ✅ | style | 235 |  |
| `packages/ui/src/styles/tailwind/index.css` | ✅ | style | 78 |  |
| `packages/ui/src/styles/tailwind/utilities.css` | ✅ | style | 123 |  |
| `packages/ui/src/styles/theme.css` | ✅ | style | 609 |  |
| `packages/ui/src/styles/utilities.css` | ✅ | style | 118 |  |
| `packages/ui/src/theme/color.ts` | ✅ | source | 286 | hexToRgb |
| `packages/ui/src/theme/context.tsx` | ✅ | source | 359 |  |
| `packages/ui/src/theme/default-themes.ts` | ✅ | source | 116 | oc2Theme |
| `packages/ui/src/theme/desktop-theme.schema.json` | ✅ | source | 161 |  |
| `packages/ui/src/theme/index.ts` | ✅ | source | 75 |  |
| `packages/ui/src/theme/loader.ts` | ✅ | source | 103 | applyTheme |
| `packages/ui/src/theme/resolve.ts` | ✅ | source | 540 | resolveThemeVariant |
| `packages/ui/src/theme/themes/amoled.json` | ✅ | source | 49 |  |
| `packages/ui/src/theme/themes/aura.json` | ✅ | source | 51 |  |
| `packages/ui/src/theme/themes/ayu.json` | ✅ | source | 51 |  |
| `packages/ui/src/theme/themes/carbonfox.json` | ✅ | source | 53 |  |
| `packages/ui/src/theme/themes/catppuccin-frappe.json` | ✅ | source | 85 |  |
| `packages/ui/src/theme/themes/catppuccin-macchiato.json` | ✅ | source | 85 |  |
| `packages/ui/src/theme/themes/catppuccin.json` | ✅ | source | 45 |  |
| `packages/ui/src/theme/themes/cobalt2.json` | ✅ | source | 87 |  |
| `packages/ui/src/theme/themes/cursor.json` | ✅ | source | 91 |  |
| `packages/ui/src/theme/themes/dracula.json` | ✅ | source | 49 |  |
| `packages/ui/src/theme/themes/everforest.json` | ✅ | source | 89 |  |
| `packages/ui/src/theme/themes/flexoki.json` | ✅ | source | 86 |  |
| `packages/ui/src/theme/themes/github.json` | ✅ | source | 85 |  |
| `packages/ui/src/theme/themes/gruvbox.json` | ✅ | source | 45 |  |
| `packages/ui/src/theme/themes/kanagawa.json` | ✅ | source | 89 |  |
| `packages/ui/src/theme/themes/lucent-orng.json` | ✅ | source | 87 |  |
| `packages/ui/src/theme/themes/material.json` | ✅ | source | 87 |  |
| `packages/ui/src/theme/themes/matrix.json` | ✅ | source | 91 |  |
| `packages/ui/src/theme/themes/mercury.json` | ✅ | source | 86 |  |
| `packages/ui/src/theme/themes/monokai.json` | ✅ | source | 49 |  |
| `packages/ui/src/theme/themes/nightowl.json` | ✅ | source | 46 |  |
| `packages/ui/src/theme/themes/nord.json` | ✅ | source | 46 |  |
| `packages/ui/src/theme/themes/oc-2.json` | ✅ | source | 88 |  |
| `packages/ui/src/theme/themes/one-dark.json` | ✅ | source | 89 |  |
| `packages/ui/src/theme/themes/onedarkpro.json` | ✅ | source | 45 |  |
| `packages/ui/src/theme/themes/opencode.json` | ✅ | source | 89 |  |
| `packages/ui/src/theme/themes/orng.json` | ✅ | source | 87 |  |
| `packages/ui/src/theme/themes/osaka-jade.json` | ✅ | source | 88 |  |
| `packages/ui/src/theme/themes/palenight.json` | ✅ | source | 85 |  |
| `packages/ui/src/theme/themes/rosepine.json` | ✅ | source | 85 |  |
| `packages/ui/src/theme/themes/shadesofpurple.json` | ✅ | source | 51 |  |
| `packages/ui/src/theme/themes/solarized.json` | ✅ | source | 49 |  |
| `packages/ui/src/theme/themes/synthwave84.json` | ✅ | source | 87 |  |
| `packages/ui/src/theme/themes/tokyonight.json` | ✅ | source | 47 |  |
| `packages/ui/src/theme/themes/vercel.json` | ✅ | source | 90 |  |
| `packages/ui/src/theme/themes/vesper.json` | ✅ | source | 51 |  |
| `packages/ui/src/theme/themes/zenburn.json` | ✅ | source | 87 |  |
| `packages/ui/src/theme/types.ts` | ✅ | source | 70 |  |
| `packages/ui/sst-env.d.ts` | ✅ | source | 10 |  |
| `packages/ui/tsconfig.json` | ✅ | config | 22 |  |
| `packages/ui/vite.config.ts` | ✅ | config | 59 |  |
| `packages/web/.gitignore` | ✅ | source | 21 |  |
| `packages/web/README.md` | ✅ | docs | 54 |  |
| `packages/web/package.json` | ✅ | source | 44 |  |
| `packages/web/public/theme.json` | ✅ | source | 183 |  |
| `packages/web/src/components/Share.tsx` | ✅ | source | 644 | fromV1 |
| `packages/web/src/components/icons/custom.tsx` | ✅ | source | 87 | IconOpenAI |
| `packages/web/src/components/icons/index.tsx` | ✅ | source | 4454 | IconAcademicCap |
| `packages/web/src/components/share.module.css` | ✅ | style | 832 |  |
| `packages/web/src/components/share/common.tsx` | ✅ | source | 128 | ShareI18nProvider |
| `packages/web/src/components/share/content-bash.module.css` | ✅ | style | 85 |  |
| `packages/web/src/components/share/content-bash.tsx` | ✅ | source | 68 | ContentBash |
| `packages/web/src/components/share/content-code.module.css` | ✅ | style | 26 |  |
| `packages/web/src/components/share/content-code.tsx` | ✅ | source | 30 | ContentCode |
| `packages/web/src/components/share/content-diff.module.css` | ✅ | style | 153 |  |
| `packages/web/src/components/share/content-diff.tsx` | ✅ | source | 240 | ContentDiff |
| `packages/web/src/components/share/content-error.module.css` | ✅ | style | 64 |  |
| `packages/web/src/components/share/content-error.tsx` | ✅ | source | 25 | ContentError |
| `packages/web/src/components/share/content-markdown.module.css` | ✅ | style | 154 |  |
| `packages/web/src/components/share/content-markdown.tsx` | ✅ | source | 74 | ContentMarkdown |
| `packages/web/src/components/share/content-text.module.css` | ✅ | style | 63 |  |
| `packages/web/src/components/share/content-text.tsx` | ✅ | source | 38 | ContentText |
| `packages/web/src/components/share/copy-button.module.css` | ✅ | style | 30 |  |
| `packages/web/src/components/share/copy-button.tsx` | ✅ | source | 36 | CopyButton |
| `packages/web/src/components/share/part.module.css` | ✅ | style | 428 |  |
| `packages/web/src/components/share/part.tsx` | ✅ | source | 817 | Part |
| `packages/web/src/content.config.ts` | ✅ | config | 16 |  |
| `packages/web/src/content/docs/acp.mdx` | ✅ | docs | 156 |  |
| `packages/web/src/content/docs/agents.mdx` | ✅ | docs | 773 |  |
| `packages/web/src/content/docs/ar/acp.mdx` | ✅ | docs | 156 |  |
| `packages/web/src/content/docs/ar/agents.mdx` | ✅ | docs | 746 |  |
| `packages/web/src/content/docs/ar/cli.mdx` | ✅ | docs | 602 |  |
| `packages/web/src/content/docs/ar/commands.mdx` | ✅ | docs | 322 |  |
| `packages/web/src/content/docs/ar/config.mdx` | ✅ | config | 685 |  |
| `packages/web/src/content/docs/ar/custom-tools.mdx` | ✅ | docs | 196 |  |
| `packages/web/src/content/docs/ar/ecosystem.mdx` | ✅ | docs | 78 |  |
| `packages/web/src/content/docs/ar/enterprise.mdx` | ✅ | docs | 165 |  |
| `packages/web/src/content/docs/ar/formatters.mdx` | ✅ | docs | 131 |  |
| `packages/web/src/content/docs/ar/github.mdx` | ✅ | docs | 321 |  |
| `packages/web/src/content/docs/ar/gitlab.mdx` | ✅ | docs | 195 |  |
| `packages/web/src/content/docs/ar/go.mdx` | ✅ | docs | 182 |  |
| `packages/web/src/content/docs/ar/ide.mdx` | ✅ | docs | 48 |  |
| `packages/web/src/content/docs/ar/index.mdx` | ✅ | docs | 344 |  |
| `packages/web/src/content/docs/ar/keybinds.mdx` | ✅ | docs | 194 |  |
| `packages/web/src/content/docs/ar/lsp.mdx` | ✅ | docs | 188 |  |
| `packages/web/src/content/docs/ar/mcp-servers.mdx` | ✅ | docs | 511 |  |
| `packages/web/src/content/docs/ar/models.mdx` | ✅ | docs | 222 |  |
| `packages/web/src/content/docs/ar/network.mdx` | ✅ | docs | 57 |  |
| `packages/web/src/content/docs/ar/permissions.mdx` | ✅ | docs | 235 |  |
| `packages/web/src/content/docs/ar/plugins.mdx` | ✅ | docs | 385 |  |
| `packages/web/src/content/docs/ar/providers.mdx` | ✅ | docs | 1983 |  |
| `packages/web/src/content/docs/ar/rules.mdx` | ✅ | docs | 180 |  |
| `packages/web/src/content/docs/ar/sdk.mdx` | ✅ | docs | 463 |  |
| `packages/web/src/content/docs/ar/server.mdx` | ✅ | docs | 287 |  |
| `packages/web/src/content/docs/ar/share.mdx` | ✅ | docs | 127 |  |
| `packages/web/src/content/docs/ar/skills.mdx` | ✅ | docs | 222 |  |
| `packages/web/src/content/docs/ar/themes.mdx` | ✅ | docs | 369 |  |
| `packages/web/src/content/docs/ar/tools.mdx` | ✅ | docs | 341 |  |
| `packages/web/src/content/docs/ar/troubleshooting.mdx` | ✅ | docs | 299 |  |
| `packages/web/src/content/docs/ar/tui.mdx` | ✅ | docs | 390 |  |
| `packages/web/src/content/docs/ar/web.mdx` | ✅ | docs | 142 |  |
| `packages/web/src/content/docs/ar/windows-wsl.mdx` | ✅ | docs | 113 |  |
| `packages/web/src/content/docs/ar/zen.mdx` | ✅ | docs | 289 |  |
| `packages/web/src/content/docs/bs/acp.mdx` | ✅ | docs | 156 |  |
| `packages/web/src/content/docs/bs/agents.mdx` | ✅ | docs | 746 |  |
| `packages/web/src/content/docs/bs/cli.mdx` | ✅ | docs | 600 |  |
| `packages/web/src/content/docs/bs/commands.mdx` | ✅ | docs | 316 |  |
| `packages/web/src/content/docs/bs/config.mdx` | ✅ | config | 685 |  |
| `packages/web/src/content/docs/bs/custom-tools.mdx` | ✅ | docs | 195 |  |
| `packages/web/src/content/docs/bs/ecosystem.mdx` | ✅ | docs | 78 |  |
| `packages/web/src/content/docs/bs/enterprise.mdx` | ✅ | docs | 165 |  |
| `packages/web/src/content/docs/bs/formatters.mdx` | ✅ | docs | 124 |  |
| `packages/web/src/content/docs/bs/github.mdx` | ✅ | docs | 311 |  |
| `packages/web/src/content/docs/bs/gitlab.mdx` | ✅ | docs | 188 |  |
| `packages/web/src/content/docs/bs/go.mdx` | ✅ | docs | 196 |  |
| `packages/web/src/content/docs/bs/ide.mdx` | ✅ | docs | 47 |  |
| `packages/web/src/content/docs/bs/index.mdx` | ✅ | docs | 323 |  |
| `packages/web/src/content/docs/bs/keybinds.mdx` | ✅ | docs | 194 |  |
| `packages/web/src/content/docs/bs/lsp.mdx` | ✅ | docs | 185 |  |
| `packages/web/src/content/docs/bs/mcp-servers.mdx` | ✅ | docs | 482 |  |
| `packages/web/src/content/docs/bs/models.mdx` | ✅ | docs | 201 |  |
| `packages/web/src/content/docs/bs/network.mdx` | ✅ | docs | 51 |  |
| `packages/web/src/content/docs/bs/permissions.mdx` | ✅ | docs | 228 |  |
| `packages/web/src/content/docs/bs/plugins.mdx` | ✅ | docs | 371 |  |
| `packages/web/src/content/docs/bs/providers.mdx` | ✅ | docs | 1993 |  |
| `packages/web/src/content/docs/bs/rules.mdx` | ✅ | docs | 180 |  |
| `packages/web/src/content/docs/bs/sdk.mdx` | ✅ | docs | 463 |  |
| `packages/web/src/content/docs/bs/server.mdx` | ✅ | docs | 284 |  |
| `packages/web/src/content/docs/bs/share.mdx` | ✅ | docs | 127 |  |
| `packages/web/src/content/docs/bs/skills.mdx` | ✅ | docs | 222 |  |
| `packages/web/src/content/docs/bs/themes.mdx` | ✅ | docs | 369 |  |
| `packages/web/src/content/docs/bs/tools.mdx` | ✅ | docs | 341 |  |
| `packages/web/src/content/docs/bs/troubleshooting.mdx` | ✅ | docs | 300 |  |
| `packages/web/src/content/docs/bs/tui.mdx` | ✅ | docs | 403 |  |
| `packages/web/src/content/docs/bs/web.mdx` | ✅ | docs | 142 |  |
| `packages/web/src/content/docs/bs/windows-wsl.mdx` | ✅ | docs | 113 |  |
| `packages/web/src/content/docs/bs/zen.mdx` | ✅ | docs | 307 |  |
| `packages/web/src/content/docs/cli.mdx` | ✅ | docs | 617 |  |
| `packages/web/src/content/docs/commands.mdx` | ✅ | docs | 323 |  |
| `packages/web/src/content/docs/config.mdx` | ✅ | config | 825 |  |
| `packages/web/src/content/docs/custom-tools.mdx` | ✅ | docs | 196 |  |
| `packages/web/src/content/docs/da/acp.mdx` | ✅ | docs | 156 |  |
| `packages/web/src/content/docs/da/agents.mdx` | ✅ | docs | 747 |  |
| `packages/web/src/content/docs/da/cli.mdx` | ✅ | docs | 603 |  |
| `packages/web/src/content/docs/da/commands.mdx` | ✅ | docs | 323 |  |
| `packages/web/src/content/docs/da/config.mdx` | ✅ | config | 688 |  |
| `packages/web/src/content/docs/da/custom-tools.mdx` | ✅ | docs | 196 |  |
| `packages/web/src/content/docs/da/ecosystem.mdx` | ✅ | docs | 78 |  |
| `packages/web/src/content/docs/da/enterprise.mdx` | ✅ | docs | 170 |  |
| `packages/web/src/content/docs/da/formatters.mdx` | ✅ | docs | 131 |  |
| `packages/web/src/content/docs/da/github.mdx` | ✅ | docs | 321 |  |
| `packages/web/src/content/docs/da/gitlab.mdx` | ✅ | docs | 195 |  |
| `packages/web/src/content/docs/da/go.mdx` | ✅ | docs | 196 |  |
| `packages/web/src/content/docs/da/ide.mdx` | ✅ | docs | 48 |  |
| `packages/web/src/content/docs/da/index.mdx` | ✅ | docs | 360 |  |
| `packages/web/src/content/docs/da/keybinds.mdx` | ✅ | docs | 194 |  |
| `packages/web/src/content/docs/da/lsp.mdx` | ✅ | docs | 189 |  |
| `packages/web/src/content/docs/da/mcp-servers.mdx` | ✅ | docs | 511 |  |
| `packages/web/src/content/docs/da/models.mdx` | ✅ | docs | 223 |  |
| `packages/web/src/content/docs/da/network.mdx` | ✅ | docs | 57 |  |
| `packages/web/src/content/docs/da/permissions.mdx` | ✅ | docs | 235 |  |
| `packages/web/src/content/docs/da/plugins.mdx` | ✅ | docs | 389 |  |
| `packages/web/src/content/docs/da/providers.mdx` | ✅ | docs | 1981 |  |
| `packages/web/src/content/docs/da/rules.mdx` | ✅ | docs | 180 |  |
| `packages/web/src/content/docs/da/sdk.mdx` | ✅ | docs | 463 |  |
| `packages/web/src/content/docs/da/server.mdx` | ✅ | docs | 287 |  |
| `packages/web/src/content/docs/da/share.mdx` | ✅ | docs | 128 |  |
| `packages/web/src/content/docs/da/skills.mdx` | ✅ | docs | 222 |  |
| `packages/web/src/content/docs/da/themes.mdx` | ✅ | docs | 369 |  |
| `packages/web/src/content/docs/da/tools.mdx` | ✅ | docs | 341 |  |
| `packages/web/src/content/docs/da/troubleshooting.mdx` | ✅ | docs | 300 |  |
| `packages/web/src/content/docs/da/tui.mdx` | ✅ | docs | 397 |  |
| `packages/web/src/content/docs/da/web.mdx` | ✅ | docs | 142 |  |
| `packages/web/src/content/docs/da/windows-wsl.mdx` | ✅ | docs | 113 |  |
| `packages/web/src/content/docs/da/zen.mdx` | ✅ | docs | 302 |  |
| `packages/web/src/content/docs/de/acp.mdx` | ✅ | docs | 156 |  |
| `packages/web/src/content/docs/de/agents.mdx` | ✅ | docs | 733 |  |
| `packages/web/src/content/docs/de/cli.mdx` | ✅ | docs | 602 |  |
| `packages/web/src/content/docs/de/commands.mdx` | ✅ | docs | 323 |  |
| `packages/web/src/content/docs/de/config.mdx` | ✅ | config | 684 |  |
| `packages/web/src/content/docs/de/custom-tools.mdx` | ✅ | docs | 170 |  |
| `packages/web/src/content/docs/de/ecosystem.mdx` | ✅ | docs | 78 |  |
| `packages/web/src/content/docs/de/enterprise.mdx` | ✅ | docs | 170 |  |
| `packages/web/src/content/docs/de/formatters.mdx` | ✅ | docs | 131 |  |
| `packages/web/src/content/docs/de/github.mdx` | ✅ | docs | 321 |  |
| `packages/web/src/content/docs/de/gitlab.mdx` | ✅ | docs | 195 |  |
| `packages/web/src/content/docs/de/go.mdx` | ✅ | docs | 184 |  |
| `packages/web/src/content/docs/de/ide.mdx` | ✅ | docs | 48 |  |
| `packages/web/src/content/docs/de/index.mdx` | ✅ | docs | 356 |  |
| `packages/web/src/content/docs/de/keybinds.mdx` | ✅ | docs | 194 |  |
| `packages/web/src/content/docs/de/lsp.mdx` | ✅ | docs | 188 |  |
| `packages/web/src/content/docs/de/mcp-servers.mdx` | ✅ | docs | 511 |  |
| `packages/web/src/content/docs/de/models.mdx` | ✅ | docs | 223 |  |
| `packages/web/src/content/docs/de/network.mdx` | ✅ | docs | 57 |  |
| `packages/web/src/content/docs/de/permissions.mdx` | ✅ | docs | 235 |  |
| `packages/web/src/content/docs/de/plugins.mdx` | ✅ | docs | 384 |  |
| `packages/web/src/content/docs/de/providers.mdx` | ✅ | docs | 1987 |  |
| `packages/web/src/content/docs/de/rules.mdx` | ✅ | docs | 190 |  |
| `packages/web/src/content/docs/de/sdk.mdx` | ✅ | docs | 465 |  |
| `packages/web/src/content/docs/de/server.mdx` | ✅ | docs | 291 |  |
| `packages/web/src/content/docs/de/share.mdx` | ✅ | docs | 130 |  |
| `packages/web/src/content/docs/de/skills.mdx` | ✅ | docs | 222 |  |
| `packages/web/src/content/docs/de/themes.mdx` | ✅ | docs | 372 |  |
| `packages/web/src/content/docs/de/tools.mdx` | ✅ | docs | 352 |  |
| `packages/web/src/content/docs/de/troubleshooting.mdx` | ✅ | docs | 300 |  |
| `packages/web/src/content/docs/de/tui.mdx` | ✅ | docs | 400 |  |
| `packages/web/src/content/docs/de/web.mdx` | ✅ | docs | 142 |  |
| `packages/web/src/content/docs/de/windows-wsl.mdx` | ✅ | docs | 115 |  |
| `packages/web/src/content/docs/de/zen.mdx` | ✅ | docs | 284 |  |
| `packages/web/src/content/docs/ecosystem.mdx` | ✅ | docs | 81 |  |
| `packages/web/src/content/docs/enterprise.mdx` | ✅ | docs | 170 |  |
| `packages/web/src/content/docs/es/acp.mdx` | ✅ | docs | 156 |  |
| `packages/web/src/content/docs/es/agents.mdx` | ✅ | docs | 747 |  |
| `packages/web/src/content/docs/es/cli.mdx` | ✅ | docs | 602 |  |
| `packages/web/src/content/docs/es/commands.mdx` | ✅ | docs | 323 |  |
| `packages/web/src/content/docs/es/config.mdx` | ✅ | config | 685 |  |
| `packages/web/src/content/docs/es/custom-tools.mdx` | ✅ | docs | 196 |  |
| `packages/web/src/content/docs/es/ecosystem.mdx` | ✅ | docs | 78 |  |
| `packages/web/src/content/docs/es/enterprise.mdx` | ✅ | docs | 170 |  |
| `packages/web/src/content/docs/es/formatters.mdx` | ✅ | docs | 131 |  |
| `packages/web/src/content/docs/es/github.mdx` | ✅ | docs | 321 |  |
| `packages/web/src/content/docs/es/gitlab.mdx` | ✅ | docs | 195 |  |
| `packages/web/src/content/docs/es/go.mdx` | ✅ | docs | 196 |  |
| `packages/web/src/content/docs/es/ide.mdx` | ✅ | docs | 48 |  |
| `packages/web/src/content/docs/es/index.mdx` | ✅ | docs | 345 |  |
| `packages/web/src/content/docs/es/keybinds.mdx` | ✅ | docs | 194 |  |
| `packages/web/src/content/docs/es/lsp.mdx` | ✅ | docs | 189 |  |
| `packages/web/src/content/docs/es/mcp-servers.mdx` | ✅ | docs | 511 |  |
| `packages/web/src/content/docs/es/models.mdx` | ✅ | docs | 223 |  |
| `packages/web/src/content/docs/es/network.mdx` | ✅ | docs | 57 |  |
| `packages/web/src/content/docs/es/permissions.mdx` | ✅ | docs | 235 |  |
| `packages/web/src/content/docs/es/plugins.mdx` | ✅ | docs | 389 |  |
| `packages/web/src/content/docs/es/providers.mdx` | ✅ | docs | 1989 |  |
| `packages/web/src/content/docs/es/rules.mdx` | ✅ | docs | 180 |  |
| `packages/web/src/content/docs/es/sdk.mdx` | ✅ | docs | 463 |  |
| `packages/web/src/content/docs/es/server.mdx` | ✅ | docs | 287 |  |
| `packages/web/src/content/docs/es/share.mdx` | ✅ | docs | 128 |  |
| `packages/web/src/content/docs/es/skills.mdx` | ✅ | docs | 222 |  |
| `packages/web/src/content/docs/es/themes.mdx` | ✅ | docs | 369 |  |
| `packages/web/src/content/docs/es/tools.mdx` | ✅ | docs | 341 |  |
| `packages/web/src/content/docs/es/troubleshooting.mdx` | ✅ | docs | 300 |  |
| `packages/web/src/content/docs/es/tui.mdx` | ✅ | docs | 400 |  |
| `packages/web/src/content/docs/es/web.mdx` | ✅ | docs | 142 |  |
| `packages/web/src/content/docs/es/windows-wsl.mdx` | ✅ | docs | 113 |  |
| `packages/web/src/content/docs/es/zen.mdx` | ✅ | docs | 302 |  |
| `packages/web/src/content/docs/formatters.mdx` | ✅ | docs | 132 |  |
| `packages/web/src/content/docs/fr/acp.mdx` | ✅ | docs | 156 |  |
| `packages/web/src/content/docs/fr/agents.mdx` | ✅ | docs | 747 |  |
| `packages/web/src/content/docs/fr/cli.mdx` | ✅ | docs | 603 |  |
| `packages/web/src/content/docs/fr/commands.mdx` | ✅ | docs | 322 |  |
| `packages/web/src/content/docs/fr/config.mdx` | ✅ | config | 686 |  |
| `packages/web/src/content/docs/fr/custom-tools.mdx` | ✅ | docs | 170 |  |
| `packages/web/src/content/docs/fr/ecosystem.mdx` | ✅ | docs | 78 |  |
| `packages/web/src/content/docs/fr/enterprise.mdx` | ✅ | docs | 165 |  |
| `packages/web/src/content/docs/fr/formatters.mdx` | ✅ | docs | 131 |  |
| `packages/web/src/content/docs/fr/github.mdx` | ✅ | docs | 322 |  |
| `packages/web/src/content/docs/fr/gitlab.mdx` | ✅ | docs | 195 |  |
| `packages/web/src/content/docs/fr/go.mdx` | ✅ | docs | 182 |  |
| `packages/web/src/content/docs/fr/ide.mdx` | ✅ | docs | 48 |  |
| `packages/web/src/content/docs/fr/index.mdx` | ✅ | docs | 344 |  |
| `packages/web/src/content/docs/fr/keybinds.mdx` | ✅ | docs | 194 |  |
| `packages/web/src/content/docs/fr/lsp.mdx` | ✅ | docs | 189 |  |
| `packages/web/src/content/docs/fr/mcp-servers.mdx` | ✅ | docs | 511 |  |
| `packages/web/src/content/docs/fr/models.mdx` | ✅ | docs | 222 |  |
| `packages/web/src/content/docs/fr/network.mdx` | ✅ | docs | 57 |  |
| `packages/web/src/content/docs/fr/permissions.mdx` | ✅ | docs | 235 |  |
| `packages/web/src/content/docs/fr/plugins.mdx` | ✅ | docs | 384 |  |
| `packages/web/src/content/docs/fr/providers.mdx` | ✅ | docs | 1996 |  |
| `packages/web/src/content/docs/fr/rules.mdx` | ✅ | docs | 180 |  |
| `packages/web/src/content/docs/fr/sdk.mdx` | ✅ | docs | 463 |  |
| `packages/web/src/content/docs/fr/server.mdx` | ✅ | docs | 287 |  |
| `packages/web/src/content/docs/fr/share.mdx` | ✅ | docs | 128 |  |
| `packages/web/src/content/docs/fr/skills.mdx` | ✅ | docs | 222 |  |
| `packages/web/src/content/docs/fr/themes.mdx` | ✅ | docs | 369 |  |
| `packages/web/src/content/docs/fr/tools.mdx` | ✅ | docs | 341 |  |
| `packages/web/src/content/docs/fr/troubleshooting.mdx` | ✅ | docs | 300 |  |
| `packages/web/src/content/docs/fr/tui.mdx` | ✅ | docs | 400 |  |
| `packages/web/src/content/docs/fr/web.mdx` | ✅ | docs | 142 |  |
| `packages/web/src/content/docs/fr/windows-wsl.mdx` | ✅ | docs | 113 |  |
| `packages/web/src/content/docs/fr/zen.mdx` | ✅ | docs | 284 |  |
| `packages/web/src/content/docs/github.mdx` | ✅ | docs | 321 |  |
| `packages/web/src/content/docs/gitlab.mdx` | ✅ | docs | 195 |  |
| `packages/web/src/content/docs/go.mdx` | ✅ | docs | 196 |  |
| `packages/web/src/content/docs/ide.mdx` | ✅ | docs | 48 |  |
| `packages/web/src/content/docs/index.mdx` | ✅ | docs | 360 |  |
| `packages/web/src/content/docs/it/acp.mdx` | ✅ | docs | 155 |  |
| `packages/web/src/content/docs/it/agents.mdx` | ✅ | docs | 745 |  |
| `packages/web/src/content/docs/it/cli.mdx` | ✅ | docs | 603 |  |
| `packages/web/src/content/docs/it/commands.mdx` | ✅ | docs | 322 |  |
| `packages/web/src/content/docs/it/config.mdx` | ✅ | config | 685 |  |
| `packages/web/src/content/docs/it/custom-tools.mdx` | ✅ | docs | 196 |  |
| `packages/web/src/content/docs/it/ecosystem.mdx` | ✅ | docs | 78 |  |
| `packages/web/src/content/docs/it/enterprise.mdx` | ✅ | docs | 165 |  |
| `packages/web/src/content/docs/it/formatters.mdx` | ✅ | docs | 132 |  |
| `packages/web/src/content/docs/it/github.mdx` | ✅ | docs | 321 |  |
| `packages/web/src/content/docs/it/gitlab.mdx` | ✅ | docs | 195 |  |
| `packages/web/src/content/docs/it/go.mdx` | ✅ | docs | 194 |  |
| `packages/web/src/content/docs/it/ide.mdx` | ✅ | docs | 48 |  |
| `packages/web/src/content/docs/it/index.mdx` | ✅ | docs | 344 |  |
| `packages/web/src/content/docs/it/keybinds.mdx` | ✅ | docs | 194 |  |
| `packages/web/src/content/docs/it/lsp.mdx` | ✅ | docs | 189 |  |
| `packages/web/src/content/docs/it/mcp-servers.mdx` | ✅ | docs | 511 |  |
| `packages/web/src/content/docs/it/models.mdx` | ✅ | docs | 222 |  |
| `packages/web/src/content/docs/it/network.mdx` | ✅ | docs | 57 |  |
| `packages/web/src/content/docs/it/permissions.mdx` | ✅ | docs | 235 |  |
| `packages/web/src/content/docs/it/plugins.mdx` | ✅ | docs | 388 |  |
| `packages/web/src/content/docs/it/providers.mdx` | ✅ | docs | 1964 |  |
| `packages/web/src/content/docs/it/rules.mdx` | ✅ | docs | 180 |  |
| `packages/web/src/content/docs/it/sdk.mdx` | ✅ | docs | 463 |  |
| `packages/web/src/content/docs/it/server.mdx` | ✅ | docs | 284 |  |
| `packages/web/src/content/docs/it/share.mdx` | ✅ | docs | 127 |  |
| `packages/web/src/content/docs/it/skills.mdx` | ✅ | docs | 222 |  |
| `packages/web/src/content/docs/it/themes.mdx` | ✅ | docs | 369 |  |
| `packages/web/src/content/docs/it/tools.mdx` | ✅ | docs | 341 |  |
| `packages/web/src/content/docs/it/troubleshooting.mdx` | ✅ | docs | 299 |  |
| `packages/web/src/content/docs/it/tui.mdx` | ✅ | docs | 397 |  |
| `packages/web/src/content/docs/it/web.mdx` | ✅ | docs | 142 |  |
| `packages/web/src/content/docs/it/windows-wsl.mdx` | ✅ | docs | 113 |  |
| `packages/web/src/content/docs/it/zen.mdx` | ✅ | docs | 302 |  |
| `packages/web/src/content/docs/ja/acp.mdx` | ✅ | docs | 155 |  |
| `packages/web/src/content/docs/ja/agents.mdx` | ✅ | docs | 743 |  |
| `packages/web/src/content/docs/ja/cli.mdx` | ✅ | docs | 602 |  |
| `packages/web/src/content/docs/ja/commands.mdx` | ✅ | docs | 322 |  |
| `packages/web/src/content/docs/ja/config.mdx` | ✅ | config | 684 |  |
| `packages/web/src/content/docs/ja/custom-tools.mdx` | ✅ | docs | 196 |  |
| `packages/web/src/content/docs/ja/ecosystem.mdx` | ✅ | docs | 78 |  |
| `packages/web/src/content/docs/ja/enterprise.mdx` | ✅ | docs | 166 |  |
| `packages/web/src/content/docs/ja/formatters.mdx` | ✅ | docs | 132 |  |
| `packages/web/src/content/docs/ja/github.mdx` | ✅ | docs | 322 |  |
| `packages/web/src/content/docs/ja/gitlab.mdx` | ✅ | docs | 195 |  |
| `packages/web/src/content/docs/ja/go.mdx` | ✅ | docs | 182 |  |
| `packages/web/src/content/docs/ja/ide.mdx` | ✅ | docs | 48 |  |
| `packages/web/src/content/docs/ja/index.mdx` | ✅ | docs | 350 |  |
| `packages/web/src/content/docs/ja/keybinds.mdx` | ✅ | docs | 194 |  |
| `packages/web/src/content/docs/ja/lsp.mdx` | ✅ | docs | 189 |  |
| `packages/web/src/content/docs/ja/mcp-servers.mdx` | ✅ | docs | 511 |  |
| `packages/web/src/content/docs/ja/models.mdx` | ✅ | docs | 221 |  |
| `packages/web/src/content/docs/ja/network.mdx` | ✅ | docs | 55 |  |
| `packages/web/src/content/docs/ja/permissions.mdx` | ✅ | docs | 282 |  |
| `packages/web/src/content/docs/ja/plugins.mdx` | ✅ | docs | 461 |  |
| `packages/web/src/content/docs/ja/providers.mdx` | ✅ | docs | 1998 |  |
| `packages/web/src/content/docs/ja/rules.mdx` | ✅ | docs | 179 |  |
| `packages/web/src/content/docs/ja/sdk.mdx` | ✅ | docs | 463 |  |
| `packages/web/src/content/docs/ja/server.mdx` | ✅ | docs | 282 |  |
| `packages/web/src/content/docs/ja/share.mdx` | ✅ | docs | 128 |  |
| `packages/web/src/content/docs/ja/skills.mdx` | ✅ | docs | 222 |  |
| `packages/web/src/content/docs/ja/themes.mdx` | ✅ | docs | 667 |  |
| `packages/web/src/content/docs/ja/tools.mdx` | ✅ | docs | 341 |  |
| `packages/web/src/content/docs/ja/troubleshooting.mdx` | ✅ | docs | 300 |  |
| `packages/web/src/content/docs/ja/tui.mdx` | ✅ | docs | 394 |  |
| `packages/web/src/content/docs/ja/web.mdx` | ✅ | docs | 143 |  |
| `packages/web/src/content/docs/ja/windows-wsl.mdx` | ✅ | docs | 116 |  |
| `packages/web/src/content/docs/ja/zen.mdx` | ✅ | docs | 284 |  |
| `packages/web/src/content/docs/keybinds.mdx` | ✅ | docs | 203 |  |
| `packages/web/src/content/docs/ko/acp.mdx` | ✅ | docs | 156 |  |
| `packages/web/src/content/docs/ko/agents.mdx` | ✅ | docs | 746 |  |
| `packages/web/src/content/docs/ko/cli.mdx` | ✅ | docs | 602 |  |
| `packages/web/src/content/docs/ko/commands.mdx` | ✅ | docs | 323 |  |
| `packages/web/src/content/docs/ko/config.mdx` | ✅ | config | 685 |  |
| `packages/web/src/content/docs/ko/custom-tools.mdx` | ✅ | docs | 196 |  |
| `packages/web/src/content/docs/ko/ecosystem.mdx` | ✅ | docs | 78 |  |
| `packages/web/src/content/docs/ko/enterprise.mdx` | ✅ | docs | 165 |  |
| `packages/web/src/content/docs/ko/formatters.mdx` | ✅ | docs | 132 |  |
| `packages/web/src/content/docs/ko/github.mdx` | ✅ | docs | 321 |  |
| `packages/web/src/content/docs/ko/gitlab.mdx` | ✅ | docs | 195 |  |
| `packages/web/src/content/docs/ko/go.mdx` | ✅ | docs | 182 |  |
| `packages/web/src/content/docs/ko/ide.mdx` | ✅ | docs | 48 |  |
| `packages/web/src/content/docs/ko/index.mdx` | ✅ | docs | 344 |  |
| `packages/web/src/content/docs/ko/keybinds.mdx` | ✅ | docs | 194 |  |
| `packages/web/src/content/docs/ko/lsp.mdx` | ✅ | docs | 189 |  |
| `packages/web/src/content/docs/ko/mcp-servers.mdx` | ✅ | docs | 511 |  |
| `packages/web/src/content/docs/ko/models.mdx` | ✅ | docs | 223 |  |
| `packages/web/src/content/docs/ko/network.mdx` | ✅ | docs | 57 |  |
| `packages/web/src/content/docs/ko/permissions.mdx` | ✅ | docs | 235 |  |
| `packages/web/src/content/docs/ko/plugins.mdx` | ✅ | docs | 388 |  |
| `packages/web/src/content/docs/ko/providers.mdx` | ✅ | docs | 1984 |  |
| `packages/web/src/content/docs/ko/rules.mdx` | ✅ | docs | 179 |  |
| `packages/web/src/content/docs/ko/sdk.mdx` | ✅ | docs | 463 |  |
| `packages/web/src/content/docs/ko/server.mdx` | ✅ | docs | 287 |  |
| `packages/web/src/content/docs/ko/share.mdx` | ✅ | docs | 128 |  |
| `packages/web/src/content/docs/ko/skills.mdx` | ✅ | docs | 222 |  |
| `packages/web/src/content/docs/ko/themes.mdx` | ✅ | docs | 369 |  |
| `packages/web/src/content/docs/ko/tools.mdx` | ✅ | docs | 341 |  |
| `packages/web/src/content/docs/ko/troubleshooting.mdx` | ✅ | docs | 303 |  |
| `packages/web/src/content/docs/ko/tui.mdx` | ✅ | docs | 396 |  |
| `packages/web/src/content/docs/ko/web.mdx` | ✅ | docs | 142 |  |
| `packages/web/src/content/docs/ko/windows-wsl.mdx` | ✅ | docs | 119 |  |
| `packages/web/src/content/docs/ko/zen.mdx` | ✅ | docs | 284 |  |
| `packages/web/src/content/docs/lsp.mdx` | ✅ | docs | 190 |  |
| `packages/web/src/content/docs/mcp-servers.mdx` | ✅ | docs | 511 |  |
| `packages/web/src/content/docs/models.mdx` | ✅ | docs | 223 |  |
| `packages/web/src/content/docs/nb/acp.mdx` | ✅ | docs | 156 |  |
| `packages/web/src/content/docs/nb/agents.mdx` | ✅ | docs | 746 |  |
| `packages/web/src/content/docs/nb/cli.mdx` | ✅ | docs | 603 |  |
| `packages/web/src/content/docs/nb/commands.mdx` | ✅ | docs | 323 |  |
| `packages/web/src/content/docs/nb/config.mdx` | ✅ | config | 688 |  |
| `packages/web/src/content/docs/nb/custom-tools.mdx` | ✅ | docs | 196 |  |
| `packages/web/src/content/docs/nb/ecosystem.mdx` | ✅ | docs | 78 |  |
| `packages/web/src/content/docs/nb/enterprise.mdx` | ✅ | docs | 170 |  |
| `packages/web/src/content/docs/nb/formatters.mdx` | ✅ | docs | 131 |  |
| `packages/web/src/content/docs/nb/github.mdx` | ✅ | docs | 325 |  |
| `packages/web/src/content/docs/nb/gitlab.mdx` | ✅ | docs | 195 |  |
| `packages/web/src/content/docs/nb/go.mdx` | ✅ | docs | 196 |  |
| `packages/web/src/content/docs/nb/ide.mdx` | ✅ | docs | 48 |  |
| `packages/web/src/content/docs/nb/index.mdx` | ✅ | docs | 359 |  |
| `packages/web/src/content/docs/nb/keybinds.mdx` | ✅ | docs | 194 |  |
| `packages/web/src/content/docs/nb/lsp.mdx` | ✅ | docs | 189 |  |
| `packages/web/src/content/docs/nb/mcp-servers.mdx` | ✅ | docs | 624 |  |
| `packages/web/src/content/docs/nb/models.mdx` | ✅ | docs | 223 |  |
| `packages/web/src/content/docs/nb/network.mdx` | ✅ | docs | 57 |  |
| `packages/web/src/content/docs/nb/permissions.mdx` | ✅ | docs | 235 |  |
| `packages/web/src/content/docs/nb/plugins.mdx` | ✅ | docs | 389 |  |
| `packages/web/src/content/docs/nb/providers.mdx` | ✅ | docs | 1956 |  |
| `packages/web/src/content/docs/nb/rules.mdx` | ✅ | docs | 180 |  |
| `packages/web/src/content/docs/nb/sdk.mdx` | ✅ | docs | 463 |  |
| `packages/web/src/content/docs/nb/server.mdx` | ✅ | docs | 287 |  |
| `packages/web/src/content/docs/nb/share.mdx` | ✅ | docs | 128 |  |
| `packages/web/src/content/docs/nb/skills.mdx` | ✅ | docs | 222 |  |
| `packages/web/src/content/docs/nb/themes.mdx` | ✅ | docs | 369 |  |
| `packages/web/src/content/docs/nb/tools.mdx` | ✅ | docs | 341 |  |
| `packages/web/src/content/docs/nb/troubleshooting.mdx` | ✅ | docs | 225 |  |
| `packages/web/src/content/docs/nb/tui.mdx` | ✅ | docs | 400 |  |
| `packages/web/src/content/docs/nb/web.mdx` | ✅ | docs | 105 |  |
| `packages/web/src/content/docs/nb/windows-wsl.mdx` | ✅ | docs | 113 |  |
| `packages/web/src/content/docs/nb/zen.mdx` | ✅ | docs | 302 |  |
| `packages/web/src/content/docs/network.mdx` | ✅ | docs | 57 |  |
| `packages/web/src/content/docs/permissions.mdx` | ✅ | docs | 236 |  |
| `packages/web/src/content/docs/pl/acp.mdx` | ✅ | docs | 158 |  |
| `packages/web/src/content/docs/pl/agents.mdx` | ✅ | docs | 746 |  |
| `packages/web/src/content/docs/pl/cli.mdx` | ✅ | docs | 603 |  |
| `packages/web/src/content/docs/pl/commands.mdx` | ✅ | docs | 323 |  |
| `packages/web/src/content/docs/pl/config.mdx` | ✅ | config | 680 |  |
| `packages/web/src/content/docs/pl/custom-tools.mdx` | ✅ | docs | 196 |  |
| `packages/web/src/content/docs/pl/ecosystem.mdx` | ✅ | docs | 78 |  |
| `packages/web/src/content/docs/pl/enterprise.mdx` | ✅ | docs | 170 |  |
| `packages/web/src/content/docs/pl/formatters.mdx` | ✅ | docs | 131 |  |
| `packages/web/src/content/docs/pl/github.mdx` | ✅ | docs | 321 |  |
| `packages/web/src/content/docs/pl/gitlab.mdx` | ✅ | docs | 195 |  |
| `packages/web/src/content/docs/pl/go.mdx` | ✅ | docs | 188 |  |
| `packages/web/src/content/docs/pl/ide.mdx` | ✅ | docs | 48 |  |
| `packages/web/src/content/docs/pl/index.mdx` | ✅ | docs | 347 |  |
| `packages/web/src/content/docs/pl/keybinds.mdx` | ✅ | docs | 194 |  |
| `packages/web/src/content/docs/pl/lsp.mdx` | ✅ | docs | 189 |  |
| `packages/web/src/content/docs/pl/mcp-servers.mdx` | ✅ | docs | 511 |  |
| `packages/web/src/content/docs/pl/models.mdx` | ✅ | docs | 223 |  |
| `packages/web/src/content/docs/pl/network.mdx` | ✅ | docs | 57 |  |
| `packages/web/src/content/docs/pl/permissions.mdx` | ✅ | docs | 235 |  |
| `packages/web/src/content/docs/pl/plugins.mdx` | ✅ | docs | 385 |  |
| `packages/web/src/content/docs/pl/providers.mdx` | ✅ | docs | 1986 |  |
| `packages/web/src/content/docs/pl/rules.mdx` | ✅ | docs | 180 |  |
| `packages/web/src/content/docs/pl/sdk.mdx` | ✅ | docs | 463 |  |
| `packages/web/src/content/docs/pl/server.mdx` | ✅ | docs | 287 |  |
| `packages/web/src/content/docs/pl/share.mdx` | ✅ | docs | 128 |  |
| `packages/web/src/content/docs/pl/skills.mdx` | ✅ | docs | 222 |  |
| `packages/web/src/content/docs/pl/themes.mdx` | ✅ | docs | 369 |  |
| `packages/web/src/content/docs/pl/tools.mdx` | ✅ | docs | 341 |  |
| `packages/web/src/content/docs/pl/troubleshooting.mdx` | ✅ | docs | 300 |  |
| `packages/web/src/content/docs/pl/tui.mdx` | ✅ | docs | 400 |  |
| `packages/web/src/content/docs/pl/web.mdx` | ✅ | docs | 142 |  |
| `packages/web/src/content/docs/pl/windows-wsl.mdx` | ✅ | docs | 113 |  |
| `packages/web/src/content/docs/pl/zen.mdx` | ✅ | docs | 302 |  |
| `packages/web/src/content/docs/plugins.mdx` | ✅ | docs | 389 |  |
| `packages/web/src/content/docs/providers.mdx` | ✅ | docs | 2207 |  |
| `packages/web/src/content/docs/pt-br/acp.mdx` | ✅ | docs | 156 |  |
| `packages/web/src/content/docs/pt-br/agents.mdx` | ✅ | docs | 747 |  |
| `packages/web/src/content/docs/pt-br/cli.mdx` | ✅ | docs | 602 |  |
| `packages/web/src/content/docs/pt-br/commands.mdx` | ✅ | docs | 322 |  |
| `packages/web/src/content/docs/pt-br/config.mdx` | ✅ | config | 687 |  |
| `packages/web/src/content/docs/pt-br/custom-tools.mdx` | ✅ | docs | 196 |  |
| `packages/web/src/content/docs/pt-br/ecosystem.mdx` | ✅ | docs | 78 |  |
| `packages/web/src/content/docs/pt-br/enterprise.mdx` | ✅ | docs | 166 |  |
| `packages/web/src/content/docs/pt-br/formatters.mdx` | ✅ | docs | 131 |  |
| `packages/web/src/content/docs/pt-br/github.mdx` | ✅ | docs | 321 |  |
| `packages/web/src/content/docs/pt-br/gitlab.mdx` | ✅ | docs | 195 |  |
| `packages/web/src/content/docs/pt-br/go.mdx` | ✅ | docs | 196 |  |
| `packages/web/src/content/docs/pt-br/ide.mdx` | ✅ | docs | 48 |  |
| `packages/web/src/content/docs/pt-br/index.mdx` | ✅ | docs | 344 |  |
| `packages/web/src/content/docs/pt-br/keybinds.mdx` | ✅ | docs | 194 |  |
| `packages/web/src/content/docs/pt-br/lsp.mdx` | ✅ | docs | 189 |  |
| `packages/web/src/content/docs/pt-br/mcp-servers.mdx` | ✅ | docs | 511 |  |
| `packages/web/src/content/docs/pt-br/models.mdx` | ✅ | docs | 222 |  |
| `packages/web/src/content/docs/pt-br/network.mdx` | ✅ | docs | 57 |  |
| `packages/web/src/content/docs/pt-br/permissions.mdx` | ✅ | docs | 235 |  |
| `packages/web/src/content/docs/pt-br/plugins.mdx` | ✅ | docs | 388 |  |
| `packages/web/src/content/docs/pt-br/providers.mdx` | ✅ | docs | 1989 |  |
| `packages/web/src/content/docs/pt-br/rules.mdx` | ✅ | docs | 180 |  |
| `packages/web/src/content/docs/pt-br/sdk.mdx` | ✅ | docs | 463 |  |
| `packages/web/src/content/docs/pt-br/server.mdx` | ✅ | docs | 284 |  |
| `packages/web/src/content/docs/pt-br/share.mdx` | ✅ | docs | 127 |  |
| `packages/web/src/content/docs/pt-br/skills.mdx` | ✅ | docs | 222 |  |
| `packages/web/src/content/docs/pt-br/themes.mdx` | ✅ | docs | 369 |  |
| `packages/web/src/content/docs/pt-br/tools.mdx` | ✅ | docs | 341 |  |
| `packages/web/src/content/docs/pt-br/troubleshooting.mdx` | ✅ | docs | 299 |  |
| `packages/web/src/content/docs/pt-br/tui.mdx` | ✅ | docs | 397 |  |
| `packages/web/src/content/docs/pt-br/web.mdx` | ✅ | docs | 142 |  |
| `packages/web/src/content/docs/pt-br/windows-wsl.mdx` | ✅ | docs | 113 |  |
| `packages/web/src/content/docs/pt-br/zen.mdx` | ✅ | docs | 284 |  |
| `packages/web/src/content/docs/ru/acp.mdx` | ✅ | docs | 156 |  |
| `packages/web/src/content/docs/ru/agents.mdx` | ✅ | docs | 746 |  |
| `packages/web/src/content/docs/ru/cli.mdx` | ✅ | docs | 603 |  |
| `packages/web/src/content/docs/ru/commands.mdx` | ✅ | docs | 323 |  |
| `packages/web/src/content/docs/ru/config.mdx` | ✅ | config | 685 |  |
| `packages/web/src/content/docs/ru/custom-tools.mdx` | ✅ | docs | 170 |  |
| `packages/web/src/content/docs/ru/ecosystem.mdx` | ✅ | docs | 78 |  |
| `packages/web/src/content/docs/ru/enterprise.mdx` | ✅ | docs | 168 |  |
| `packages/web/src/content/docs/ru/formatters.mdx` | ✅ | docs | 119 |  |
| `packages/web/src/content/docs/ru/github.mdx` | ✅ | docs | 321 |  |
| `packages/web/src/content/docs/ru/gitlab.mdx` | ✅ | docs | 195 |  |
| `packages/web/src/content/docs/ru/go.mdx` | ✅ | docs | 196 |  |
| `packages/web/src/content/docs/ru/ide.mdx` | ✅ | docs | 48 |  |
| `packages/web/src/content/docs/ru/index.mdx` | ✅ | docs | 359 |  |
| `packages/web/src/content/docs/ru/keybinds.mdx` | ✅ | docs | 194 |  |
| `packages/web/src/content/docs/ru/lsp.mdx` | ✅ | docs | 188 |  |
| `packages/web/src/content/docs/ru/mcp-servers.mdx` | ✅ | docs | 511 |  |
| `packages/web/src/content/docs/ru/models.mdx` | ✅ | docs | 223 |  |
| `packages/web/src/content/docs/ru/network.mdx` | ✅ | docs | 57 |  |
| `packages/web/src/content/docs/ru/permissions.mdx` | ✅ | docs | 235 |  |
| `packages/web/src/content/docs/ru/plugins.mdx` | ✅ | docs | 385 |  |
| `packages/web/src/content/docs/ru/providers.mdx` | ✅ | docs | 1987 |  |
| `packages/web/src/content/docs/ru/rules.mdx` | ✅ | docs | 180 |  |
| `packages/web/src/content/docs/ru/sdk.mdx` | ✅ | docs | 463 |  |
| `packages/web/src/content/docs/ru/server.mdx` | ✅ | docs | 287 |  |
| `packages/web/src/content/docs/ru/share.mdx` | ✅ | docs | 128 |  |
| `packages/web/src/content/docs/ru/skills.mdx` | ✅ | docs | 222 |  |
| `packages/web/src/content/docs/ru/themes.mdx` | ✅ | docs | 369 |  |
| `packages/web/src/content/docs/ru/tools.mdx` | ✅ | docs | 341 |  |
| `packages/web/src/content/docs/ru/troubleshooting.mdx` | ✅ | docs | 300 |  |
| `packages/web/src/content/docs/ru/tui.mdx` | ✅ | docs | 400 |  |
| `packages/web/src/content/docs/ru/web.mdx` | ✅ | docs | 142 |  |
| `packages/web/src/content/docs/ru/windows-wsl.mdx` | ✅ | docs | 113 |  |
| `packages/web/src/content/docs/ru/zen.mdx` | ✅ | docs | 302 |  |
| `packages/web/src/content/docs/rules.mdx` | ✅ | docs | 188 |  |
| `packages/web/src/content/docs/sdk.mdx` | ✅ | docs | 463 |  |
| `packages/web/src/content/docs/server.mdx` | ✅ | docs | 287 |  |
| `packages/web/src/content/docs/share.mdx` | ✅ | docs | 128 |  |
| `packages/web/src/content/docs/skills.mdx` | ✅ | docs | 222 |  |
| `packages/web/src/content/docs/th/acp.mdx` | ✅ | docs | 156 |  |
| `packages/web/src/content/docs/th/agents.mdx` | ✅ | docs | 736 |  |
| `packages/web/src/content/docs/th/cli.mdx` | ✅ | docs | 604 |  |
| `packages/web/src/content/docs/th/commands.mdx` | ✅ | docs | 320 |  |
| `packages/web/src/content/docs/th/config.mdx` | ✅ | config | 690 |  |
| `packages/web/src/content/docs/th/custom-tools.mdx` | ✅ | docs | 196 |  |
| `packages/web/src/content/docs/th/ecosystem.mdx` | ✅ | docs | 78 |  |
| `packages/web/src/content/docs/th/enterprise.mdx` | ✅ | docs | 170 |  |
| `packages/web/src/content/docs/th/formatters.mdx` | ✅ | docs | 131 |  |
| `packages/web/src/content/docs/th/github.mdx` | ✅ | docs | 321 |  |
| `packages/web/src/content/docs/th/gitlab.mdx` | ✅ | docs | 195 |  |
| `packages/web/src/content/docs/th/go.mdx` | ✅ | docs | 182 |  |
| `packages/web/src/content/docs/th/ide.mdx` | ✅ | docs | 48 |  |
| `packages/web/src/content/docs/th/index.mdx` | ✅ | docs | 360 |  |
| `packages/web/src/content/docs/th/keybinds.mdx` | ✅ | docs | 194 |  |
| `packages/web/src/content/docs/th/lsp.mdx` | ✅ | docs | 189 |  |
| `packages/web/src/content/docs/th/mcp-servers.mdx` | ✅ | docs | 511 |  |
| `packages/web/src/content/docs/th/models.mdx` | ✅ | docs | 223 |  |
| `packages/web/src/content/docs/th/network.mdx` | ✅ | docs | 57 |  |
| `packages/web/src/content/docs/th/permissions.mdx` | ✅ | docs | 235 |  |
| `packages/web/src/content/docs/th/plugins.mdx` | ✅ | docs | 389 |  |
| `packages/web/src/content/docs/th/providers.mdx` | ✅ | docs | 2532 |  |
| `packages/web/src/content/docs/th/rules.mdx` | ✅ | docs | 180 |  |
| `packages/web/src/content/docs/th/sdk.mdx` | ✅ | docs | 463 |  |
| `packages/web/src/content/docs/th/server.mdx` | ✅ | docs | 287 |  |
| `packages/web/src/content/docs/th/share.mdx` | ✅ | docs | 128 |  |
| `packages/web/src/content/docs/th/skills.mdx` | ✅ | docs | 222 |  |
| `packages/web/src/content/docs/th/themes.mdx` | ✅ | docs | 369 |  |
| `packages/web/src/content/docs/th/tools.mdx` | ✅ | docs | 341 |  |
| `packages/web/src/content/docs/th/troubleshooting.mdx` | ✅ | docs | 300 |  |
| `packages/web/src/content/docs/th/tui.mdx` | ✅ | docs | 400 |  |
| `packages/web/src/content/docs/th/web.mdx` | ✅ | docs | 142 |  |
| `packages/web/src/content/docs/th/windows-wsl.mdx` | ✅ | docs | 113 |  |
| `packages/web/src/content/docs/th/zen.mdx` | ✅ | docs | 286 |  |
| `packages/web/src/content/docs/themes.mdx` | ✅ | docs | 369 |  |
| `packages/web/src/content/docs/tools.mdx` | ✅ | docs | 345 |  |
| `packages/web/src/content/docs/tr/acp.mdx` | ✅ | docs | 156 |  |
| `packages/web/src/content/docs/tr/agents.mdx` | ✅ | docs | 746 |  |
| `packages/web/src/content/docs/tr/cli.mdx` | ✅ | docs | 603 |  |
| `packages/web/src/content/docs/tr/commands.mdx` | ✅ | docs | 323 |  |
| `packages/web/src/content/docs/tr/config.mdx` | ✅ | config | 687 |  |
| `packages/web/src/content/docs/tr/custom-tools.mdx` | ✅ | docs | 196 |  |
| `packages/web/src/content/docs/tr/ecosystem.mdx` | ✅ | docs | 78 |  |
| `packages/web/src/content/docs/tr/enterprise.mdx` | ✅ | docs | 170 |  |
| `packages/web/src/content/docs/tr/formatters.mdx` | ✅ | docs | 131 |  |
| `packages/web/src/content/docs/tr/github.mdx` | ✅ | docs | 321 |  |
| `packages/web/src/content/docs/tr/gitlab.mdx` | ✅ | docs | 195 |  |
| `packages/web/src/content/docs/tr/go.mdx` | ✅ | docs | 182 |  |
| `packages/web/src/content/docs/tr/ide.mdx` | ✅ | docs | 48 |  |
| `packages/web/src/content/docs/tr/index.mdx` | ✅ | docs | 347 |  |
| `packages/web/src/content/docs/tr/keybinds.mdx` | ✅ | docs | 194 |  |
| `packages/web/src/content/docs/tr/lsp.mdx` | ✅ | docs | 189 |  |
| `packages/web/src/content/docs/tr/mcp-servers.mdx` | ✅ | docs | 511 |  |
| `packages/web/src/content/docs/tr/models.mdx` | ✅ | docs | 223 |  |
| `packages/web/src/content/docs/tr/network.mdx` | ✅ | docs | 57 |  |
| `packages/web/src/content/docs/tr/permissions.mdx` | ✅ | docs | 235 |  |
| `packages/web/src/content/docs/tr/plugins.mdx` | ✅ | docs | 388 |  |
| `packages/web/src/content/docs/tr/providers.mdx` | ✅ | docs | 1988 |  |
| `packages/web/src/content/docs/tr/rules.mdx` | ✅ | docs | 180 |  |
| `packages/web/src/content/docs/tr/sdk.mdx` | ✅ | docs | 463 |  |
| `packages/web/src/content/docs/tr/server.mdx` | ✅ | docs | 285 |  |
| `packages/web/src/content/docs/tr/share.mdx` | ✅ | docs | 127 |  |
| `packages/web/src/content/docs/tr/skills.mdx` | ✅ | docs | 222 |  |
| `packages/web/src/content/docs/tr/themes.mdx` | ✅ | docs | 369 |  |
| `packages/web/src/content/docs/tr/tools.mdx` | ✅ | docs | 341 |  |
| `packages/web/src/content/docs/tr/troubleshooting.mdx` | ✅ | docs | 299 |  |
| `packages/web/src/content/docs/tr/tui.mdx` | ✅ | docs | 398 |  |
| `packages/web/src/content/docs/tr/web.mdx` | ✅ | docs | 142 |  |
| `packages/web/src/content/docs/tr/windows-wsl.mdx` | ✅ | docs | 113 |  |
| `packages/web/src/content/docs/tr/zen.mdx` | ✅ | docs | 284 |  |
| `packages/web/src/content/docs/troubleshooting.mdx` | ✅ | docs | 300 |  |
| `packages/web/src/content/docs/tui.mdx` | ✅ | docs | 394 |  |
| `packages/web/src/content/docs/web.mdx` | ✅ | docs | 142 |  |
| `packages/web/src/content/docs/windows-wsl.mdx` | ✅ | docs | 112 |  |
| `packages/web/src/content/docs/zen.mdx` | ✅ | docs | 302 |  |
| `packages/web/src/content/docs/zh-cn/acp.mdx` | ✅ | docs | 156 |  |
| `packages/web/src/content/docs/zh-cn/agents.mdx` | ✅ | docs | 746 |  |
| `packages/web/src/content/docs/zh-cn/cli.mdx` | ✅ | docs | 602 |  |
| `packages/web/src/content/docs/zh-cn/commands.mdx` | ✅ | docs | 322 |  |
| `packages/web/src/content/docs/zh-cn/config.mdx` | ✅ | config | 683 |  |
| `packages/web/src/content/docs/zh-cn/custom-tools.mdx` | ✅ | docs | 196 |  |
| `packages/web/src/content/docs/zh-cn/ecosystem.mdx` | ✅ | docs | 78 |  |
| `packages/web/src/content/docs/zh-cn/enterprise.mdx` | ✅ | docs | 165 |  |
| `packages/web/src/content/docs/zh-cn/formatters.mdx` | ✅ | docs | 132 |  |
| `packages/web/src/content/docs/zh-cn/github.mdx` | ✅ | docs | 321 |  |
| `packages/web/src/content/docs/zh-cn/gitlab.mdx` | ✅ | docs | 194 |  |
| `packages/web/src/content/docs/zh-cn/go.mdx` | ✅ | docs | 182 |  |
| `packages/web/src/content/docs/zh-cn/ide.mdx` | ✅ | docs | 48 |  |
| `packages/web/src/content/docs/zh-cn/index.mdx` | ✅ | docs | 343 |  |
| `packages/web/src/content/docs/zh-cn/keybinds.mdx` | ✅ | docs | 194 |  |
| `packages/web/src/content/docs/zh-cn/lsp.mdx` | ✅ | docs | 189 |  |
| `packages/web/src/content/docs/zh-cn/mcp-servers.mdx` | ✅ | docs | 511 |  |
| `packages/web/src/content/docs/zh-cn/models.mdx` | ✅ | docs | 222 |  |
| `packages/web/src/content/docs/zh-cn/network.mdx` | ✅ | docs | 57 |  |
| `packages/web/src/content/docs/zh-cn/permissions.mdx` | ✅ | docs | 235 |  |
| `packages/web/src/content/docs/zh-cn/plugins.mdx` | ✅ | docs | 388 |  |
| `packages/web/src/content/docs/zh-cn/providers.mdx` | ✅ | docs | 1949 |  |
| `packages/web/src/content/docs/zh-cn/rules.mdx` | ✅ | docs | 180 |  |
| `packages/web/src/content/docs/zh-cn/sdk.mdx` | ✅ | docs | 463 |  |
| `packages/web/src/content/docs/zh-cn/server.mdx` | ✅ | docs | 284 |  |
| `packages/web/src/content/docs/zh-cn/share.mdx` | ✅ | docs | 127 |  |
| `packages/web/src/content/docs/zh-cn/skills.mdx` | ✅ | docs | 222 |  |
| `packages/web/src/content/docs/zh-cn/themes.mdx` | ✅ | docs | 369 |  |
| `packages/web/src/content/docs/zh-cn/tools.mdx` | ✅ | docs | 341 |  |
| `packages/web/src/content/docs/zh-cn/troubleshooting.mdx` | ✅ | docs | 299 |  |
| `packages/web/src/content/docs/zh-cn/tui.mdx` | ✅ | docs | 387 |  |
| `packages/web/src/content/docs/zh-cn/web.mdx` | ✅ | docs | 142 |  |
| `packages/web/src/content/docs/zh-cn/windows-wsl.mdx` | ✅ | docs | 112 |  |
| `packages/web/src/content/docs/zh-cn/zen.mdx` | ✅ | docs | 284 |  |
| `packages/web/src/content/docs/zh-tw/acp.mdx` | ✅ | docs | 156 |  |
| `packages/web/src/content/docs/zh-tw/agents.mdx` | ✅ | docs | 746 |  |
| `packages/web/src/content/docs/zh-tw/cli.mdx` | ✅ | docs | 603 |  |
| `packages/web/src/content/docs/zh-tw/commands.mdx` | ✅ | docs | 322 |  |
| `packages/web/src/content/docs/zh-tw/config.mdx` | ✅ | config | 687 |  |
| `packages/web/src/content/docs/zh-tw/custom-tools.mdx` | ✅ | docs | 196 |  |
| `packages/web/src/content/docs/zh-tw/ecosystem.mdx` | ✅ | docs | 78 |  |
| `packages/web/src/content/docs/zh-tw/enterprise.mdx` | ✅ | docs | 165 |  |
| `packages/web/src/content/docs/zh-tw/formatters.mdx` | ✅ | docs | 132 |  |
| `packages/web/src/content/docs/zh-tw/github.mdx` | ✅ | docs | 321 |  |
| `packages/web/src/content/docs/zh-tw/gitlab.mdx` | ✅ | docs | 194 |  |
| `packages/web/src/content/docs/zh-tw/go.mdx` | ✅ | docs | 182 |  |
| `packages/web/src/content/docs/zh-tw/ide.mdx` | ✅ | docs | 48 |  |
| `packages/web/src/content/docs/zh-tw/index.mdx` | ✅ | docs | 343 |  |
| `packages/web/src/content/docs/zh-tw/keybinds.mdx` | ✅ | docs | 194 |  |
| `packages/web/src/content/docs/zh-tw/lsp.mdx` | ✅ | docs | 189 |  |
| `packages/web/src/content/docs/zh-tw/mcp-servers.mdx` | ✅ | docs | 511 |  |
| `packages/web/src/content/docs/zh-tw/models.mdx` | ✅ | docs | 222 |  |
| `packages/web/src/content/docs/zh-tw/network.mdx` | ✅ | docs | 57 |  |
| `packages/web/src/content/docs/zh-tw/permissions.mdx` | ✅ | docs | 235 |  |
| `packages/web/src/content/docs/zh-tw/plugins.mdx` | ✅ | docs | 388 |  |
| `packages/web/src/content/docs/zh-tw/providers.mdx` | ✅ | docs | 1970 |  |
| `packages/web/src/content/docs/zh-tw/rules.mdx` | ✅ | docs | 180 |  |
| `packages/web/src/content/docs/zh-tw/sdk.mdx` | ✅ | docs | 463 |  |
| `packages/web/src/content/docs/zh-tw/server.mdx` | ✅ | docs | 284 |  |
| `packages/web/src/content/docs/zh-tw/share.mdx` | ✅ | docs | 127 |  |
| `packages/web/src/content/docs/zh-tw/skills.mdx` | ✅ | docs | 222 |  |
| `packages/web/src/content/docs/zh-tw/themes.mdx` | ✅ | docs | 369 |  |
| `packages/web/src/content/docs/zh-tw/tools.mdx` | ✅ | docs | 341 |  |
| `packages/web/src/content/docs/zh-tw/troubleshooting.mdx` | ✅ | docs | 299 |  |
| `packages/web/src/content/docs/zh-tw/tui.mdx` | ✅ | docs | 397 |  |
| `packages/web/src/content/docs/zh-tw/web.mdx` | ✅ | docs | 142 |  |
| `packages/web/src/content/docs/zh-tw/windows-wsl.mdx` | ✅ | docs | 112 |  |
| `packages/web/src/content/docs/zh-tw/zen.mdx` | ✅ | docs | 291 |  |
| `packages/web/src/content/i18n/ar.json` | ✅ | source | 75 |  |
| `packages/web/src/content/i18n/bs.json` | ✅ | source | 75 |  |
| `packages/web/src/content/i18n/da.json` | ✅ | source | 75 |  |
| `packages/web/src/content/i18n/de.json` | ✅ | source | 75 |  |
| `packages/web/src/content/i18n/en.json` | ✅ | source | 75 |  |
| `packages/web/src/content/i18n/es.json` | ✅ | source | 75 |  |
| `packages/web/src/content/i18n/fr.json` | ✅ | source | 75 |  |
| `packages/web/src/content/i18n/it.json` | ✅ | source | 75 |  |
| `packages/web/src/content/i18n/ja.json` | ✅ | source | 75 |  |
| `packages/web/src/content/i18n/ko.json` | ✅ | source | 75 |  |
| `packages/web/src/content/i18n/nb.json` | ✅ | source | 75 |  |
| `packages/web/src/content/i18n/pl.json` | ✅ | source | 75 |  |
| `packages/web/src/content/i18n/pt-BR.json` | ✅ | source | 75 |  |
| `packages/web/src/content/i18n/ru.json` | ✅ | source | 75 |  |
| `packages/web/src/content/i18n/th.json` | ✅ | source | 75 |  |
| `packages/web/src/content/i18n/tr.json` | ✅ | source | 75 |  |
| `packages/web/src/content/i18n/zh-CN.json` | ✅ | source | 75 |  |
| `packages/web/src/content/i18n/zh-TW.json` | ✅ | source | 75 |  |
| `packages/web/src/i18n/locales.ts` | ✅ | source | 114 | exactLocale |
| `packages/web/src/middleware.ts` | ✅ | source | 94 | onRequest |
| `packages/web/src/pages/[...slug].md.ts` | ✅ | source | 34 | GET |
| `packages/web/src/styles/custom.css` | ✅ | style | 405 |  |
| `packages/web/src/types/lang-map.d.ts` | ✅ | source | 27 |  |
| `packages/web/src/types/starlight-virtual.d.ts` | ✅ | source | 14 |  |
| `packages/web/sst-env.d.ts` | ✅ | source | 10 |  |
| `packages/web/tsconfig.json` | ✅ | config | 9 |  |
| `patches/install-korean-ime-fix.sh` | ✅ | source | 120 |  |
| `script/beta.ts` | ✅ | source | 360 |  |
| `script/changelog.ts` | ✅ | source | 76 |  |
| `script/duplicate-pr.ts` | ✅ | source | 79 |  |
| `script/format.ts` | ✅ | source | 5 |  |
| `script/generate.ts` | ✅ | source | 9 |  |
| `script/github/close-issues.ts` | ✅ | source | 96 |  |
| `script/publish.ts` | ✅ | source | 74 |  |
| `script/raw-changelog.ts` | ✅ | source | 261 |  |
| `script/stats.ts` | ✅ | source | 225 |  |
| `script/sync-zed.ts` | ✅ | source | 130 |  |
| `script/version.ts` | ✅ | source | 36 |  |
| `sdks/vscode/.gitignore` | ✅ | source | 1 |  |
| `sdks/vscode/README.md` | ✅ | docs | 34 |  |
| `sdks/vscode/esbuild.js` | ✅ | source | 54 |  |
| `sdks/vscode/package.json` | ✅ | source | 108 |  |
| `sdks/vscode/src/extension.ts` | ✅ | source | 137 | deactivate |
| `sdks/vscode/sst-env.d.ts` | ✅ | source | 10 |  |
| `sdks/vscode/tsconfig.json` | ✅ | config | 16 |  |
| `specs/project.md` | ✅ | docs | 64 |  |
| `specs/v2/session.md` | ✅ | docs | 17 |  |
| `sst-env.d.ts` | ✅ | source | 319 |  |
| `sst.config.ts` | ✅ | config | 23 |  |
| `tsconfig.json` | ✅ | config | 5 |  |
| `turbo.json` | ✅ | source | 31 |  |

---
*Generated: 2026-05-04 02:45:04Z*
