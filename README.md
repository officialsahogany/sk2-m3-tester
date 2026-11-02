# Seven Kingdoms II: Titan Wars Mod v30

Seven Kingdoms II: Titan Wars Mod는 비공식 팬 모드이며 Enlight 공식판이 아닙니다. 옛 이름은 M3입니다. Steam Seven Kingdoms 2 HD 정품(2.10e 또는 2.20 베타)이 필요합니다. 원작 게임 파일은 포함하지 않습니다. 일반 공개 배포 중단은 유지되며 이 저장소는 정품 보유자 테스터용입니다.

[정품 보유자용 런처 ZIP](https://github.com/officialsahogany/sk2-m3-tester/releases/latest/download/SK2M3Launcher.zip) · [런처 소스](https://github.com/officialsahogany/sk2-m3-tester/releases/latest/download/SK2M3Launcher-source.zip)

런처 ZIP을 풀고 SK2M3Launcher.exe를 실행합니다. 모드용 빈 폴더 또는 기존 M3/Titan Wars 설치 폴더를 선택한 뒤 업데이트 확인 → 게임 설치/업데이트 → 게임 시작을 누릅니다. Steam 폴더는 원작 확인 창에서만 선택합니다. 원작과 모드는 서로 다른 폴더에 두며 다른 드라이브도 지원합니다. 원작 확인 실패 시 표시된 파일과 Steam 무결성 검사를 확인하세요. 실행 중인 게임을 마친 뒤 업데이트하세요. 자세한 변경 문서와 소스는 설치 폴더 docs와 source에 있습니다.

v30은 2026년 11월 2일 선택한 메인 게임을 담습니다. 런처 프로그램은 검토된 1.25 그대로입니다.

v29 이후 변경:
- 첫 게임 시작 때 리플레이 검증 캐시가 NTFS에서 잠시 멈추던 문제를 고쳤습니다.
- 프라이탄 노예 마을 공물을 원작과 같은 1배로 되돌렸습니다. 엑소붐 번개 폭풍은 4회 타격마다 20에서 30으로 바뀌었습니다.
- 인간 지역 총공세의 60칸 변경을 철회해 40칸으로 되돌렸습니다. 쉬는 야생 용과 병력이 탄 트로이 목마를 다룰 때의 충돌 방지도 포함합니다.
- 유물은 자동으로 줍지 않으며 직접 줍기와 AI 수집은 유지합니다. 일반 유닛의 다이아몬드장·오팔장과 거인 어깨 갑옷의 계급 금속색을 수정했습니다.
- 비마 벌집·타르메스 개미집을 더블클릭으로 함께 선택하고 번식할 수 있습니다. 추방자의 전당 고용 B키, 주인 없는 둥지 매수 E키를 추가했습니다.
- 왕국 배치 Classic / Spread Out 옵션과 공물 마을에서 생기는 신생 왕국 처리를 반영했습니다.
- 브라질 포르투갈어 첫 편집 초안을 추가했습니다. 게임 첫 화면의 언어 순환은 한국어 → English → 简体中文 → Português입니다. 런처 1.25의 언어 메뉴는 한국어·영어·중국어만 지원하므로 Português는 게임 첫 화면에서 선택하세요.

포르투갈어는 기계 번역을 보조로 사용한 첫 편집 초안이며 원어민 검토가 끝나지 않았습니다. 29개 중 28개 글꼴에서 악센트 글자가 작고 1~2픽셀 위로 뜹니다(FNT_SOP 제외). F8 순위 단추는 Patente, 도움말은 Classificação로 서로 다릅니다. 일부 첫 화면 두 줄 단추가 비좁고, 프라이탄 왕 칭호 Supremo / All High와 Fryhtan / Fryhtans 표기가 섞여 있습니다. FNT_BLD 최대 높이는 14에서 15로 바뀌었으며 화면 영향은 찾지 못했습니다. 후속 수정 지시는 있지만 이 판에는 아직 적용되지 않았습니다. 한국어·영어·중국어 문구와 기존 글자 픽셀은 유지합니다.

이 판의 저장 형식은 463입니다. 저장·설정·리플레이 파일은 업데이트 때 보존합니다. 다만 v29 및 이전 판의 녹화는 기록 당시 실행 파일·자료 해시가 달라 업데이트 후 재생할 수 없으며, 파일은 삭제하지 않습니다. v30에서 새로 녹화한 리플레이를 사용하세요. 세계 정복 모드는 리플레이를 기록하지 않습니다. 새 저장을 구버전에서 열 수 있다고 보장하지 않습니다.

알려진 기존 시험 실패는 실패로 유지합니다: 중국어 백과사전 wrapped body fits, 한국어 Tab을 기대하는 hotkeys 판정, startup/research-rule, 티탄 성소 번역 제목, 관전자 참가 AI-tribute-progression, caravan-stock, item-enhancement, blacksmith-input, m3-fort-controls, attack-filter, restart-menu, 유물 작업의 item-tooltip 기존 실패. 별도 관전자 설정·밸런스 측정은 아직 게시되지 않아 포함하지 않았습니다. 네트워크 멀티플레이는 검증하지 않았습니다. 전체 시험이나 모든 옛 저장의 호환을 보장하지 않습니다.

런처 1.25는 버그리포트에 최근 AI 통계 로그를 최대 6개, 파일당 4MiB, 합계 12MiB까지 첨부합니다. 긴 로그는 처음과 끝을 남기고 누락 범위를 기록합니다. 사용자가 보내기 버튼을 눌러야 전송합니다. 인간 AI 유지비 원인 해결을 뜻하지 않으며 P2P 공유 기능은 없습니다. 런처 1.21~1.24는 1.25로 자체 업데이트하고 이미 1.25인 런처는 그대로 사용합니다.

## English

v30 packages the published main game selected on November 2, 2026. The reviewed launcher 1.25 program is unchanged.

Changes since v29: the NTFS replay-cache first-start freeze fix; Fryhtan slave-town tribute restored to its original amount; Exovum Lightning Storm increased from 20 to 30 damage for each of four pulses; withdrawal of the human regional-wave 60-tile change (back to 40); a crash guard for resting wild dragons and occupied Trojan Horses; no automatic relic pickup while manual and AI pickup remain; ordinary Diamond/Opal rank metal and Laestrygonian pauldron rank colours; Bheema-Hyfe/Tarmes-Mownd group selection/breeding; Exiles Hall B and unowned-lair E hotkeys; Classic/Spread Out kingdom placement; newborn kingdoms from tribute towns; Brazilian Portuguese.

Portuguese is a brand-new, machine-assisted first editorial draft. Native-speaker review is pending. Select Português in the game's title-menu cycle (ko, en, zh, pt); launcher 1.25 itself still offers only Korean, English and Chinese. Known limitations: accent glyphs render about 1-2 px high and smaller than base glyphs on 28 of 29 fonts (except FNT_SOP); F8 reads Patente while help/tutorial say Classificação; some two-line title buttons are cramped; Supremo / All High (43 body uses) and Fryhtans (97) / Fryhtan (513) are mixed; FNT_BLD maximum height changed from 14 to 15 (no screen effect found). Fixes are planned but not applied in this build. Existing Korean, English and Chinese text and glyph pixels are retained.

Save format is 463. Saves, settings and recording files are preserved during update. Recordings made in v29 or earlier are cleanly refused after this update because recorded executable/data hashes differ; recording files are kept. New v30 recordings can play. World Conquest does not record replays. Downgrade save compatibility is not guaranteed.

Existing baseline failures remain failures: Chinese encyclopedia wrapped-body-fits, hotkeys Korean-Tab expectation, startup/research-rule assertion, titan sanctuary localized title, spectator-join AI-tribute-progression, caravan-stock, item-enhancement, blacksmith-input, m3-fort-controls, attack-filter, restart-menu and the relic task's existing item-tooltip failure. Separate spectator-setting/balance measurements are unpublished and excluded. Network multiplayer is unverified. No claim covers every test, campaign or historical save.

Launcher 1.25 attaches up to six recent AI-metrics logs to a user-initiated bug report (4 MiB per file, 12 MiB total), retaining the head/tail of oversized files and stating omitted ranges. Sending requires the user to press Send. This is diagnostic support, not a claimed human-AI upkeep fix. There is no P2P sharing. Versions 1.21-1.24 self-update to 1.25; an existing 1.25 launcher stays unchanged.

## 中文

v30包含2026年11月2日选定的已发布主游戏，启动器程序仍为已审核的1.25。

相对v29：修复NTFS回放缓存首次开始卡顿；弗莱坦奴隶城镇贡金恢复原作数值；Exovum雷暴每次伤害20改为30，共4次；撤回人类区域总攻60格改动，恢复40格；防止休息的野龙和载人特洛伊木马相关崩溃；自动拾取排除遗物，保留手动与AI拾取；修正普通单位钻石/蛋白石军衔金属色和巨人肩甲军衔色；蜂巢/蚁巢成组选择与繁殖；流亡者大厅B键雇佣和无主巢穴E键收购；Classic/Spread Out王国分布与贡金城镇新生王国处理；加入巴西葡萄牙语。

葡萄牙语是机器辅助的首版编辑草稿，尚未完成母语者审核。请在游戏标题画面的ko→en→zh→pt语言循环中选择Português；1.25启动器菜单仍仅支持韩、英、中。已知问题包括28/29种字体的重音字符偏小并高出约1至2像素（FNT_SOP除外）、F8按钮Patente与帮助Classificação不一致、部分双行标题按钮拥挤、Supremo/All High以及Fryhtan/Fryhtans混用、FNT_BLD最大高度14改为15但未发现画面影响。修复已计划，但本版尚未应用。韩、英、中原有文本及字形像素保留。

存档格式463。更新保留存档、设置和回放文件。v29及更早回放因记录的可执行文件/资料哈希不同而被明确拒绝播放，文件不会删除；请使用v30新回放。世界征服不录制回放，不保证新存档可用旧版打开。

既有测试失败保留为失败：中文百科换行、hotkeys韩文Tab预期、startup/research-rule、泰坦圣所译名、spectator-join AI-tribute-progression，以及caravan-stock、item-enhancement、blacksmith-input、m3-fort-controls、attack-filter、restart-menu和既有item-tooltip问题。独立的观战设置/平衡测量尚未发布，不在本版内。网络多人游戏未验证。

启动器1.25仅在用户发送错误报告时附带最近AI日志（最多6个、每个4MiB、总计12MiB），长日志保留首尾并说明省略范围；不代表人类AI维护费问题已解决，无P2P共享。1.21至1.24升级为1.25，已有1.25不变。
