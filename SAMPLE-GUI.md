================================================================
=== CATEGORIZED IMGUI DOCUMENTATION ===
================================================================

Generated: 2025-08-17 14:15:17
Lua Version: Lua 5.4

📊 STATISTIK:
- Functions: 250 (dikategorikan dalam 0 kategori)
- Tables/Enums: 15 (Total items: 217)
- Other Properties: 0
- Global ImGui Functions: 2

📋 DAFTAR ISI (TABLE OF CONTENTS):
================================================================
 1. 📝 WIDGETS - INPUT           (29 functions)
 2. 🪟 WINDOW & LAYOUT           (65 functions)
 3. 🔘 WIDGETS - BASIC           (30 functions)
 4. 🖱️ INPUT & INTERACTION    (21 functions)
 5. 🖼️ DRAWING & RENDERING    (2 functions)
 6. 📊 WIDGETS - DATA            (2 functions)
 7. 🔧 UTILITIES & HELPERS       (8 functions)
 8. 🌐 UNCATEGORIZED             (69 functions)
 9. 🗂️ CONTAINERS & POPUPS    (4 functions)
10. 📏 LAYOUT & POSITIONING      (13 functions)
11. 🎨 STYLE & THEMING           (7 functions)
12. 🗂️  TABLES/ENUMS                   (15 tables)
13. 🌐 GLOBAL FUNCTIONS               (2 functions)

💡 TIP: Gunakan Ctrl+F untuk mencari kategori atau fungsi tertentu!

================================================================
=== 🔍 FUNCTIONS BY CATEGORY ===
================================================================

┌─────────────────────────────────────────────────────────────────┐
│ 🪟 WINDOW & LAYOUT                                           │
└─────────────────────────────────────────────────────────────────┘
  1. ImGui.Begin() [C]
  2. ImGui.BeginChild() [C]
  3. ImGui.BeginChildFrame() [C]
  4. ImGui.BeginDisabled() [C]
  5. ImGui.BeginGroup() [C]
  6. ImGui.BeginMainMenuBar() [C]
  7. ImGui.BeginMenu() [C]
  8. ImGui.BeginMenuBar() [C]
  9. ImGui.BeginPopup() [C]
 10. ImGui.BeginPopupContextItem() [C]
 11. ImGui.BeginPopupContextVoid() [C]
 12. ImGui.BeginPopupContextWindow() [C]
 13. ImGui.BeginPopupModal() [C]
 14. ImGui.BeginTabBar() [C]
 15. ImGui.BeginTabItem() [C]
 16. ImGui.BeginTable() [C]
 17. ImGui.BeginTooltip() [C]
 18. ImGui.Columns() [C]
 19. ImGui.End() [C]
 20. ImGui.EndChild() [C]
 21. ImGui.EndChildFrame() [C]
 22. ImGui.EndDisabled() [C]
 23. ImGui.EndGroup() [C]
 24. ImGui.EndMainMenuBar() [C]
 25. ImGui.EndMenu() [C]
 26. ImGui.EndMenuBar() [C]
 27. ImGui.EndPopup() [C]
 28. ImGui.EndTabBar() [C]
 29. ImGui.EndTabItem() [C]
 30. ImGui.EndTable() [C]
 31. ImGui.EndTooltip() [C]
 32. ImGui.GetColumnsCount() [C]
 33. ImGui.GetFrameHeightWithSpacing() [C]
 34. ImGui.GetTextLineHeightWithSpacing() [C]
 35. ImGui.GetWindowContentRegionMax() [C]
 36. ImGui.GetWindowContentRegionMin() [C]
 37. ImGui.GetWindowHeight() [C]
 38. ImGui.GetWindowPos() [C]
 39. ImGui.GetWindowSize() [C]
 40. ImGui.GetWindowWidth() [C]
 41. ImGui.Indent() [C]
 42. ImGui.IsWindowAppearing() [C]
 43. ImGui.IsWindowCollapsed() [C]
 44. ImGui.IsWindowFocused() [C]
 45. ImGui.IsWindowHovered() [C]
 46. ImGui.NewLine() [C]
 47. ImGui.NextColumn() [C]
 48. ImGui.SameLine() [C]
 49. ImGui.Separator() [C]
 50. ImGui.SeparatorText() [C]
 51. ImGui.SetNextFrameWantCaptureKeyboard() [C]
 52. ImGui.SetNextFrameWantCaptureMouse() [C]
 53. ImGui.SetNextItemOpen() [C]
 54. ImGui.SetNextItemWidth() [C]
 55. ImGui.SetNextWindowBgAlpha() [C]
 56. ImGui.SetNextWindowCollapsed() [C]
 57. ImGui.SetNextWindowContentSize() [C]
 58. ImGui.SetNextWindowFocus() [C]
 59. ImGui.SetNextWindowPos() [C]
 60. ImGui.SetNextWindowScroll() [C]
 61. ImGui.SetNextWindowSize() [C]
 62. ImGui.SetNextWindowSizeConstraints() [C]
 63. ImGui.Spacing() [C]
 64. ImGui.TableNextColumn() [C]
 65. ImGui.Unindent() [C]

┌─────────────────────────────────────────────────────────────────┐
│ 🔘 WIDGETS - BASIC                                           │
└─────────────────────────────────────────────────────────────────┘
  1. ImGui.AlignTextToFramePadding() [C]
  2. ImGui.ArrowButton() [C]
  3. ImGui.Bullet() [C]
  4. ImGui.BulletText() [C]
  5. ImGui.Button() [C]
  6. ImGui.CalcTextSize() [C]
  7. ImGui.Checkbox() [C]
  8. ImGui.CheckboxFlags() [C]
  9. ImGui.ColorButton() [C]
 10. ImGui.GetClipboardText() [C]
 11. ImGui.GetTextLineHeight() [C]
 12. ImGui.Image() [C]
 13. ImGui.ImageButton() [C]
 14. ImGui.InvisibleButton() [C]
 15. ImGui.LabelText() [C]
 16. ImGui.LogButtons() [C]
 17. ImGui.LogText() [C]
 18. ImGui.PopButtonRepeat() [C]
 19. ImGui.PopTextWrapPos() [C]
 20. ImGui.PushButtonRepeat() [C]
 21. ImGui.PushTextWrapPos() [C]
 22. ImGui.RadioButton() [C]
 23. ImGui.SetClipboardText() [C]
 24. ImGui.SmallButton() [C]
 25. ImGui.TabItemButton() [C]
 26. ImGui.Text() [C]
 27. ImGui.TextColored() [C]
 28. ImGui.TextDisabled() [C]
 29. ImGui.TextUnformatted() [C]
 30. ImGui.TextWrapped() [C]

┌─────────────────────────────────────────────────────────────────┐
│ 📝 WIDGETS - INPUT                                           │
└─────────────────────────────────────────────────────────────────┘
  1. ImGui.BeginCombo() [C]
  2. ImGui.BeginListBox() [C]
  3. ImGui.ColorEdit4() [C]
  4. ImGui.Combo() [C]
  5. ImGui.DragFloat() [C]
  6. ImGui.DragInt() [C]
  7. ImGui.DragScalar() [C]
  8. ImGui.EndCombo() [C]
  9. ImGui.EndListBox() [C]
 10. ImGui.GetMouseDragDelta() [C]
 11. ImGui.GetTreeNodeToLabelSpacing() [C]
 12. ImGui.InputFloat() [C]
 13. ImGui.InputInt() [C]
 14. ImGui.InputText() [C]
 15. ImGui.InputTextMultiline() [C]
 16. ImGui.InputTextWithHint() [C]
 17. ImGui.IsMouseDragging() [C]
 18. ImGui.ResetMouseDragDelta() [C]
 19. ImGui.Selectable() [C]
 20. ImGui.SetColorEditOptions() [C]
 21. ImGui.SliderAngle() [C]
 22. ImGui.SliderFloat() [C]
 23. ImGui.SliderInt() [C]
 24. ImGui.SliderScalar() [C]
 25. ImGui.TreeNode() [C]
 26. ImGui.TreeNodeEx() [C]
 27. ImGui.TreePop() [C]
 28. ImGui.VSliderFloat() [C]
 29. ImGui.VSliderInt() [C]

┌─────────────────────────────────────────────────────────────────┐
│ 📊 WIDGETS - DATA                                            │
└─────────────────────────────────────────────────────────────────┘
  1. ImGui.ProgressBar() [C]
  2. ImGui.SetTooltip() [C]

┌─────────────────────────────────────────────────────────────────┐
│ 🗂️ CONTAINERS & POPUPS                                    │
└─────────────────────────────────────────────────────────────────┘
  1. ImGui.CloseCurrentPopup() [C]
  2. ImGui.MenuItem() [C]
  3. ImGui.OpenPopup() [C]
  4. ImGui.OpenPopupOnItemClick() [C]

┌─────────────────────────────────────────────────────────────────┐
│ 🎨 STYLE & THEMING                                           │
└─────────────────────────────────────────────────────────────────┘
  1. ImGui.GetStyleColorVec4() [C]
  2. ImGui.PopID() [C]
  3. ImGui.PopStyleColor() [C]
  4. ImGui.PopStyleVar() [C]
  5. ImGui.PushID() [C]
  6. ImGui.PushStyleColor() [C]
  7. ImGui.PushStyleVar() [C]

┌─────────────────────────────────────────────────────────────────┐
│ 🖱️ INPUT & INTERACTION                                    │
└─────────────────────────────────────────────────────────────────┘
  1. ImGui.GetItemID() [C]
  2. ImGui.GetItemRectMax() [C]
  3. ImGui.GetItemRectMin() [C]
  4. ImGui.GetItemRectSize() [C]
  5. ImGui.GetMousePos() [C]
  6. ImGui.GetMousePosOnOpeningCurrentPopup() [C]
  7. ImGui.IsItemActivated() [C]
  8. ImGui.IsItemActive() [C]
  9. ImGui.IsItemClicked() [C]
 10. ImGui.IsItemDeactivated() [C]
 11. ImGui.IsItemDeactivatedAfterEdit() [C]
 12. ImGui.IsItemEdited() [C]
 13. ImGui.IsItemFocused() [C]
 14. ImGui.IsItemHovered() [C]
 15. ImGui.IsItemToggledOpen() [C]
 16. ImGui.IsItemVisible() [C]
 17. ImGui.IsMouseClicked() [C]
 18. ImGui.IsMouseDown() [C]
 19. ImGui.IsMouseReleased() [C]
 20. ImGui.SetItemAllowOverlap() [C]
 21. ImGui.SetItemDefaultFocus() [C]

┌─────────────────────────────────────────────────────────────────┐
│ 🖼️ DRAWING & RENDERING                                    │
└─────────────────────────────────────────────────────────────────┘
  1. ImGui.GetBackgroundDrawList() [Lua]
  2. ImGui.GetForegroundDrawList() [Lua]

┌─────────────────────────────────────────────────────────────────┐
│ 📏 LAYOUT & POSITIONING                                      │
└─────────────────────────────────────────────────────────────────┘
  1. ImGui.GetContentRegionAvail() [C]
  2. ImGui.GetContentRegionMax() [C]
  3. ImGui.GetCursorPos() [C]
  4. ImGui.GetCursorPosX() [C]
  5. ImGui.GetCursorPosY() [C]
  6. ImGui.GetCursorScreenPos() [C]
  7. ImGui.GetCursorStartPos() [C]
  8. ImGui.GetFrameCount() [C]
  9. ImGui.GetFrameHeight() [C]
 10. ImGui.SetCursorPos() [C]
 11. ImGui.SetCursorPosX() [C]
 12. ImGui.SetCursorPosY() [C]
 13. ImGui.SetCursorScreenPos() [C]

┌─────────────────────────────────────────────────────────────────┐
│ 🔧 UTILITIES & HELPERS                                       │
└─────────────────────────────────────────────────────────────────┘
  1. ImGui.GetVersion() [C]
  2. ImGui.ShowAboutWindow() [C]
  3. ImGui.ShowDemoWindow() [C]
  4. ImGui.ShowFontSelector() [C]
  5. ImGui.ShowMetricsWindow() [C]
  6. ImGui.ShowStyleEditor() [C]
  7. ImGui.ShowStyleSelector() [C]
  8. ImGui.ShowUserGuide() [C]

┌─────────────────────────────────────────────────────────────────┐
│ 🌐 UNCATEGORIZED                                             │
└─────────────────────────────────────────────────────────────────┘
  1. ImGui.CalcItemWidth() [C]
  2. ImGui.CollapsingHeader() [C]
  3. ImGui.ColorConvertFloat4ToU32() [C]
  4. ImGui.ColorConvertHSVtoRGB() [C]
  5. ImGui.ColorConvertRGBtoHSV() [C]
  6. ImGui.ColorConvertU32ToFloat4() [C]
  7. ImGui.Dummy() [C]
  8. ImGui.GetColorU32() [C]
  9. ImGui.GetColumnIndex() [C]
 10. ImGui.GetColumnOffset() [C]
 11. ImGui.GetColumnWidth() [C]
 12. ImGui.GetFontSize() [C]
 13. ImGui.GetFontTexUvWhitePixel() [C]
 14. ImGui.GetID() [C]
 15. ImGui.GetMouseClickedCount() [C]
 16. ImGui.GetMouseCursor() [C]
 17. ImGui.GetScrollMaxX() [C]
 18. ImGui.GetScrollMaxY() [C]
 19. ImGui.GetScrollX() [C]
 20. ImGui.GetScrollY() [C]
 21. ImGui.GetTime() [C]
 22. ImGui.IsAnyItemActive() [C]
 23. ImGui.IsAnyItemFocused() [C]
 24. ImGui.IsAnyItemHovered() [C]
 25. ImGui.IsAnyMouseDown() [C]
 26. ImGui.IsMouseDoubleClicked() [C]
 27. ImGui.IsMouseHoveringRect() [C]
 28. ImGui.IsPopupOpen() [C]
 29. ImGui.IsRectVisible() [C]
 30. ImGui.LogFinish() [C]
 31. ImGui.LogToClipboard() [C]
 32. ImGui.LogToFile() [C]
 33. ImGui.LogToTTY() [C]
 34. ImGui.PopClipRect() [C]
 35. ImGui.PopItemWidth() [C]
 36. ImGui.PushClipRect() [C]
 37. ImGui.PushItemWidth() [C]
 38. ImGui.SetColumnOffset() [C]
 39. ImGui.SetColumnWidth() [C]
 40. ImGui.SetKeyboardFocusHere() [C]
 41. ImGui.SetMouseCursor() [C]
 42. ImGui.SetScrollFromPosX() [C]
 43. ImGui.SetScrollFromPosY() [C]
 44. ImGui.SetScrollHereX() [C]
 45. ImGui.SetScrollHereY() [C]
 46. ImGui.SetScrollX() [C]
 47. ImGui.SetScrollY() [C]
 48. ImGui.SetTabItemClosed() [C]
 49. ImGui.SetWindowCollapsed() [C]
 50. ImGui.SetWindowFocus() [C]
 51. ImGui.SetWindowFontScale() [C]
 52. ImGui.SetWindowPos() [C]
 53. ImGui.SetWindowSize() [C]
 54. ImGui.ShowDebugLogWindow() [C]
 55. ImGui.ShowStackToolWindow() [C]
 56. ImGui.TableGetColumnCount() [C]
 57. ImGui.TableGetColumnFlags() [C]
 58. ImGui.TableGetColumnIndex() [C]
 59. ImGui.TableGetColumnName() [C]
 60. ImGui.TableGetRowIndex() [C]
 61. ImGui.TableHeader() [C]
 62. ImGui.TableHeadersRow() [C]
 63. ImGui.TableNextRow() [C]
 64. ImGui.TableSetBgColor() [C]
 65. ImGui.TableSetColumnEnabled() [C]
 66. ImGui.TableSetColumnIndex() [C]
 67. ImGui.TableSetupColumn() [C]
 68. ImGui.TableSetupScrollFreeze() [C]
 69. ImGui.TreePush() [C]

================================================================
=== 🗂️ TABLES/ENUMS ===
================================================================

┌── ImGui.BG [11 items] ──┐
│ ImGui.BG.__index [TABLE - 0 items]
│   ImGui.BG.__index.__index [TABLE - 0 items]
│     ImGui.BG.__index.__index.__index [TABLE - 0 items]
│     ImGui.BG.__index.__index.AddCircleFilled() [Lua]
│     ImGui.BG.__index.__index.AddCircle() [Lua]
│     ImGui.BG.__index.__index.AddRectFilled() [Lua]
│     ImGui.BG.__index.__index.AddNgon() [Lua]
│     ImGui.BG.__index.__index.AddText() [Lua]
│     ImGui.BG.__index.__index.AddNgonFilled() [Lua]
│     ImGui.BG.__index.__index.AddLine() [Lua]
│     ImGui.BG.__index.__index.AddRectFilledMultiColor() [Lua]
│     ImGui.BG.__index.__index.AddRect() [Lua]
│     ImGui.BG.__index.__index.P = 0 [number]
│   ImGui.BG.__index.AddCircleFilled() [Lua]
│   ImGui.BG.__index.AddCircle() [Lua]
│   ImGui.BG.__index.AddRectFilled() [Lua]
│   ImGui.BG.__index.AddNgon() [Lua]
│   ImGui.BG.__index.AddText() [Lua]
│   ImGui.BG.__index.AddNgonFilled() [Lua]
│   ImGui.BG.__index.AddLine() [Lua]
│   ImGui.BG.__index.AddRectFilledMultiColor() [Lua]
│   ImGui.BG.__index.AddRect() [Lua]
│   ImGui.BG.__index.P = 0 [number]
│ ImGui.BG.AddCircleFilled() [Lua]
│ ImGui.BG.AddCircle() [Lua]
│ ImGui.BG.AddRectFilled() [Lua]
│ ImGui.BG.AddNgon() [Lua]
│ ImGui.BG.AddText() [Lua]
│ ImGui.BG.AddNgonFilled() [Lua]
│ ImGui.BG.AddLine() [Lua]
│ ImGui.BG.AddRectFilledMultiColor() [Lua]
│ ImGui.BG.AddRect() [Lua]
│ ImGui.BG.P = 0 [number]
└─────────────────────────────────┘

┌── ImGui.Col [54 items] ──┐
│ ImGui.Col.TitleBg = 10 [number]
│ ImGui.Col.ScrollbarBg = 14 [number]
│ ImGui.Col.HeaderActive = 26 [number]
│ ImGui.Col.SeparatorHovered = 28 [number]
│ ImGui.Col.TableRowBg = 48 [number]
│ ImGui.Col.ScrollbarGrab = 15 [number]
│ ImGui.Col.TextDisabled = 1 [number]
│ ImGui.Col.Text = 0 [number]
│ ImGui.Col.TabActive = 36 [number]
│ ImGui.Col.TabUnfocusedActive = 39 [number]
│ ImGui.Col.SliderGrab = 19 [number]
│ ImGui.Col.PlotLines = 41 [number]
│ ImGui.Col.SliderGrabActive = 20 [number]
│ ImGui.Col.Separator = 27 [number]
│ ImGui.Col.COUNT = 58 [number]
│ ImGui.Col.ResizeGripActive = 32 [number]
│ ImGui.Col.TitleBgCollapsed = 12 [number]
│ ImGui.Col.ModalWindowDimBg = 57 [number]
│ ImGui.Col.NavWindowingDimBg = 56 [number]
│ ImGui.Col.NavWindowingHighlight = 55 [number]
│ ImGui.Col.ResizeGripHovered = 31 [number]
│ ImGui.Col.NavHighlight = 54 [number]
│ ImGui.Col.DragDropTarget = 53 [number]
│ ImGui.Col.PlotHistogram = 43 [number]
│ ImGui.Col.Button = 21 [number]
│ ImGui.Col.TextSelectedBg = 51 [number]
│ ImGui.Col.TableRowBgAlt = 49 [number]
│ ImGui.Col.ResizeGrip = 30 [number]
│ ImGui.Col.PlotLinesHovered = 42 [number]
│ ImGui.Col.TableBorderLight = 47 [number]
│ ImGui.Col.FrameBgHovered = 8 [number]
│ ImGui.Col.TableBorderStrong = 46 [number]
│ ImGui.Col.FrameBgActive = 9 [number]
│ ImGui.Col.TableHeaderBg = 45 [number]
│ ImGui.Col.PlotHistogramHovered = 44 [number]
│ ImGui.Col.CheckMark = 18 [number]
│ ImGui.Col.Tab = 35 [number]
│ ImGui.Col.TabUnfocused = 38 [number]
│ ImGui.Col.TabHovered = 34 [number]
│ ImGui.Col.Header = 24 [number]
│ ImGui.Col.TitleBgActive = 11 [number]
│ ImGui.Col.ButtonActive = 23 [number]
│ ImGui.Col.FrameBg = 7 [number]
│ ImGui.Col.ScrollbarGrabHovered = 16 [number]
│ ImGui.Col.ButtonHovered = 22 [number]
│ ImGui.Col.Border = 5 [number]
│ ImGui.Col.MenuBarBg = 13 [number]
│ ImGui.Col.WindowBg = 2 [number]
│ ImGui.Col.ChildBg = 3 [number]
│ ImGui.Col.ScrollbarGrabActive = 17 [number]
│ ImGui.Col.SeparatorActive = 29 [number]
│ ImGui.Col.BorderShadow = 6 [number]
│ ImGui.Col.HeaderHovered = 25 [number]
│ ImGui.Col.PopupBg = 4 [number]
└──────────────────────────────────┘

┌── ImGui.Cond [5 items] ──┐
│ ImGui.Cond.Appearing = 8 [number]
│ ImGui.Cond.Always = 1 [number]
│ ImGui.Cond.Once = 2 [number]
│ ImGui.Cond.FirstUseEver = 4 [number]
│ ImGui.Cond.None = 0 [number]
└──────────────────────────────────┘

┌── ImGui.DataType [11 items] ──┐
│ ImGui.DataType.Double = 9 [number]
│ ImGui.DataType.S8 = 0 [number]
│ ImGui.DataType.S32 = 4 [number]
│ ImGui.DataType.S16 = 2 [number]
│ ImGui.DataType.U16 = 3 [number]
│ ImGui.DataType.U8 = 1 [number]
│ ImGui.DataType.U32 = 5 [number]
│ ImGui.DataType.Float = 8 [number]
│ ImGui.DataType.S64 = 6 [number]
│ ImGui.DataType.COUNT = 12 [number]
│ ImGui.DataType.U64 = 7 [number]
└───────────────────────────────────────┘

┌── ImGui.Dir [6 items] ──┐
│ ImGui.Dir.Right = 1 [number]
│ ImGui.Dir.COUNT = 4 [number]
│ ImGui.Dir.Down = 3 [number]
│ ImGui.Dir.Left = 0 [number]
│ ImGui.Dir.None = -1 [number]
│ ImGui.Dir.Up = 2 [number]
└─────────────────────────────────┘

┌── ImGui.DrawFlags [14 items] ──┐
│ ImGui.DrawFlags.RoundCornersLeft = 80 [number]
│ ImGui.DrawFlags.RoundCornersAll = 240 [number]
│ ImGui.DrawFlags.RoundCornersBottom = 192 [number]
│ ImGui.DrawFlags.RoundCornersTopLeft = 16 [number]
│ ImGui.DrawFlags.RoundCornersDefault_ = 240 [number]
│ ImGui.DrawFlags.RoundCornersTop = 48 [number]
│ ImGui.DrawFlags.RoundCornersMask_ = 496 [number]
│ ImGui.DrawFlags.RoundCornersRight = 160 [number]
│ ImGui.DrawFlags.RoundCornersBottomLeft = 64 [number]
│ ImGui.DrawFlags.None = 0 [number]
│ ImGui.DrawFlags.RoundCornersTopRight = 32 [number]
│ ImGui.DrawFlags.RoundCornersNone = 256 [number]
│ ImGui.DrawFlags.RoundCornersBottomRight = 128 [number]
│ ImGui.DrawFlags.Closed = 1 [number]
└────────────────────────────────────────┘

┌── ImGui.DrawListFlags [5 items] ──┐
│ ImGui.DrawListFlags.AntiAliasedLinesUseTex = 2 [number]
│ ImGui.DrawListFlags.AntiAliasedLines = 1 [number]
│ ImGui.DrawListFlags.AntiAliasedFill = 4 [number]
│ ImGui.DrawListFlags.AllowVtxOffset = 8 [number]
│ ImGui.DrawListFlags.None = 0 [number]
└───────────────────────────────────────────┘

┌── ImGui.FG [11 items] ──┐
│ ImGui.FG.__index [TABLE - 0 items]
│   ImGui.FG.__index.__index [TABLE - 0 items]
│     ImGui.FG.__index.__index.__index [TABLE - 0 items]
│     ImGui.FG.__index.__index.AddCircleFilled() [Lua]
│     ImGui.FG.__index.__index.AddCircle() [Lua]
│     ImGui.FG.__index.__index.AddRectFilled() [Lua]
│     ImGui.FG.__index.__index.AddNgon() [Lua]
│     ImGui.FG.__index.__index.AddText() [Lua]
│     ImGui.FG.__index.__index.AddNgonFilled() [Lua]
│     ImGui.FG.__index.__index.AddLine() [Lua]
│     ImGui.FG.__index.__index.AddRectFilledMultiColor() [Lua]
│     ImGui.FG.__index.__index.AddRect() [Lua]
│     ImGui.FG.__index.__index.P = 1 [number]
│   ImGui.FG.__index.AddCircleFilled() [Lua]
│   ImGui.FG.__index.AddCircle() [Lua]
│   ImGui.FG.__index.AddRectFilled() [Lua]
│   ImGui.FG.__index.AddNgon() [Lua]
│   ImGui.FG.__index.AddText() [Lua]
│   ImGui.FG.__index.AddNgonFilled() [Lua]
│   ImGui.FG.__index.AddLine() [Lua]
│   ImGui.FG.__index.AddRectFilledMultiColor() [Lua]
│   ImGui.FG.__index.AddRect() [Lua]
│   ImGui.FG.__index.P = 1 [number]
│ ImGui.FG.AddCircleFilled() [Lua]
│ ImGui.FG.AddCircle() [Lua]
│ ImGui.FG.AddRectFilled() [Lua]
│ ImGui.FG.AddNgon() [Lua]
│ ImGui.FG.AddText() [Lua]
│ ImGui.FG.AddNgonFilled() [Lua]
│ ImGui.FG.AddLine() [Lua]
│ ImGui.FG.AddRectFilledMultiColor() [Lua]
│ ImGui.FG.AddRect() [Lua]
│ ImGui.FG.P = 1 [number]
└─────────────────────────────────┘

┌── ImGui.InputTextFlags [22 items] ──┐
│ ImGui.InputTextFlags.CallbackResize = 4194304 [number]
│ ImGui.InputTextFlags.CharsNoBlank = 16 [number]
│ ImGui.InputTextFlags.NoHorizontalScroll = 32768 [number]
│ ImGui.InputTextFlags.CharsUppercase = 8 [number]
│ ImGui.InputTextFlags.AutoSelectAll = 4096 [number]
│ ImGui.InputTextFlags.CallbackHistory = 524288 [number]
│ ImGui.InputTextFlags.None = 0 [number]
│ ImGui.InputTextFlags.EnterReturnsTrue = 64 [number]
│ ImGui.InputTextFlags.EscapeClearsAll = 128 [number]
│ ImGui.InputTextFlags.CharsHexadecimal = 2 [number]
│ ImGui.InputTextFlags.CallbackCompletion = 262144 [number]
│ ImGui.InputTextFlags.AlwaysOverwrite = 2048 [number]
│ ImGui.InputTextFlags.CallbackAlways = 1048576 [number]
│ ImGui.InputTextFlags.CharsDecimal = 1 [number]
│ ImGui.InputTextFlags.CallbackEdit = 8388608 [number]
│ ImGui.InputTextFlags.ReadOnly = 512 [number]
│ ImGui.InputTextFlags.AllowTabInput = 32 [number]
│ ImGui.InputTextFlags.NoUndoRedo = 65536 [number]
│ ImGui.InputTextFlags.Password = 1024 [number]
│ ImGui.InputTextFlags.CharsScientific = 4 [number]
│ ImGui.InputTextFlags.CallbackCharFilter = 2097152 [number]
│ ImGui.InputTextFlags.CtrlEnterForNewLine = 256 [number]
└─────────────────────────────────────────────┘

┌── ImGui.MouseButton [4 items] ──┐
│ ImGui.MouseButton.Right = 1 [number]
│ ImGui.MouseButton.Left = 0 [number]
│ ImGui.MouseButton.COUNT = 5 [number]
│ ImGui.MouseButton.Middle = 2 [number]
└─────────────────────────────────────────┘

┌── ImGui.MouseCursor [11 items] ──┐
│ ImGui.MouseCursor.ResizeNWSE = 6 [number]
│ ImGui.MouseCursor.ResizeNESW = 5 [number]
│ ImGui.MouseCursor.ResizeEW = 4 [number]
│ ImGui.MouseCursor.COUNT = 11 [number]
│ ImGui.MouseCursor.Hand = 7 [number]
│ ImGui.MouseCursor.Arrow = 0 [number]
│ ImGui.MouseCursor.NotAllowed = 10 [number]
│ ImGui.MouseCursor.ResizeAll = 2 [number]
│ ImGui.MouseCursor.None = -1 [number]
│ ImGui.MouseCursor.ResizeNS = 3 [number]
│ ImGui.MouseCursor.TextInput = 1 [number]
└──────────────────────────────────────────┘

┌── ImGui.SortDirection [3 items] ──┐
│ ImGui.SortDirection.Descending = 2 [number]
│ ImGui.SortDirection.None = 0 [number]
│ ImGui.SortDirection.Ascending = 1 [number]
└───────────────────────────────────────────┘

┌── ImGui.StyleVar [26 items] ──┐
│ ImGui.StyleVar.FrameRounding = 12 [number]
│ ImGui.StyleVar.WindowMinSize = 5 [number]
│ ImGui.StyleVar.TabRounding = 23 [number]
│ ImGui.StyleVar.Alpha = 0 [number]
│ ImGui.StyleVar.GrabMinSize = 20 [number]
│ ImGui.StyleVar.WindowRounding = 3 [number]
│ ImGui.StyleVar.PopupBorderSize = 10 [number]
│ ImGui.StyleVar.ChildBorderSize = 8 [number]
│ ImGui.StyleVar.WindowTitleAlign = 6 [number]
│ ImGui.StyleVar.FrameBorderSize = 13 [number]
│ ImGui.StyleVar.PopupRounding = 9 [number]
│ ImGui.StyleVar.ButtonTextAlign = 31 [number]
│ ImGui.StyleVar.ChildRounding = 7 [number]
│ ImGui.StyleVar.GrabRounding = 21 [number]
│ ImGui.StyleVar.ScrollbarRounding = 19 [number]
│ ImGui.StyleVar.FramePadding = 11 [number]
│ ImGui.StyleVar.ScrollbarSize = 18 [number]
│ ImGui.StyleVar.CellPadding = 17 [number]
│ ImGui.StyleVar.IndentSpacing = 16 [number]
│ ImGui.StyleVar.WindowBorderSize = 4 [number]
│ ImGui.StyleVar.ItemInnerSpacing = 15 [number]
│ ImGui.StyleVar.SelectableTextAlign = 32 [number]
│ ImGui.StyleVar.WindowPadding = 2 [number]
│ ImGui.StyleVar.ItemSpacing = 14 [number]
│ ImGui.StyleVar.COUNT = 36 [number]
│ ImGui.StyleVar.DisabledAlpha = 1 [number]
└───────────────────────────────────────┘

┌── ImGui.TableBgTarget [4 items] ──┐
│ ImGui.TableBgTarget.CellBg = 3 [number]
│ ImGui.TableBgTarget.RowBg1 = 2 [number]
│ ImGui.TableBgTarget.None = 0 [number]
│ ImGui.TableBgTarget.RowBg0 = 1 [number]
└───────────────────────────────────────────┘

┌── ImGui.WindowFlags [30 items] ──┐
│ ImGui.WindowFlags.Tooltip = 33554432 [number]
│ ImGui.WindowFlags.NoNavInputs = 65536 [number]
│ ImGui.WindowFlags.NoCollapse = 32 [number]
│ ImGui.WindowFlags.NoBackground = 128 [number]
│ ImGui.WindowFlags.NoInputs = 197120 [number]
│ ImGui.WindowFlags.ChildMenu = 268435456 [number]
│ ImGui.WindowFlags.NoNav = 196608 [number]
│ ImGui.WindowFlags.NoBringToFrontOnFocus = 8192 [number]
│ ImGui.WindowFlags.NoTitleBar = 1 [number]
│ ImGui.WindowFlags.NoSavedSettings = 256 [number]
│ ImGui.WindowFlags.AlwaysUseWindowPadding = 1073741824 [number]
│ ImGui.WindowFlags.NoDecoration = 43 [number]
│ ImGui.WindowFlags.NoMouseInputs = 512 [number]
│ ImGui.WindowFlags.AlwaysVerticalScrollbar = 16384 [number]
│ ImGui.WindowFlags.NoResize = 2 [number]
│ ImGui.WindowFlags.ChildWindow = 16777216 [number]
│ ImGui.WindowFlags.NavFlattened = 536870912 [number]
│ ImGui.WindowFlags.NoNavFocus = 131072 [number]
│ ImGui.WindowFlags.NoFocusOnAppearing = 4096 [number]
│ ImGui.WindowFlags.Modal = 134217728 [number]
│ ImGui.WindowFlags.MenuBar = 1024 [number]
│ ImGui.WindowFlags.NoScrollWithMouse = 16 [number]
│ ImGui.WindowFlags.UnsavedDocument = 262144 [number]
│ ImGui.WindowFlags.Popup = 67108864 [number]
│ ImGui.WindowFlags.HorizontalScrollbar = 2048 [number]
│ ImGui.WindowFlags.NoScrollbar = 8 [number]
│ ImGui.WindowFlags.None = 0 [number]
│ ImGui.WindowFlags.NoMove = 4 [number]
│ ImGui.WindowFlags.AlwaysAutoResize = 64 [number]
│ ImGui.WindowFlags.AlwaysHorizontalScrollbar = 32768 [number]
└──────────────────────────────────────────┘


================================================================
=== 🌐 GLOBAL IMGUI FUNCTIONS ===
================================================================
  1. ImVec2()
  2. ImVec4()


================================================================
=== ⚡ QUICK REFERENCE (MOST COMMONLY USED) ===
================================================================
WINDOW MANAGEMENT:
  if ImGui.Begin("Window Title") then
    -- Your content here
    ImGui.End()
  end

COMMON WIDGETS:
  ImGui.Text("Hello World")
  if ImGui.Button("Click Me") then -- returns true when clicked
    -- Button was pressed
  end
  value, changed = ImGui.SliderFloat("Slider", value, 0.0, 100.0)

GLOBAL HELPERS:
  ImVec2(width, height)     -- For sizes and positions
  ImVec4(r, g, b, a)        -- For colors (0.0-1.0 range)

================================================================
=== ✅ DOCUMENTATION COMPLETE ===
================================================================

