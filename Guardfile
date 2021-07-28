{
	"info": {
		"_postman_id": "4de2b686-ab03-438f-afc3-bac476855006",
		"name": "Rails Api",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json"
	},
	"item": [
		{
			"name": "admin-user",
			"item": [
				{
					"name": "admin user search",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "query",
								"value": "ben",
								"type": "text",
								"disabled": true
							}
						],
						"body": {
							"mode": "formdata",
							"formdata": [
								{
									"key": "query",
									"value": "h",
									"type": "text"
								}
							]
						},
						"url": {
							"raw": "localhost:3000/api/admin/users",
							"host": [
								"localhost"
							],
							"port": "3000",
							"path": [
								"api",
								"admin",
								"users"
							]
						}
					},
					"response": []
				},
				{
					"name": "admin user get one",
					"request": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "localhost:3000/api/admin/users/2",
							"host": [
								"localhost"
							],
							"port": "3000",
							"path": [
								"api",
								"admin",
								"users",
								"2"
							]
						}
					},
					"response": []
				},
				{
					"name": "admin user create",
					"request": {
						"method": "POST",
						"header": [],
						"body": {
							"mode": "formdata",
							"formdata": [
								{
									"key": "username",
									"value": "caption",
									"description": "validation",
									"type": "text"
								},
								{
									"key": "email",
									"value": "caption@admin.com",
									"description": "validation",
									"type": "text"
								},
								{
									"key": "password",
									"value": "123",
									"type": "text"
								},
								{
									"key": "password_confirmation",
									"value": "123",
									"type": "text"
								},
								{
									"key": "admin",
									"value": "1",
									"description": "0=> normol user, 1=> admin user",
									"type": "text"
								},
								{
									"key": "first_name",
									"value": "Admin",
									"type": "text"
								},
								{
									"key": "last_name",
									"value": "User",
									"type": "text"
								},
								{
									"key": "title",
									"value": "project Manager",
									"type": "text"
								},
								{
									"key": "company",
									"value": "Company Of Travel",
									"type": "text"
								},
								{
									"key": "group_ids[]",
									"value": "11",
									"type": "text"
								},
								{
									"key": "group_ids[]",
									"value": "12",
									"type": "text"
								},
								{
									"key": "commit",
									"value": "Save User",
									"type": "text",
									"disabled": true
								}
							]
						},
						"url": {
							"raw": "localhost:3000/api/admin/users",
							"host": [
								"localhost"
							],
							"port": "3000",
							"path": [
								"api",
								"admin",
								"users"
							]
						}
					},
					"response": []
				},
				{
					"name": "admin user update",
					"request": {
						"method": "POST",
						"header": [],
						"body": {
							"mode": "formdata",
							"formdata": [
								{
									"key": "username",
									"value": "UpdateUser113",
									"type": "text"
								},
								{
									"key": "email",
									"value": "caption1@gmail.com",
									"type": "text",
									"disabled": true
								}
							]
						},
						"url": {
							"raw": "localhost:3000/api/admin/users/10",
							"host": [
								"localhost"
							],
							"port": "3000",
							"path": [
								"api",
								"admin",
								"users",
								"10"
							]
						}
					},
					"response": []
				},
				{
					"name": "admin user delete",
					"request": {
						"method": "POST",
						"header": [],
						"url": {
							"raw": "localhost:3000/api/admin/users/10/delete",
							"host": [
								"localhost"
							],
							"port": "3000",
							"path": [
								"api",
								"admin",
								"users",
								"10",
								"delete"
							]
						}
					},
					"response": []
				},
				{
					"name": "admin user suspend",
					"request": {
						"method": "POST",
						"header": [],
						"body": {
							"mode": "formdata",
							"formdata": [
								{
									"key": "id",
									"value": "11",
									"type": "text",
									"disabled": true
								}
							]
						},
						"url": {
							"raw": "localhost:3000/api/admin/users/7/suspend",
							"host": [
								"localhost"
							],
							"port": "3000",
							"path": [
								"api",
								"admin",
								"users",
								"7",
								"suspend"
							]
						}
					},
					"response": []
				},
				{
					"name": "admin user reactivate",
					"request": {
						"method": "POST",
						"header": [],
						"url": {
							"raw": "localhost:3000/api/admin/users/7/reactivate",
							"host": [
								"localhost"
							],
							"port": "3000",
							"path": [
								"api",
								"admin",
								"users",
								"7",
								"reactivate"
							]
						}
					},
					"response": []
				}
			]
		},
		{
			"name": "admin-group",
			"item": [
				{
					"name": "admin group get all",
					"request": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "localhost:3000/api/admin/groups",
							"host": [
								"localhost"
							],
							"port": "3000",
							"path": [
								"api",
								"admin",
								"groups"
							]
						}
					},
					"response": []
				},
				{
					"name": "admin group update",
					"request": {
						"method": "POST",
						"header": [],
						"body": {
							"mode": "formdata",
							"formdata": [
								{
									"key": "id",
									"value": "10",
									"type": "text",
									"disabled": true
								},
								{
									"key": "name",
									"value": "update test",
									"type": "text"
								}
							]
						},
						"url": {
							"raw": "localhost:3000/api/admin/groups/11",
							"host": [
								"localhost"
							],
							"port": "3000",
							"path": [
								"api",
								"admin",
								"groups",
								"11"
							],
							"query": [
								{
									"key": "id",
									"value": "10",
									"disabled": true
								},
								{
									"key": "name",
									"value": "update test",
									"disabled": true
								}
							]
						}
					},
					"response": []
				},
				{
					"name": "admin group get one",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [],
						"body": {
							"mode": "formdata",
							"formdata": [
								{
									"key": "id",
									"value": "2",
									"type": "text",
									"disabled": true
								}
							]
						},
						"url": {
							"raw": "localhost:3000/api/admin/groups/11",
							"host": [
								"localhost"
							],
							"port": "3000",
							"path": [
								"api",
								"admin",
								"groups",
								"11"
							],
							"query": [
								{
									"key": "id",
									"value": "1",
									"disabled": true
								}
							]
						}
					},
					"response": []
				},
				{
					"name": "admin group creat",
					"request": {
						"method": "POST",
						"header": [],
						"body": {
							"mode": "formdata",
							"formdata": [
								{
									"key": "name",
									"value": "test3 group",
									"type": "text"
								},
								{
									"key": "user_ids[]",
									"value": "1",
									"type": "text"
								},
								{
									"key": "user_ids[]",
									"value": "2",
									"type": "text",
									"disabled": true
								},
								{
									"key": "user_ids[]",
									"value": "5",
									"type": "text",
									"disabled": true
								}
							]
						},
						"url": {
							"raw": "localhost:3000/api/admin/groups",
							"host": [
								"localhost"
							],
							"port": "3000",
							"path": [
								"api",
								"admin",
								"groups"
							],
							"query": [
								{
									"key": "name",
									"value": "test group",
									"disabled": true
								},
								{
									"key": "user_ids",
									"value": "[1,2,3,4]",
									"disabled": true
								}
							]
						}
					},
					"response": []
				},
				{
					"name": "admin group delete",
					"request": {
						"method": "POST",
						"header": [],
						"url": {
							"raw": "localhost:3000/api/admin/groups/11/delete",
							"host": [
								"localhost"
							],
							"port": "3000",
							"path": [
								"api",
								"admin",
								"groups",
								"11",
								"delete"
							]
						}
					},
					"response": []
				}
			]
		},
		{
			"name": "admin-field_group",
			"item": [
				{
					"name": "admin field_group create",
					"request": {
						"method": "POST",
						"header": [],
						"body": {
							"mode": "formdata",
							"formdata": [
								{
									"key": "klass_name",
									"value": "Account",
									"type": "text"
								},
								{
									"key": "label",
									"value": "test field group",
									"type": "text"
								},
								{
									"key": "tag_id",
									"value": "6",
									"type": "text"
								}
							]
						},
						"url": {
							"raw": "localhost:3000/api/admin/field_groups",
							"host": [
								"localhost"
							],
							"port": "3000",
							"path": [
								"api",
								"admin",
								"field_groups"
							]
						}
					},
					"response": []
				},
				{
					"name": "admin field_group update",
					"request": {
						"method": "POST",
						"header": [],
						"body": {
							"mode": "formdata",
							"formdata": [
								{
									"key": "klass_name",
									"value": "Account",
									"type": "text"
								},
								{
									"key": "label",
									"value": "label1",
									"type": "text"
								},
								{
									"key": "tag_id",
									"value": "3",
									"type": "text"
								}
							]
						},
						"url": {
							"raw": "localhost:3000/api/admin/field_groups/2",
							"host": [
								"localhost"
							],
							"port": "3000",
							"path": [
								"api",
								"admin",
								"field_groups",
								"2"
							]
						}
					},
					"response": []
				},
				{
					"name": "admin field_group delete",
					"request": {
						"method": "POST",
						"header": [],
						"url": {
							"raw": "localhost:3000/api/admin/field_groups/2/delete",
							"host": [
								"localhost"
							],
							"port": "3000",
							"path": [
								"api",
								"admin",
								"field_groups",
								"2",
								"delete"
							]
						}
					},
					"response": []
				},
				{
					"name": "admin field_group search with klass_name",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [],
						"body": {
							"mode": "formdata",
							"formdata": [
								{
									"key": "klass_name",
									"value": "Account",
									"type": "text"
								}
							]
						},
						"url": {
							"raw": "localhost:3000/api/admin/field_groups",
							"host": [
								"localhost"
							],
							"port": "3000",
							"path": [
								"api",
								"admin",
								"field_groups"
							]
						}
					},
					"response": []
				},
				{
					"name": "admin filed_group get one",
					"request": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "localhost:3000/api/admin/field_groups/3",
							"host": [
								"localhost"
							],
							"port": "3000",
							"path": [
								"api",
								"admin",
								"field_groups",
								"3"
							]
						}
					},
					"response": []
				}
			]
		},
		{
			"name": "admin-field",
			"item": [
				{
					"name": "admin field create",
					"request": {
						"method": "POST",
						"header": [
							{
								"key": "",
								"value": "6",
								"equals": true
							},
							{
								"key": "label",
								"value": "Add Field Test",
								"equals": true
							},
							{
								"key": "as",
								"value": "radio_buutton",
								"equals": true,
								"description": "Short Answer=>string, Long Answer=>text, Email, Address=>email, Url=>url, Phone Number=>tel. Select List=>select, Radio Buttons=>raio_button, CheckBox List=>check_boxes, Checkbox=>boolean, Date=>date, Date & Time=> datetime, Number(Decimal)=>decimal, Number(Integer)=>integer, Number(Floating Point)=>float, Date Pair=>date_pair, Date & Time Pair=>datetime_pair"
							},
							{
								"key": "collection_string",
								"value": null,
								"equals": false,
								"description": "+radio_button,+boolean"
							},
							{
								"key": "required",
								"value": "1",
								"equals": true,
								"description": "0=> unrequired, 1=> required"
							},
							{
								"key": "disabled",
								"value": "0",
								"equals": true,
								"description": "0=> enable, 1=>disable"
							},
							{
								"key": "hit",
								"value": null,
								"equals": false
							},
							{
								"key": "placeholder",
								"value": null,
								"equals": false,
								"description": "-datetime,-decimal"
							}
						],
						"body": {
							"mode": "formdata",
							"formdata": [
								{
									"key": "field[field_group_id]",
									"value": "6"
								},
								{
									"key": "field[label]",
									"value": "Add Field Test"
								},
								{
									"key": "field[as]",
									"value": "string",
									"description": "Short Answer=>string, Long Answer=>text, Email, Address=>email, Url=>url, Phone Number=>tel. Select List=>select, Radio Buttons=>raio_button, CheckBox List=>check_boxes, Checkbox=>boolean, Date=>date, Date & Time=> datetime, Number(Decimal)=>decimal, Number(Integer)=>integer, Number(Floating Point)=>float, Date Pair=>date_pair, Date & Time Pair=>datetime_pair"
								},
								{
									"key": "field[collection_string]",
									"value": null,
									"description": "+radio_button,+boolean",
									"disabled": true
								},
								{
									"key": "field[required]",
									"value": "1",
									"description": "0=> unrequired, 1=> required"
								},
								{
									"key": "field[disabled]",
									"value": "0",
									"description": "0=> enable, 1=>disable"
								},
								{
									"key": "field[hint]",
									"value": "1"
								},
								{
									"key": "field[placeholder]",
									"value": "2",
									"description": "-datetime,-decimal"
								},
								{
									"key": "field[minlength]",
									"value": "0",
									"description": "-radio_button,-datetime,-decimal"
								},
								{
									"key": "field[maxlength]",
									"value": "100",
									"description": "-radio_button,-datetime,-decimal"
								},
								{
									"key": "pair[0][hint]",
									"value": null,
									"description": "datetime_pair",
									"disabled": true
								},
								{
									"key": "pair[0][required]",
									"value": "0",
									"description": "datetime_pair",
									"disabled": true
								},
								{
									"key": "pair[0][disabled]",
									"value": "0",
									"description": "datetime_pair",
									"disabled": true
								},
								{
									"key": "pair[0][id]",
									"value": null,
									"description": "datetime_pair",
									"disabled": true
								},
								{
									"key": "pair[1][id]",
									"value": null,
									"description": "datetime_pair",
									"disabled": true
								}
							]
						},
						"url": {
							"raw": "localhost:3000/api/admin/fields/",
							"host": [
								"localhost"
							],
							"port": "3000",
							"path": [
								"api",
								"admin",
								"fields",
								""
							],
							"query": [
								{
									"key": "field_group_id",
									"value": "6",
									"disabled": true
								},
								{
									"key": "label",
									"value": "Add Field Test",
									"disabled": true
								},
								{
									"key": "as",
									"value": "radio_buutton",
									"description": "Short Answer=>string, Long Answer=>text, Email, Address=>email, Url=>url, Phone Number=>tel. Select List=>select, Radio Buttons=>raio_button, CheckBox List=>check_boxes, Checkbox=>boolean, Date=>date, Date & Time=> datetime, Number(Decimal)=>decimal, Number(Integer)=>integer, Number(Floating Point)=>float, Date Pair=>date_pair, Date & Time Pair=>datetime_pair",
									"disabled": true
								},
								{
									"key": "collection_string",
									"value": null,
									"description": "+radio_button,+boolean",
									"disabled": true
								},
								{
									"key": "required",
									"value": "1",
									"description": "0=> unrequired, 1=> required",
									"disabled": true
								},
								{
									"key": "disabled",
									"value": "0",
									"description": "0=> enable, 1=>disable",
									"disabled": true
								},
								{
									"key": "hit",
									"value": null,
									"disabled": true
								},
								{
									"key": "placeholder",
									"value": null,
									"description": "-datetime,-decimal",
									"disabled": true
								},
								{
									"key": "minlength",
									"value": "0",
									"description": "-radio_button,-datetime,-decimal",
									"disabled": true
								},
								{
									"key": "maxlength",
									"value": "100",
									"description": "-radio_button,-datetime,-decimal",
									"disabled": true
								},
								{
									"key": "pair[0][hint]",
									"value": null,
									"description": "datetime_pair",
									"disabled": true
								},
								{
									"key": "pair[0][required]",
									"value": "0",
									"description": "datetime_pair",
									"disabled": true
								},
								{
									"key": "pair[0][disabled]",
									"value": "0",
									"description": "datetime_pair",
									"disabled": true
								},
								{
									"key": "pair[0][id]",
									"value": null,
									"description": "datetime_pair",
									"disabled": true
								},
								{
									"key": "pair[1][id]",
									"value": null,
									"description": "datetime_pair",
									"disabled": true
								}
							]
						}
					},
					"response": []
				},
				{
					"name": "admin field get one",
					"request": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "localhost:3000/api/admin/fields/3",
							"host": [
								"localhost"
							],
							"port": "3000",
							"path": [
								"api",
								"admin",
								"fields",
								"3"
							]
						}
					},
					"response": []
				},
				{
					"name": "admin field update",
					"request": {
						"method": "POST",
						"header": [],
						"body": {
							"mode": "formdata",
							"formdata": [
								{
									"key": "field[field_group_id]",
									"value": "6"
								},
								{
									"key": "field[label]",
									"value": "Add Field Test1"
								},
								{
									"key": "field[as]",
									"value": "string",
									"description": "Short Answer=>string, Long Answer=>text, Email, Address=>email, Url=>url, Phone Number=>tel. Select List=>select, Radio Buttons=>raio_button, CheckBox List=>check_boxes, Checkbox=>boolean, Date=>date, Date & Time=> datetime, Number(Decimal)=>decimal, Number(Integer)=>integer, Number(Floating Point)=>float, Date Pair=>date_pair, Date & Time Pair=>datetime_pair"
								}
							]
						},
						"url": {
							"raw": "localhost:3000/api/admin/fields/2",
							"host": [
								"localhost"
							],
							"port": "3000",
							"path": [
								"api",
								"admin",
								"fields",
								"2"
							],
							"query": [
								{
									"key": "field[field_group_id]",
									"value": "6",
									"disabled": true
								},
								{
									"key": "field[label]",
									"value": "Add Field Test",
									"disabled": true
								},
								{
									"key": "field[as]",
									"value": "string",
									"description": "Short Answer=>string, Long Answer=>text, Email, Address=>email, Url=>url, Phone Number=>tel. Select List=>select, Radio Buttons=>raio_button, CheckBox List=>check_boxes, Checkbox=>boolean, Date=>date, Date & Time=> datetime, Number(Decimal)=>decimal, Number(Integer)=>integer, Number(Floating Point)=>float, Date Pair=>date_pair, Date & Time Pair=>datetime_pair",
									"disabled": true
								},
								{
									"key": "",
									"value": null,
									"disabled": true
								}
							]
						}
					},
					"response": []
				},
				{
					"name": "admin field delete",
					"request": {
						"method": "POST",
						"header": [],
						"url": {
							"raw": "localhost:3000/api/admin/fields/2/delete",
							"host": [
								"localhost"
							],
							"port": "3000",
							"path": [
								"api",
								"admin",
								"fields",
								"2",
								"delete"
							]
						}
					},
					"response": []
				}
			]
		},
		{
			"name": "admin-tag",
			"item": [
				{
					"name": "admin tag get all",
					"request": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "localhost:3000/api/admin/tags",
							"host": [
								"localhost"
							],
							"port": "3000",
							"path": [
								"api",
								"admin",
								"tags"
							]
						}
					},
					"response": []
				},
				{
					"name": "admin tag update",
					"request": {
						"method": "POST",
						"header": [],
						"body": {
							"mode": "formdata",
							"formdata": [
								{
									"key": "name",
									"value": "update tag name",
									"type": "text"
								}
							]
						},
						"url": {
							"raw": "localhost:3000/api/admin/tags/3",
							"host": [
								"localhost"
							],
							"port": "3000",
							"path": [
								"api",
								"admin",
								"tags",
								"3"
							],
							"query": [
								{
									"key": "name",
									"value": "update tag",
									"disabled": true
								}
							]
						}
					},
					"response": []
				},
				{
					"name": "admin tag create",
					"request": {
						"method": "POST",
						"header": [],
						"body": {
							"mode": "formdata",
							"formdata": [
								{
									"key": "name",
									"value": "test tag",
									"type": "text"
								},
								{
									"key": "taggings_count",
									"value": "",
									"type": "text"
								}
							]
						},
						"url": {
							"raw": "localhost:3000/api/admin/tags",
							"host": [
								"localhost"
							],
							"port": "3000",
							"path": [
								"api",
								"admin",
								"tags"
							],
							"query": [
								{
									"key": "name",
									"value": "test tag",
									"disabled": true
								},
								{
									"key": "",
									"value": null,
									"disabled": true
								}
							]
						}
					},
					"response": []
				},
				{
					"name": "admin tag delete",
					"request": {
						"method": "POST",
						"header": [],
						"url": {
							"raw": "localhost:3000/api/admin/tags/2/delete",
							"host": [
								"localhost"
							],
							"port": "3000",
							"path": [
								"api",
								"admin",
								"tags",
								"2",
								"delete"
							]
						}
					},
					"response": []
				}
			]
		},
		{
			"name": "Entities",
			"item": [
				{
					"name": "accounts",
					"item": [
						{
							"name": "all",
							"protocolProfileBehavior": {
								"disableBodyPruning": true
							},
							"request": {
								"method": "GET",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": [
										{
											"key": "query",
											"value": "h",
											"type": "text"
										}
									]
								},
								"url": {
									"raw": "localhost:3000/api/entities/accounts",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"accounts"
									]
								}
							},
							"response": []
						},
						{
							"name": "show",
							"protocolProfileBehavior": {
								"disableBodyPruning": true
							},
							"request": {
								"method": "GET",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": []
								},
								"url": {
									"raw": "localhost:3000/api/entities/accounts/1",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"accounts",
										"1"
									]
								}
							},
							"response": []
						},
						{
							"name": "edit",
							"protocolProfileBehavior": {
								"disableBodyPruning": true
							},
							"request": {
								"method": "GET",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": []
								},
								"url": {
									"raw": "localhost:3000/api/entities/accounts/1/edit",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"accounts",
										"1",
										"edit"
									]
								}
							},
							"response": []
						},
						{
							"name": "delete",
							"request": {
								"method": "POST",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": []
								},
								"url": {
									"raw": "localhost:3000/api/entities/accounts/1/delete",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"accounts",
										"1",
										"delete"
									]
								}
							},
							"response": []
						},
						{
							"name": "update",
							"request": {
								"method": "POST",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": [
										{
											"key": "account[name]",
											"value": "10",
											"type": "text"
										},
										{
											"key": "account[assigned_to]",
											"value": "2",
											"type": "text"
										},
										{
											"key": "account[billing[address]]",
											"value": "sdcsec",
											"type": "text",
											"disabled": true
										},
										{
											"key": "account[shipping[address]]",
											"value": "fdger",
											"type": "text",
											"disabled": true
										}
									]
								},
								"url": {
									"raw": "localhost:3000/api/entities/accounts/4",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"accounts",
										"4"
									],
									"query": [
										{
											"key": "opportunity[user_id]",
											"value": "2",
											"disabled": true
										},
										{
											"key": "opportunity[name]",
											"value": "estesdf",
											"disabled": true
										}
									]
								}
							},
							"response": []
						},
						{
							"name": "create",
							"request": {
								"method": "POST",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": [
										{
											"key": "account[name]",
											"value": "asdcae",
											"type": "text"
										},
										{
											"key": "account[assigned_to]",
											"value": "2",
											"type": "text"
										},
										{
											"key": "account[billing[address]]",
											"value": "sdcsec",
											"type": "text",
											"disabled": true
										},
										{
											"key": "account[shipping[address]]",
											"value": "fdger",
											"type": "text",
											"disabled": true
										}
									]
								},
								"url": {
									"raw": "localhost:3000/api/entities/accounts/",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"accounts",
										""
									],
									"query": [
										{
											"key": "opportunity[user_id]",
											"value": "2",
											"disabled": true
										},
										{
											"key": "opportunity[name]",
											"value": "estesdf",
											"disabled": true
										}
									]
								}
							},
							"response": []
						}
					]
				},
				{
					"name": "leads",
					"item": [
						{
							"name": "all",
							"protocolProfileBehavior": {
								"disableBodyPruning": true
							},
							"request": {
								"method": "GET",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": [
										{
											"key": "query",
											"value": "he",
											"type": "text"
										}
									]
								},
								"url": {
									"raw": "localhost:3000/api/entities/leads",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"leads"
									]
								}
							},
							"response": []
						},
						{
							"name": "one",
							"protocolProfileBehavior": {
								"disableBodyPruning": true
							},
							"request": {
								"method": "GET",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": [
										{
											"key": "query",
											"value": "he",
											"type": "text",
											"disabled": true
										}
									]
								},
								"url": {
									"raw": "localhost:3000/api/entities/leads/4",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"leads",
										"4"
									]
								}
							},
							"response": []
						},
						{
							"name": "delete",
							"request": {
								"method": "POST",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": [
										{
											"key": "query",
											"value": "he",
											"type": "text",
											"disabled": true
										}
									]
								},
								"url": {
									"raw": "localhost:3000/api/entities/leads/4/delete",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"leads",
										"4",
										"delete"
									]
								}
							},
							"response": []
						},
						{
							"name": "update",
							"request": {
								"method": "POST",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": [
										{
											"key": "lead[user_id]",
											"value": "5",
											"type": "text"
										},
										{
											"key": "ead[user_id]: 5\nlead[first_name]: Michael\nlead[last_name]: Jackson\nlead[email]: michael.jackson@jackson.com\nlead[phone]: 000234 7892\nlead[tag_list][]: \nlead[tag_list][]: 下級\nlead[tag_list][]: Homes\nlead[assigned_to]: \nlead[status]: new\nlead[rating]: 0\nlead[source]: other\nlead[campaign_id]: \nlead[title]: \nlead[company]: \nlead[alt_email]: \nlead[mobile]: \nlead[business_address_attributes][address_type]: Business\nlead[business_address_attributes][street1]: \nlead[business_address_attributes][street2]: \nlead[business_address_attributes][city]: \nlead[business_address_attributes][state]: \nlead[business_address_attributes][zipcode]: \nlead[business_address_attributes][country]: \nlead[business_address_attributes][id]: 428\nlead[referred_by]: \nlead[do_not_call]: 0\nlead[blog]: \nlead[twitter]: \nlead[linkedin]: \nlead[facebook]: \nlead[skype]: \nlead[cf_street_address]: \nlead[cf_rep_name]: Kat\nlead[cf_type_of_facility][]: \nlead[cf_dfdsffdf]: \nlead[access]: Public\nlead[user_ids][]: \nlead[group_ids][]:",
											"value": "",
											"type": "text",
											"disabled": true
										}
									]
								},
								"url": {
									"raw": "localhost:3000/api/entities/leads/5",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"leads",
										"5"
									]
								}
							},
							"response": []
						},
						{
							"name": "create",
							"request": {
								"method": "POST",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": [
										{
											"key": "lead[user_id]",
											"value": "5",
											"type": "text"
										},
										{
											"key": "ead[user_id]: 5\nlead[first_name]: Michael\nlead[last_name]: Jackson\nlead[email]: michael.jackson@jackson.com\nlead[phone]: 000234 7892\nlead[tag_list][]: \nlead[tag_list][]: 下級\nlead[tag_list][]: Homes\nlead[assigned_to]: \nlead[status]: new\nlead[rating]: 0\nlead[source]: other\nlead[campaign_id]: \nlead[title]: \nlead[company]: \nlead[alt_email]: \nlead[mobile]: \nlead[business_address_attributes][address_type]: Business\nlead[business_address_attributes][street1]: \nlead[business_address_attributes][street2]: \nlead[business_address_attributes][city]: \nlead[business_address_attributes][state]: \nlead[business_address_attributes][zipcode]: \nlead[business_address_attributes][country]: \nlead[business_address_attributes][id]: 428\nlead[referred_by]: \nlead[do_not_call]: 0\nlead[blog]: \nlead[twitter]: \nlead[linkedin]: \nlead[facebook]: \nlead[skype]: \nlead[cf_street_address]: \nlead[cf_rep_name]: Kat\nlead[cf_type_of_facility][]: \nlead[cf_dfdsffdf]: \nlead[access]: Public\nlead[user_ids][]: \nlead[group_ids][]:",
											"value": "",
											"type": "text",
											"disabled": true
										}
									]
								},
								"url": {
									"raw": "localhost:3000/api/entities/leads",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"leads"
									]
								}
							},
							"response": []
						},
						{
							"name": "convert",
							"request": {
								"method": "POST",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": [
										{
											"key": "account[user_id]",
											"value": "5",
											"type": "text"
										},
										{
											"key": "account[user_id]: 2\naccount[access]: Lead\naccount[name]: \naccount[assigned_to]: \nopportunity[user_id]: 2\nopportunity[access]: Lead\nopportunity[assigned_to]: \nopportunity[campaign_id]: 179\nopportunity[source]: campaign\nopportunity[name]: \nopportunity[stage]: prospecting\nopportunity[closes_on]: \nopportunity[probability]: \nopportunity[amount]: \nopportunity[discount]: \naccess: Lead\nlead[user_ids][]: \nlead[group_ids][]: ",
											"value": "",
											"type": "text",
											"disabled": true
										},
										{
											"key": "account[access]",
											"value": "Lead",
											"type": "text"
										},
										{
											"key": "account[name]",
											"value": "qwe",
											"type": "text"
										},
										{
											"key": "opportunity[campaign_id]",
											"value": "179",
											"type": "text"
										}
									]
								},
								"url": {
									"raw": "localhost:3000/api/entities/leads/5/convert",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"leads",
										"5",
										"convert"
									]
								}
							},
							"response": []
						},
						{
							"name": "reject",
							"request": {
								"method": "POST",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": []
								},
								"url": {
									"raw": "localhost:3000/api/entities/leads/5/reject",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"leads",
										"5",
										"reject"
									]
								}
							},
							"response": []
						}
					]
				},
				{
					"name": "contacts",
					"item": [
						{
							"name": "all",
							"protocolProfileBehavior": {
								"disableBodyPruning": true
							},
							"request": {
								"method": "GET",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": [
										{
											"key": "query",
											"value": "q",
											"type": "text"
										}
									]
								},
								"url": {
									"raw": "localhost:3000/api/entities/contacts",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"contacts"
									]
								}
							},
							"response": []
						},
						{
							"name": "show",
							"protocolProfileBehavior": {
								"disableBodyPruning": true
							},
							"request": {
								"method": "GET",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": []
								},
								"url": {
									"raw": "localhost:3000/api/entities/contacts/1",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"contacts",
										"1"
									]
								}
							},
							"response": []
						},
						{
							"name": "edit",
							"protocolProfileBehavior": {
								"disableBodyPruning": true
							},
							"request": {
								"method": "GET",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": []
								},
								"url": {
									"raw": "localhost:3000/api/entities/contacts/1/edit",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"contacts",
										"1",
										"edit"
									]
								}
							},
							"response": []
						},
						{
							"name": "create",
							"request": {
								"method": "POST",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": [
										{
											"key": "contact[user_id]",
											"value": "3"
										},
										{
											"key": "contact[first_name]",
											"value": "blajnjnef"
										},
										{
											"key": "account[user_id]",
											"value": "2"
										},
										{
											"key": "account[access]",
											"value": "Public"
										},
										{
											"key": "contact[tag_list][]",
											"value": "0"
										},
										{
											"key": "contact[business_address_attributes][country]",
											"value": "us"
										},
										{
											"key": "contact[group_ids][]",
											"value": "1"
										},
										{
											"key": "",
											"value": "",
											"type": "text"
										}
									]
								},
								"url": {
									"raw": "localhost:3000/api/entities/contacts",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"contacts"
									]
								}
							},
							"response": []
						},
						{
							"name": "delete",
							"request": {
								"method": "POST",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": [
										{
											"key": "contact[user_id]",
											"value": "3"
										},
										{
											"key": "contact[first_name]",
											"value": "blajnjnef"
										},
										{
											"key": "account[user_id]",
											"value": "2"
										},
										{
											"key": "account[access]",
											"value": "Public"
										},
										{
											"key": "contact[tag_list][]",
											"value": "0"
										},
										{
											"key": "contact[business_address_attributes][country]",
											"value": "us"
										},
										{
											"key": "contact[group_ids][]",
											"value": "1"
										},
										{
											"key": "",
											"value": "",
											"type": "text"
										}
									]
								},
								"url": {
									"raw": "localhost:3000/api/entities/contacts/1/delete",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"contacts",
										"1",
										"delete"
									]
								}
							},
							"response": []
						},
						{
							"name": "update",
							"request": {
								"method": "POST",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": [
										{
											"key": "contact[user_id]",
											"value": "3"
										},
										{
											"key": "contact[first_name]",
											"value": "blajnjnef"
										},
										{
											"key": "account[user_id]",
											"value": "2"
										},
										{
											"key": "account[access]",
											"value": "Public"
										},
										{
											"key": "contact[tag_list][]",
											"value": "0"
										},
										{
											"key": "contact[business_address_attributes][country]",
											"value": "us"
										},
										{
											"key": "contact[group_ids][]",
											"value": "1"
										},
										{
											"key": "",
											"value": "",
											"type": "text"
										}
									]
								},
								"url": {
									"raw": "localhost:3000/api/entities/contacts/5",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"contacts",
										"5"
									]
								}
							},
							"response": []
						}
					]
				},
				{
					"name": "opportunitis",
					"item": [
						{
							"name": "all",
							"protocolProfileBehavior": {
								"disableBodyPruning": true
							},
							"request": {
								"method": "GET",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": [
										{
											"key": "query",
											"value": "h",
											"type": "text"
										}
									]
								},
								"url": {
									"raw": "localhost:3000/api/entities/opportunities",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"opportunities"
									]
								}
							},
							"response": []
						},
						{
							"name": "show",
							"protocolProfileBehavior": {
								"disableBodyPruning": true
							},
							"request": {
								"method": "GET",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": [
										{
											"key": "query",
											"value": "",
											"type": "text"
										}
									]
								},
								"url": {
									"raw": "localhost:3000/api/entities/opportunities/3",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"opportunities",
										"3"
									]
								}
							},
							"response": []
						},
						{
							"name": "delete",
							"request": {
								"method": "POST",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": [
										{
											"key": "query",
											"value": "",
											"type": "text"
										}
									]
								},
								"url": {
									"raw": "localhost:3000/api/entities/accounts/3/delete",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"accounts",
										"3",
										"delete"
									]
								}
							},
							"response": []
						},
						{
							"name": "update",
							"request": {
								"method": "POST",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": [
										{
											"key": "opportunity[user_id]",
											"value": "2",
											"type": "text"
										},
										{
											"key": "opportunity[name]",
											"value": "dfvdfvdfvdfv",
											"type": "text"
										},
										{
											"key": "account[user_id]",
											"value": "2",
											"type": "text"
										},
										{
											"key": "account[access]",
											"value": "Public",
											"type": "text"
										}
									]
								},
								"url": {
									"raw": "localhost:3000/api/entities/opportunities/4",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"opportunities",
										"4"
									],
									"query": [
										{
											"key": "opportunity[user_id]",
											"value": "2",
											"disabled": true
										},
										{
											"key": "opportunity[name]",
											"value": "estesdf",
											"disabled": true
										}
									]
								}
							},
							"response": []
						},
						{
							"name": "create",
							"request": {
								"method": "POST",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": [
										{
											"key": "opportunity[user_id]",
											"value": "2",
											"type": "text"
										},
										{
											"key": "opportunity[name]",
											"value": "dfvdfvdfvdfv",
											"type": "text"
										},
										{
											"key": "account[user_id]",
											"value": "2",
											"type": "text"
										},
										{
											"key": "account[access]",
											"value": "Public",
											"type": "text"
										}
									]
								},
								"url": {
									"raw": "localhost:3000/api/entities/opportunities",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"opportunities"
									],
									"query": [
										{
											"key": "opportunity[user_id]",
											"value": "2",
											"disabled": true
										},
										{
											"key": "opportunity[name]",
											"value": "estesdf",
											"disabled": true
										}
									]
								}
							},
							"response": []
						},
						{
							"name": "edit",
							"request": {
								"method": "GET",
								"header": [],
								"url": {
									"raw": "localhost:3000/api/entities/opportunities/3/edit",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"opportunities",
										"3",
										"edit"
									]
								}
							},
							"response": []
						}
					]
				},
				{
					"name": "campains",
					"item": [
						{
							"name": "all",
							"protocolProfileBehavior": {
								"disableBodyPruning": true
							},
							"request": {
								"method": "GET",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": [
										{
											"key": "query",
											"value": "hyddsec",
											"type": "text"
										}
									]
								},
								"url": {
									"raw": "localhost:3000/api/entities/campaigns",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"campaigns"
									]
								}
							},
							"response": []
						},
						{
							"name": "one",
							"request": {
								"method": "GET",
								"header": [],
								"url": {
									"raw": "localhost:3000/api/entities/campaigns/6/edit",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"campaigns",
										"6",
										"edit"
									]
								}
							},
							"response": []
						},
						{
							"name": "delete",
							"request": {
								"method": "POST",
								"header": [],
								"url": {
									"raw": "localhost:3000/api/entities/campaigns/5/delete",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"campaigns",
										"5",
										"delete"
									]
								}
							},
							"response": []
						},
						{
							"name": "update",
							"request": {
								"method": "POST",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": [
										{
											"key": "campaign[user_id]: 1\ncampaign[name]: Look sharp, feel sharp\ncampaign[starts_on]: 2018-06-05\ncampaign[ends_on]: 2018-07-14\ncampaign[status]: planned\ncampaign[tag_list][]: \ncampaign[tag_list][]: Products\ncampaign[tag_list][]: Homes\ncampaign[target_leads]: 137\ncampaign[target_conversion]: 24.0\ncampaign[target_revenue]: 998000\ncampaign[budget]: 347000\ncampaign[objectives]: Saepe corrupti harum neque repudiandae nihil dicta.\ncampaign[cf__]: \ncampaign[cf_campaign_type]: Simple\ncampaign[cf_checkiing_it][]: \ncampaign[cf_okokok][]: \ncampaign[cf_testtesttest]: \ncampaign[access]: Public\ncampaign[user_ids][]: \ncampaign[group_ids][]:",
											"value": "",
											"type": "text",
											"disabled": true
										},
										{
											"key": "campaign[user_id]",
											"value": "1",
											"type": "text"
										},
										{
											"key": "campaign[name]",
											"value": "This is the test, feel sharp",
											"type": "text"
										},
										{
											"key": "campaign[starts_on]",
											"value": "2018-06-05",
											"type": "text"
										}
									]
								},
								"url": {
									"raw": "localhost:3000/api/entities/campaigns/1",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"campaigns",
										"1"
									]
								}
							},
							"response": []
						},
						{
							"name": "create",
							"request": {
								"method": "POST",
								"header": [],
								"body": {
									"mode": "formdata",
									"formdata": [
										{
											"key": "campaign[user_id]: 1\ncampaign[name]: Look sharp, feel sharp\ncampaign[starts_on]: 2018-06-05\ncampaign[ends_on]: 2018-07-14\ncampaign[status]: planned\ncampaign[tag_list][]: \ncampaign[tag_list][]: Products\ncampaign[tag_list][]: Homes\ncampaign[target_leads]: 137\ncampaign[target_conversion]: 24.0\ncampaign[target_revenue]: 998000\ncampaign[budget]: 347000\ncampaign[objectives]: Saepe corrupti harum neque repudiandae nihil dicta.\ncampaign[cf__]: \ncampaign[cf_campaign_type]: Simple\ncampaign[cf_checkiing_it][]: \ncampaign[cf_okokok][]: \ncampaign[cf_testtesttest]: \ncampaign[access]: Public\ncampaign[user_ids][]: \ncampaign[group_ids][]:",
											"value": "",
											"type": "text",
											"disabled": true
										},
										{
											"key": "campaign[user_id]",
											"value": "1",
											"type": "text"
										},
										{
											"key": "campaign[name]",
											"value": "This is the test, feel sharpdce",
											"type": "text"
										},
										{
											"key": "campaign[starts_on]",
											"value": "2018-06-05",
											"type": "text"
										}
									]
								},
								"url": {
									"raw": "localhost:3000/api/entities/campaigns",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"campaigns"
									]
								}
							},
							"response": []
						},
						{
							"name": "show",
							"request": {
								"method": "GET",
								"header": [],
								"url": {
									"raw": "localhost:3000/api/entities/campaigns/10",
									"host": [
										"localhost"
									],
									"port": "3000",
									"path": [
										"api",
										"entities",
										"campaigns",
										"10"
									]
								}
							},
							"response": []
						}
					]
				}
			]
		},
		{
			"name": "API TEST ",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "localhost:3000/api/status",
					"host": [
						"localhost"
					],
					"port": "3000",
					"path": [
						"api",
						"status"
					]
				}
			},
			"response": []
		},
		{
			"name": "sign_in",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "email",
							"value": "dan@example.com",
							"type": "text"
						},
						{
							"key": "password",
							"value": "dan",
							"type": "text"
						},
						{
							"key": "authenticity_token",
							"value": "OSLmNAMZj5DDkOpRzLi0d70ZQEFPUvZQDBA42UFB0HgTUegGeFoikmlOxP9F15LAPAe056MK0zu41WiSJo/H0g==",
							"type": "text",
							"disabled": true
						}
					]
				},
				"url": {
					"raw": "localhost:3000/api/users/sign_in",
					"host": [
						"localhost"
					],
					"port": "3000",
					"path": [
						"api",
						"users",
						"sign_in"
					]
				}
			},
			"response": []
		}
	]
}