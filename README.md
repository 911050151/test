
#include <opencv2\opencv.hpp>
#include <iostream>
#include <string>
using namespace cv;
using namespace std;
int main()
{
	Mat img = imread("12.jpg");
	if(img.empty())
	{
		cout<<"error";
		return -1;
	}
	imshow("xx的靓照",img);
	waitKey(0);
	return 0;
}
