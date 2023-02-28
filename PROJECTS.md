# Github projects and how to use it for dqualizer

## Installation

> ⚠️ **If you create a private repository**: You need to add the organization secrets to the repository secrets since our current plan does not allow for organization secrets in private repositories!

1. Create a new repository using this [template](https://github.com/dqualizer/template)
2. This will copy [workflows](.github/workflows) and [issue templates](.github/ISSUE_TEMPLATE/)
3. Link the dqualizer project to the repository ![image](https://user-images.githubusercontent.com/33718194/221803125-5cfb2a24-4c43-466d-aed6-2714c5d86ad0.png) ![image](https://user-images.githubusercontent.com/33718194/221803202-e07edc2f-f7c8-410e-93aa-c860586d452e.png) ![image](https://user-images.githubusercontent.com/33718194/221803327-b815b93e-00b9-41c9-94c3-2fa741359b83.png)
4. Navigate to the [project](https://github.com/orgs/dqualizer/projects/3)

## Github projects

### Landing page

View show the data in a readable format. There are 3 different views - board, table and roadmap.
![image](https://user-images.githubusercontent.com/33718194/221804258-db07eacb-b424-4548-8368-f5e06ce2198a.png)

#### Board
Shows columns of data. Mostly the columns will be created in Settings/Custom fields.
![image](https://user-images.githubusercontent.com/33718194/221804527-1810bf22-cbac-4b1d-8680-40df2af97fcb.png)

#### Table
Shows data grouped by properties (assignees, milestones, labels, ...)
![image](https://user-images.githubusercontent.com/33718194/221805507-5dd7aec8-0142-4b9f-9454-3b7e7f7a5efa.png)

#### Roadmap
Shows data associated with a date or an iteration.
![image](https://user-images.githubusercontent.com/33718194/221805873-b59e6415-59f9-45a5-aa3e-12ebda88ff5c.png)

### Items

#### View Items
Click on the item to get an overview over an issue.
![image](https://user-images.githubusercontent.com/33718194/221812505-3ca30848-2ccf-4e04-89c6-fca62401edcf.png)
![image](https://user-images.githubusercontent.com/33718194/221812540-fb9513f1-101a-4207-ac0a-62270b63a601.png)

#### Edit Items
Just drag and drop items into the specific colmuns or rows.

#### Edit Issue
Navigate to the issue. On the right select the project and choose the values. This is equivalent to dragging and dropping items in the views.
![image](https://user-images.githubusercontent.com/33718194/221818569-542fd8df-f605-4e24-88e6-453d262b84fc.png)

### Views

#### Configure views
Click on the arrow next to a view
![image](https://user-images.githubusercontent.com/33718194/221807727-9f563d97-ab42-45ad-a151-ece00f4b5875.png)

##### Visible fields
Change visible fields (assignees, labels, ...)
![image](https://user-images.githubusercontent.com/33718194/221807818-e38702c0-ee9c-4d8f-86a3-d0c73c39541f.png)

##### Columns (Board)
Change the field that is used to display the columns
![image](https://user-images.githubusercontent.com/33718194/221807989-e19a02d5-3214-4dde-bc05-c9aad2c66d2a.png)

##### Filter
Filter the issues that are shown in the view. (e.g. filter by field status:"🏃 Sprint Backlog" estimate:* or filter by label label:concept)
![image](https://user-images.githubusercontent.com/33718194/221808582-982835fe-ffc2-40e2-891a-fa8ece289b4b.png)

### Workflows

Activate a workflow to get an automation on specific events. More [workflows](.github/workflows)
![image](https://user-images.githubusercontent.com/33718194/221816769-5cbed6aa-a5fc-4fbe-84ef-97cd3ba63440.png)
More [customization](https://docs.github.com/en/issues/planning-and-tracking-with-projects/automating-your-project/using-the-api-to-manage-projects)

### Settings

#### Navigate to settings.

![image](https://user-images.githubusercontent.com/33718194/221804784-c2ff4a77-2038-43b3-82fd-dcfe4241c41d.png)
![image](https://user-images.githubusercontent.com/33718194/221804890-554078fc-883b-443c-9675-21e7784b8d80.png)

#### Custom fields

![image](https://user-images.githubusercontent.com/33718194/221804936-10ef91e2-2cf0-4459-af7f-e4870e379175.png)

##### Edit Custom fields

Edit a custom field by clicking on it and setting new values in field settings.
![image](https://user-images.githubusercontent.com/33718194/221805084-7371d72b-63a3-4cac-867e-070919e4a7e2.png)
![image](https://user-images.githubusercontent.com/33718194/221805197-6a148b94-3aed-4300-9c74-8a0eab30c8cc.png)

##### Field type single select

Create a selection with options that can be used to create kanban boards in the project (used for status, planning poker, ...).
![image](https://user-images.githubusercontent.com/33718194/221806267-72dac012-2a5d-49e2-ac42-84d99286c598.png)
![image](https://user-images.githubusercontent.com/33718194/221806289-b7406b6c-96e4-4688-9619-a03946f555e0.png)

##### Field type iteration

Creates an iteration with a date range (for example 2 weeks). Each iteration gets its own field. Can be used for planning sprint weeks. In the roadmap an iteration can be used to define a date range.
![image](https://user-images.githubusercontent.com/33718194/221806798-1522c508-9a08-4eec-8afe-610b0feeae50.png)
