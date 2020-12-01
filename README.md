# ReadMeFile-practice
# Breakfast
Today I had a banana as 9 am lectures are too early.
Although a bowl of kraves is calling for me.

My LinkedIn account [Click Here for link](https://www.linkedin.com/in/will-bennett-14b94618a/)
![Image of an Octocat](https://mir-s3-cdn-cf.behance.net/projects/404/648905101021897.Y3JvcCwxMzE3LDEwMzAsMjkwLDMy.jpg)

## Ordered List of my favourite games:
1. Halo Reach
2. CSGO
3. Risk of Rain
4. Brawlhalla
5. Terraria

## Task list for Prp Dev:
- [x] Submit topic idea
- [x] Research around idea
- [ ] Complete topic essay
- [ ] Finish website
- [ ] Complete portfolio

## Code for GEC [Program 15 starry output]
int main()
{

	bool replay = true;
	char userInput;

	while (replay)
	{
		int lineNum;
		int starNum = 1;

		cout << "Enter a number between 1 and 10" << endl;
		cin >> lineNum;

		if (lineNum > 0 && lineNum < 11)
		{
			for (int i = lineNum; i > 0; i--)
			{
				//cout << "hello";
				for (int n = 0; n < starNum; n++)
				{
					cout << "*";

				}
				starNum++;
				cout << "\n";
			}
		}
		cout << "Do you want to have another go [Y/N]" << endl;
		cin >> userInput;
		if (userInput == 'y' || userInput == 'Y')
			cout << "replaying" << endl;


		else if (userInput == 'n' || userInput == 'N')
		{
			cout << "Goodbye";
			Sleep(1000);
			replay = false;
		}
	}

