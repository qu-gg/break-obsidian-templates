---

database-plugin: basic

---

```yaml:dbfolder
name: new database
description: new description
columns:
  __file__:
    key: __file__
    id: __file__
    input: markdown
    label: File
    accessorKey: __file__
    isMetadata: true
    skipPersist: false
    isDragDisabled: false
    csvCandidate: true
    accessor: __file__
    position: 1
    isSorted: true
    isSortedDesc: false
    width: 201
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      source_data: current_folder
  __created__:
    key: __created__
    id: __created__
    input: calendar_time
    label: Created
    accessorKey: __created__
    isMetadata: true
    isDragDisabled: false
    skipPersist: false
    csvCandidate: true
    accessor: __created__
    position: 17
    width: 168
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      source_data: current_folder
  __modified__:
    key: __modified__
    id: __modified__
    input: calendar_time
    label: Modified
    accessorKey: __modified__
    isMetadata: true
    isDragDisabled: false
    skipPersist: false
    csvCandidate: true
    accessor: __modified__
    position: 16
    width: 171
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      source_data: current_folder
  Hearts:
    input: number
    accessor: Location
    key: Hearts
    label: Hearts
    position: 4
    skipPersist: false
    accessorKey: Hearts
    width: 87
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      content_alignment: text-align-center
  Attack:
    input: number
    accessorKey: Attack
    key: Attack
    id: Attack
    label: Attack
    position: 5
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Defense:
    input: text
    accessorKey: Defense
    key: Defense
    id: Defense
    label: Defense
    position: 6
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Speed:
    input: tags
    accessorKey: Speed
    key: Speed
    id: Speed
    label: Speed
    position: 7
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Slow", value: "Slow", color: "hsl(163, 95%, 90%)"}
      - { label: "Average", value: "Average", color: "hsl(35, 95%, 90%)"}
      - { label: "Fast", value: "Fast", color: "hsl(191, 95%, 90%)"}
      - { label: "VeryFast", value: "VeryFast", color: "hsl(84, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
  Might:
    input: number
    accessorKey: Might
    key: Might
    id: Might
    label: Might
    position: 8
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Deftness:
    input: number
    accessorKey: Deftness
    key: Deftness
    id: Deftness
    label: Deftness
    position: 9
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Grit:
    input: number
    accessorKey: Grit
    key: Grit
    id: Grit
    label: Grit
    position: 10
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Insight:
    input: number
    accessorKey: Insight
    key: Insight
    id: Insight
    label: Insight
    position: 11
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Aura:
    input: number
    accessorKey: Aura
    key: Aura
    id: Aura
    label: Aura
    position: 12
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Size:
    input: tags
    accessorKey: Size
    key: Size
    id: Size
    label: Size
    position: 13
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Tiny", value: "Tiny", color: "hsl(231, 95%, 90%)"}
      - { label: "Small", value: "Small", color: "hsl(18, 95%, 90%)"}
      - { label: "Medium", value: "Medium", color: "hsl(3, 95%, 90%)"}
      - { label: "Large", value: "Large", color: "hsl(10, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
  Allegiance:
    input: tags
    accessorKey: Allegiance
    key: Allegiance
    id: Allegiance
    label: Allegiance
    position: 14
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 124
    options:
      - { label: "DarkAligned", value: "DarkAligned", color: "hsl(142, 95%, 90%)"}
      - { label: "LightAligned", value: "LightAligned", color: "hsl(341, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
  AllegiancePoints:
    input: number
    accessorKey: AllegiancePoints
    key: AllegiancePoints
    id: AllegiancePoints
    label: AllegiancePoints
    position: 15
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Level:
    input: tags
    accessor: Type
    key: Level
    label: Level
    position: 2
    skipPersist: false
    accessorKey: Level
    width: 115
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Mook", value: "Mook", color: "hsl(175, 95%, 90%)"}
      - { label: "Boss", value: "Boss", color: "hsl(38, 95%, 90%)"}
      - { label: "MegaBoss", value: "MegaBoss", color: "hsl(319, 95%, 90%)"}
      - { label: "Colossal", value: "Colossal", color: "hsl(40, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      source_data: current_folder
      option_source: manual
  Rank:
    input: number
    accessorKey: Rank
    key: Rank
    id: Rank
    label: Rank
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
config:
  enable_show_state: false
  group_folder_column: 
  remove_field_when_delete_column: true
  cell_size: compact
  sticky_first_column: true
  show_metadata_created: true
  show_metadata_modified: true
  source_data: tag
  source_form_result: "#Adversary"
  show_metadata_tasks: false
  frontmatter_quote_wrap: false
  row_templates_folder: /
  current_row_template: -- Templates/Template - Adversary.md
  pagination_size: 15
  source_destination_path: Adversaries
  remove_empty_folders: false
  automatically_group_files: false
  hoist_files_with_empty_attributes: true
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: top
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
  font_size: 16
  metadata_date_format: "yyyy-MM-dd HH:mm:ss"
  enable_footer: false
  implementation: default
  show_metadata_tags: false
filters:
  enabled: false
  conditions:
```