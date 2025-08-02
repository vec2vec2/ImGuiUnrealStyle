# ImGuiUnrealStyle
UnrealStyle for ImGui
<img width="1810" height="1298" alt="image" src="https://github.com/user-attachments/assets/94504def-c976-41e8-a21e-d2f9841153b0" />

```c++
   inline void SetupImGuiUnrealStyle()
  {
    // UnrealStyle style by vec2
    // https://github.com/vec2vec2/ImGuiUnrealStyle
    ImGuiStyle& style = ImGui::GetStyle();
    style.Alpha = 1.0f;
    style.DisabledAlpha = 1.0f;
    style.WindowPadding = ImVec2(7, 7);
    style.WindowRounding = 11.5f;
    style.WindowBorderSize = 3;
    style.WindowMinSize = ImVec2(20.0f, 20.0f);
    style.WindowTitleAlign = ImVec2(0.5f, 0.5f);
    style.WindowMenuButtonPosition = ImGuiDir_Right;
    style.ChildRounding = 0.0f;
    style.ChildBorderSize = 1.0f;
    style.PopupRounding = 0.0f;
    style.PopupBorderSize = 1.0f;
    style.FramePadding = ImVec2(8, 5);
    style.FrameRounding = 3;
    style.FrameBorderSize = 1.0f;
    style.ItemSpacing = ImVec2(5.1, 4.0f);
    style.ItemInnerSpacing = ImVec2(4.0, 1.8);
    style.CellPadding = ImVec2(4, 2);
    style.IndentSpacing = 20.0f;
    style.ColumnsMinSpacing = 4.9;
    style.ScrollbarSize = 13.6;
    style.ScrollbarRounding = 15.9;
    style.GrabMinSize = 3.7;
    style.GrabRounding = 4.0f;
    style.TabRounding = 0.0f;
    style.TabBorderSize = 0.0f;
    style.ColorButtonPosition = ImGuiDir_Right;
    style.ButtonTextAlign = ImVec2(0.5f, 0.5f);
    style.SelectableTextAlign = ImVec2(0.0f, 0.0f);
    ImVec4* colors = ImGui::GetStyle().Colors;
    colors[ImGuiCol_Text] = ImVec4(1.00f, 1.00f, 1.00f, 1.00f);
    colors[ImGuiCol_TextDisabled] = ImVec4(0.37f, 0.37f, 0.37f, 1.00f);
    colors[ImGuiCol_WindowBg] = ImVec4(0.08f, 0.08f, 0.08f, 1.00f);
    colors[ImGuiCol_ChildBg] = ImVec4(0.10f, 0.10f, 0.10f, 1.00f);
    colors[ImGuiCol_PopupBg] = ImVec4(0.10f, 0.10f, 0.10f, 1.00f);
    colors[ImGuiCol_Border] = ImVec4(0.21f, 0.21f, 0.21f, 1.00f);
    colors[ImGuiCol_BorderShadow] = ImVec4(0.00f, 0.00f, 0.00f, 0.00f);
    colors[ImGuiCol_FrameBg] = ImVec4(0.06f, 0.06f, 0.06f, 1.00f);
    colors[ImGuiCol_FrameBgHovered] = ImVec4(0.15f, 0.15f, 0.15f, 1.00f);
    colors[ImGuiCol_FrameBgActive] = ImVec4(0.10f, 0.10f, 0.10f, 1.00f);
    colors[ImGuiCol_TitleBg] = ImVec4(0.08f, 0.08f, 0.08f, 1.00f);
    colors[ImGuiCol_TitleBgActive] = ImVec4(0.12f, 0.12f, 0.12f, 1.00f);
    colors[ImGuiCol_TitleBgCollapsed] = ImVec4(0.08f, 0.09f, 0.10f, 0.93f);
    colors[ImGuiCol_MenuBarBg] = ImVec4(0.14f, 0.14f, 0.14f, 1.00f);
    colors[ImGuiCol_ScrollbarBg] = ImVec4(0.10f, 0.10f, 0.10f, 1.00f);
    colors[ImGuiCol_ScrollbarGrab] = ImVec4(0.34f, 0.34f, 0.34f, 1.00f);
    colors[ImGuiCol_ScrollbarGrabHovered] = ImVec4(0.50f, 0.50f, 0.50f, 1.00f);
    colors[ImGuiCol_ScrollbarGrabActive] = ImVec4(0.51f, 0.51f, 0.51f, 1.00f);
    colors[ImGuiCol_CheckMark] = ImVec4(0.00f, 0.44f, 0.88f, 1.00f);
    colors[ImGuiCol_SliderGrab] = ImVec4(0.40f, 0.40f, 0.40f, 1.00f);
    colors[ImGuiCol_SliderGrabActive] = ImVec4(0.60f, 0.60f, 0.60f, 1.00f);
    colors[ImGuiCol_Button] = ImVec4(0.22f, 0.22f, 0.22f, 1.00f);
    colors[ImGuiCol_ButtonHovered] = ImVec4(0.34f, 0.34f, 0.34f, 1.00f);
    colors[ImGuiCol_ButtonActive] = ImVec4(0.18f, 0.18f, 0.18f, 1.00f);
    colors[ImGuiCol_Header] = ImVec4(0.18f, 0.18f, 0.18f, 1.00f);
    colors[ImGuiCol_HeaderHovered] = ImVec4(0.36f, 0.36f, 0.36f, 1.00f);
    colors[ImGuiCol_HeaderActive] = ImVec4(0.17f, 0.17f, 0.17f, 1.00f);
    colors[ImGuiCol_Separator] = ImVec4(0.13f, 0.13f, 0.13f, 1.00f);
    colors[ImGuiCol_SeparatorHovered] = ImVec4(0.16f, 0.18f, 0.25f, 1.00f);
    colors[ImGuiCol_SeparatorActive] = ImVec4(0.16f, 0.18f, 0.25f, 1.00f);
    colors[ImGuiCol_ResizeGrip] = ImVec4(0.15f, 0.15f, 0.15f, 1.00f);
    colors[ImGuiCol_ResizeGripHovered] = ImVec4(0.22f, 0.22f, 0.22f, 1.00f);
    colors[ImGuiCol_ResizeGripActive] = ImVec4(0.31f, 0.31f, 0.31f, 1.00f);
    colors[ImGuiCol_InputTextCursor] = ImVec4(1.00f, 1.00f, 1.00f, 1.00f);
    colors[ImGuiCol_TabHovered] = ImVec4(0.23f, 0.23f, 0.23f, 1.00f);
    colors[ImGuiCol_Tab] = ImVec4(0.11f, 0.11f, 0.11f, 1.00f);
    colors[ImGuiCol_TabSelected] = ImVec4(0.19f, 0.19f, 0.19f, 1.00f);
    colors[ImGuiCol_TabSelectedOverline] = ImVec4(0.00f, 0.44f, 0.88f, 0.00f);
    colors[ImGuiCol_TabDimmed] = ImVec4(0.10f, 0.10f, 0.10f, 0.00f);
    colors[ImGuiCol_TabDimmedSelected] = ImVec4(0.10f, 0.10f, 0.10f, 0.00f);
    colors[ImGuiCol_TabDimmedSelectedOverline] = ImVec4(0.50f, 0.50f, 0.50f, 0.00f);
    colors[ImGuiCol_DockingPreview] = ImVec4(1.00f, 1.00f, 1.00f, 0.47f);
    colors[ImGuiCol_DockingEmptyBg] = ImVec4(0.67f, 0.67f, 0.67f, 1.00f);
    colors[ImGuiCol_PlotLines] = ImVec4(0.52f, 0.60f, 0.70f, 1.00f);
    colors[ImGuiCol_PlotLinesHovered] = ImVec4(0.04f, 0.98f, 0.98f, 1.00f);
    colors[ImGuiCol_PlotHistogram] = ImVec4(0.88f, 0.79f, 0.56f, 1.00f);
    colors[ImGuiCol_PlotHistogramHovered] = ImVec4(0.96f, 0.96f, 0.96f, 1.00f);
    colors[ImGuiCol_TableHeaderBg] = ImVec4(0.05f, 0.05f, 0.07f, 1.00f);
    colors[ImGuiCol_TableBorderStrong] = ImVec4(0.05f, 0.05f, 0.07f, 1.00f);
    colors[ImGuiCol_TableBorderLight] = ImVec4(0.00f, 0.00f, 0.00f, 1.00f);
    colors[ImGuiCol_TableRowBg] = ImVec4(0.12f, 0.13f, 0.15f, 1.00f);
    colors[ImGuiCol_TableRowBgAlt] = ImVec4(0.10f, 0.11f, 0.12f, 1.00f);
    colors[ImGuiCol_TextLink] = ImVec4(0.26f, 0.59f, 0.98f, 1.00f);
    colors[ImGuiCol_TextSelectedBg] = ImVec4(0.00f, 0.44f, 0.88f, 1.00f);
    colors[ImGuiCol_TreeLines] = ImVec4(0.43f, 0.43f, 0.50f, 0.50f);
    colors[ImGuiCol_DragDropTarget] = ImVec4(0.50f, 0.51f, 1.00f, 1.00f);
    colors[ImGuiCol_NavCursor] = ImVec4(0.27f, 0.29f, 1.00f, 1.00f);
    colors[ImGuiCol_NavWindowingHighlight] = ImVec4(0.50f, 0.51f, 1.00f, 1.00f);
    colors[ImGuiCol_NavWindowingDimBg] = ImVec4(0.20f, 0.18f, 0.55f, 0.50f);
    colors[ImGuiCol_ModalWindowDimBg] = ImVec4(0.20f, 0.18f, 0.55f, 0.50f);
  }
```
