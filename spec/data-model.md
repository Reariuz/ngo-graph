# Nodes

## Organisation
- actor_id (global, Immutable)
- legal_form (NGO, Partei, Firma, Initiative)
- reach (regional, überregional, Langesweit, Bundesweit, Digital)
- display_name
- description
- created_at
- contact_info

## Label
- Label_id
- name
- description (?)
- created_by (Actor)
- created_at
- epistemic_status (claim | consensus | disputed | deprecated)

## LabelVersion
- label_version_id
- label_id
- name
- descrptin
- valid_from
- valid_to
- supersedes (LabelVersion?)
- change_reason (?)
- changed_by (Actor)

## Project
- project_id
- name
- description
- initiated_by (Actor)
- status(active | dormant | finished)
- start_date
- end_date


# Beziehungen

## Actor_supports_Label
  - actor_id
  - label_id
  - since
  - until

## Label_Relation
- from_label_id
- to_label_id
- type (broader | narrower | overlaps | contradicts | merge_into)
- created_by
- created_at

  
    
